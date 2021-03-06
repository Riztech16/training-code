- What is the lineage of an RDD?
- How can we see the Lineage?
- What do the indentations mean in the printed lineage?
- What is the logical plan?  The physical plan?
- How many partitions does a single task work on?
- What’s the difference between cluster mode and client mode on YARN?
- What is an executor?  What are executors when we run Spark on YARN?
- What is AWS?
- EC2?
- S3?
- EMR?
- What does it mean to run an EMR Step Execution?
- What are some benefits to using the cloud?
- What is the Spark History Server?
- What does it mean to “spill to disk” when executing spark tasks?
- Why can Spark skip entire stages if they are the same between jobs?
- What is a reasonable number of partitions for Spark?
- When during a Job do we need to pay attention to the number of partitions and adjust if necessary?
- What is spark.driver.memory?  What about spark.executor.memory?
- What are some steps we can take to debug a Spark Application?

- What is a Spark Application? Job? Stage? Task?
- When we cache an RDD, can we use it across Tasks? Stages? Jobs?
  - NOTE: Adam had this question wrong in Wed notes! it's fixed now
- What are Persistence Storage Levels in Spark?
  - Some levels have _SER, what does this mean?
  - Some levels have _2, what does this mean?
  - If the storage level for a persist is MEMORY_ONLY and there isn't enough memory, what happens?
- What is the storage level for .cache()?