# Introduction: #
Periodic-frequent patterns play a crucial role in identifying regularities within temporal databases. While existing studies primarily focus on mining such patterns from precise data, this is not applicable to real-world applications where data uncertainty is inherent. Recognizing this, researchers have recently directed their attention towards mining periodic frequent patterns from uncertain data. However, the computational complexity of finding these patterns is expensive due to the enormous search space, which grows exponentially with the number of items in the database. To address this challenge, previous studies have proposed novel tree structures and upper-bound constraints. In our observation, we have discovered a potential avenue for reducing the search space. In this thesis, we focus on developing novel algorithm to find periodic-frequent patterns in uncertain databases. We introduce a novel and tighter-upper bound constraint named "cutoff expected support" (CES) to reduce the search space. This constraint exploits the anti-monotonic nature of the probability (i.e., probability decreases with the increase in the number of items that have to occur simultaneously). This constraint determines whether a superset of a pattern can be a periodic-frequent pattern in a database. Additionally, we present an efficient depth-first search algorithm, called Uncertain Periodic-Frequent Pattern-growth++ (UPFP-growth++), which effectively discovers the complete set of desired patterns in a database. Empirical evaluations conducted on real-world and synthetic databases demonstrate that CES significantly reduces the search space, and UPFP-growth++ exhibits excellent efficiency in pattern discovery.

# This Github repository contains the files needed for execution: #
* Algorithms:
    * UPFPGrowth
    * UPFPGrowth++
* Datasets:
  * "uncertain_Temporal_T10I4D1200K.csv"
  * "uncertain_Tempora_Retail.csv"


- Executing Notebooks:
  - T10I4D200K.ipynb

**This work was done by PALLA Likhitha under the masters programme.**
