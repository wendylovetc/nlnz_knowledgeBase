# (2020) The Case for Alternative Web Archival Formats to Expedite the Data-To-Insight Cycle

Xinyue Wang, Zhiwu Xie

## Highlights

+ The WARC format performs bad for batch processing workload due to its *data structure, encoding, and addressing method.*
+ Better performance can be easily achieved by reformatting WARC files into *Parquet* or *Avro* formats.

![image-20231128121201369](./literature_review.assets/image-20231128121201369.png)

**Figure 1.** Comparing WARC-CDX, Parquet, and Avro

<img src="./literature_review.assets/image-20231128121206975.png" alt="image-20231128121206975" style="zoom:50%;" />

**Figure 2.** Use predicate pushdown and projection pushdown to skip reading unnecessary row groups or columns in Parquet data
