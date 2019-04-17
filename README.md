Stream Processing Systems ReadingList
--
Reading list of research works at stream processing. PR are welcome!

# Hardware Consious Stream Processing 

## Experimental study

- Evaluation of Streaming Aggregation on Parallel Hardware Architectures, DEBS'10 https://www.scott-a-s.com/files/debs2010.pdf.
- Revisiting the Design of Data Stream Processing Systems on Multi-Core Processors, ICDE'17 https://www.comp.nus.edu.sg/~hebs/pub/shuhaoICDE17a.pdf
- Analyzing Efficient Stream Processing on Modern Hardware, VLDB'19 http://www.vldb.org/pvldb/vol12/p516-zeuch.pdf

## Accelerating Expensive Operator

### Stream Join
- CellJoin: a parallel stream join operator for the cell processor, VLDB'09 https://dl.acm.org/citation.cfm?id=1527463
- How Soccer Players Would do Stream Joins, SIGMOD'11 http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.362.2471&rep=rep1&type=pdf
- Stream Join Processing on Heterogeneous Processors, BTW workshop'13 https://www.semanticscholar.org/paper/Stream-Join-Processing-on-Heterogeneous-Processors-Karnagel-Schlegel/1678406ae271c6a421510a3cf811e95978dc51ae
- Low-Latency Handshake Join, VLDB'14 http://www.vldb.org/pvldb/vol7/p709-roy.pdf
- SplitJoin: A Scalable, Low-latency Stream Join Architecture with Adjustable Ordering Precision, ATC'16 https://www.usenix.org/system/files/conference/atc16/atc16_paper-najafi.pdf
- An FPGA-based High-Throughput Stream Join Architecture, FPL'16 https://www.extrahpc.eu/media/public/publicity/publication/an-fpga-based-high-throughput-stream-join-architecture.pdf
- PanJoin: A Partition-based Adaptive Stream Join, arxiv'18 https://arxiv.org/abs/1811.05065
- Parallel Index-based Stream Join on a Multicore CPU, arxiv'19 https://arxiv.org/pdf/1903.00452.pdf

### Stream Aggregate
- An Efficient and Scalable Implementation of Sliding-Window Aggregate Operator on FPGA, CANDAR'13 https://core.ac.uk/download/pdf/147692472.pdf
- FPGA-Accelerated Group-by Aggregation Using Synchronizing Caches, DaMoN '16 https://dl.acm.org/citation.cfm?id=2933360
- Single window stream aggregation using reconfigurable hardware, ICFPT'17 https://ieeexplore.ieee.org/abstract/document/8280128
- Hammer Slide: Work- and CPU-efficient Streaming Window Aggregation, ADMS'18 https://spiral.imperial.ac.uk/bitstream/10044/1/62249/2/SIMDWindowPaper_ADMS.pdf
- Scotty: Efficient Window Aggregation for out-of-order Stream Processing, ICDE'18

### Deterministic Operator
- Scalejoin: A deterministic, disjoint-parallel and skew-resilient stream join, 2015 IEEE International Conference on Big Data (Big Data) http://www.cse.chalmers.se/~ioaniko/docs/bigdata15.pdf
- StreamBox: Modern Stream Processing on a Multicore Machine, ATC'17 https://www.usenix.org/system/files/conference/atc17/atc17-miao.pdf
- Scaling Ordered Stream Processing on Shared-Memory Multicores, 	arXiv'18 https://arxiv.org/abs/1803.11328


## Efficient Stream Flow
### In-DAG Stream Flow
- TerseCades: Efficient Data Compression in Stream Processing, ATC'18 https://www.usenix.org/system/files/conference/atc18/atc18-pekhimenko.pdf
- Low latency stream processing: Apache Heron with Infiniband & Intel Omni-Path, UCC’17 http://dsc.soic.indiana.edu/publications/Heron_Infiniband.pdf
- StreamBox-HBM: Stream Analytics on High Bandwidth Hybrid Memory, ASPLOS'19 https://arxiv.org/pdf/1901.01328.pdf
- Stream Processing on High-Bandwidth Memory, GI-Workshop'18 http://ceur-ws.org/Vol-2126/paper6.pdf
### Out-DAG Stream Flow
- High-Performance Stateful Stream Processing on Solid-State Drives, APSys'18 http://spl.snu.ac.kr/wp-content/uploads/2012/07/a9-lee.pdf
- An NVM-Aware Storage Layout for Analytical Workloads, http://www.carch.ac.cn/~ictdb/HardBD-Active-2018/papers/GotzeBS-hardbd-active-18.pdf
- Energy-Efficient Streaming Using Non-volatile Memory, https://link.springer.com/content/pdf/10.1007%2Fs11265-008-0308-1.pdf

## HW-Conscious Query Optimization
### Multisocket, multicore
- Orchestrating the Execution of Stream Programs on Multicore Platforms, PLDI'08 https://dl.acm.org/citation.cfm?id=1375596
- Mapping Stream Programs onto Heterogeneous Multiprocessor Systems, CASES '09 https://dl.acm.org/citation.cfm?id=1629395.1629406
- MacroSS: macro-SIMDization of streaming applications, ASPLOS'10 https://dl.acm.org/citation.cfm?id=1736020.1736053
- Orchestration by approximation: mapping stream programs onto multicore architectures, ASPLOS'11 https://dl.acm.org/citation.cfm?id=1950406
- Cache-Conscious Scheduling of Streaming Applications, SPAA'12 https://dspace.mit.edu/bitstream/handle/1721.1/90261/leiserson_cache-conscious.pdf?sequence=1
- Auto-pipelining for Data Stream Processing, TPDS'13 https://tristartom.github.io/docs/tpds13.pdf
- Low Power and Scalable Many-Core Architecture for Big-Data Stream Computing,VLSI'14, http://medianetlab.ee.ucla.edu/papers/ISVLSI_FINAL.pdf
- Trill: A High-Performance Incremental Query Processor for Diverse Analytics, VLDB'14 https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/trill-vldb2015.pdf
- A Cost Model for Data Stream Processing on Modern Hardware, ADMS'17 https://pdfs.semanticscholar.org/4806/7dc25203e351444a60e502adab45bf543c9d.pdf
- Exploiting Manycore Architectures for Parallel Data Stream Processing, GI-Workshop'18, http://ceur-ws.org/Vol-1858/paper13.pdf
### FPGA
- A Computing Origami: Folding Streams in FPGAs, DAC'09 https://www.comp.nus.edu.sg/~wongwf/papers/DAC09_Andrei.pdf
- Streams on Wires — A Query Compiler for FPGAs, VLDB'09 https://dl.acm.org/citation.cfm?id=1687654
- Multi-query Stream Processing on FPGAs, ICDE'12 https://ieeexplore.ieee.org/document/6228175
- Flexible query processor on FPGAs, VLDB'13 (demo) https://dl.acm.org/citation.cfm?id=2536303

### GPGPU
- Software Pipelined Execution of Stream Programs on GPUs, CGO'09 https://ieeexplore.ieee.org/document/4907664
- Sponge: Portable Stream Programming on Graphics Engines, ASPLOS'11 https://dl.acm.org/citation.cfm?id=1950409
- Automated Architecture-Aware Mapping of Streaming Applications Onto GPUs, IPDPS'11 https://ieeexplore.ieee.org/document/6012816
- GStream: A General-Purpose Data Streaming Framework on GPU Clusters, ICPP'11 http://optout.csc.ncsu.edu/~mueller/ftp/pub/mueller/papers/icpp11-1.pdf
- Processing data streams with hard real-time constraints on heterogeneous systems, ICS'11 https://dl.acm.org/citation.cfm?id=1995915
- Scheduling processing of real-time data streams on heterogeneous multi-GPU systems, SYSTOR 2012 http://www.cs.technion.ac.il/~uriv/Publications/ver-multigpu-systor12-authorcopy.pdf
- A Scalable Software Framework for Stateful Stream Data Processing on Multiple GPUs and Applications, GPU Computing and Applications'14  https://link.springer.com/chapter/10.1007/978-981-287-134-3_7
- Toward GPU Accelerated Data Stream Processing, GI-Workshop'15 http://ceur-ws.org/Vol-1366/paper15.pdf
- A holistic approach to build real-time stream processing system with GPU，J. Parallel Distrib. Comput. 2015 https://www.sciencedirect.com/science/article/pii/S0743731515000921
- G-Storm: GPU-enabled high-throughput online data processing in Storm, BIG DATA '15 https://dl.acm.org/citation.cfm?id=2878053
- Communication-aware mapping of stream graphs for multi-GPU platforms, CGO’16 https://dl.acm.org/citation.cfm?id=2854055
- GStreamMiner: A GPU-accelerated Data Stream Mining Framework, CIKM'16 https://dl.acm.org/citation.cfm?id=2983341
- SABER: Window-Based Hybrid Stream Processing for Heterogeneous Architectures, SIGMOD'16 https://www.matthiasweidlich.com/paper/saber_SIGMOD_2016.pdf

## Complex Event Processing

### Partition by key
Partition and Compose: Parallel Complex Event Processing, DEBS ’12 http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.374.1592&rep=rep1&type=pdf

### Run-based
RIP: run-based intra-query parallelism for scalable complex event processing, DEBS'13 https://dl.acm.org/citation.cfm?id=2488257



# General Stream Processing 

## Surveys

- Tutorial: Sliding-Window Aggregation Algorithms, http://hirzels.com/martin/papers/debs17-tutorial.pdf
- A Survey of State Management in Big Data Processing Systems, VLDBJ'18 https://arxiv.org/pdf/1702.01596.pdf
- A SURVEY OF JOIN PROCESSING IN DATA STREAMS, 2006 http://db.cs.duke.edu/papers/2006-xy-sjoinbook.pdf 
## Early Prototypes (before 2005)

- TelegraphCQ: Continuous Dataflow Processing for an Uncertain World, CIDR'03 http://db.csail.mit.edu/madden/html/TCQcidr03.pdf
- Aurora: a new model and architecture for data stream management, VLDBJ'03 http://cs.brown.edu/research/aurora/vldb03_journal.pdf
- The Design of the Borealis Stream Processing Engine, CIDR'05 http://cidrdb.org/cidr2005/papers/P23.pdf


## New Directions

- Chi: A Scalable and Programmable Control Plane for Distributed Stream Processing Systems, VLDB'18 http://shivaram.org/publications/chi-vldb18.pdf
- New Techniques to Curtail the Tail Latency in Stream Processing Systems, DCC'16 http://dprg.cs.uiuc.edu/docs/tail_latency_DCC16/lower_the_tail_latency_of_storm.pdf 

## APIs

- Stream Processing Languages in the Big Data Era, SIGMOD rec'05 https://sigmodrecord.org/publications/sigmodRecord/1806/pdfs/05_Surveys_Hirzel.pdf
- The CQL Continuous Query Language: Semantic Foundations and Query Execution, VLDBJ'06 https://dl.acm.org/citation.cfm?id=1146463
- Towards a Streaming SQL Standard, VLDB'08 http://cs.brown.edu/~ugur/streamsql.pdf

## Cost Model and Query Optimization

- Rate-Based Query Optimization for Streaming Information Sources, SIGMOD'02 http://research.cs.wisc.edu/niagara/papers/rates_crc.pdf
- Modeling Performance of a Parallel Streaming Engine: Bridging Theory and Costs, ICPE'13 https://dl.acm.org/citation.cfm?id=2479895
- A Holistic View of Stream Partitioning Costs, VLDB'17 http://www.vldb.org/pvldb/vol10/p1286-katsipoulakis.pdf
- Maximizing the Output Rate of Multi-Way Join Queries over Streaming Information Sources, VLDB'03 http://www.vldb.org/conf/2003/papers/S10P01.pdf

## Execution Engine

- Out-of-Order Processing: A New Architecture for High-Performance Stream Systems, VLDB'08 http://www.vldb.org/pvldb/1/1453890.pdf
- Drizzle: Fast and Adaptable Stream Processing at Scale, SOSP'17 http://shivaram.org/publications/drizzle-sosp17.pdf
- Adaptive Stream Processing using Dynamic Batch Sizing, SoCC'14 https://dl.acm.org/citation.cfm?id=2670995
- Sub-O(log n) Out-of-Order Sliding-Window Aggregation, https://arxiv.org/pdf/1810.11308.pdf
- Cutty: Aggregate Sharing for User-Defined Windows, CIKM '16  https://dl.acm.org/citation.cfm?id=2983807

## Availability 
- High-Availability Algorithms for Distributed Stream Processing, ICDE'05 http://cs.brown.edu/research/aurora/hwang.icde05.ha.pdf
- Fault-tolerant Stream Processing using a Distributed, Replicated File System, VLDB'08 http://www.vldb.org/pvldb/1/1453920.pdf

## Elasticity

- Latency-aware Elastic Scaling for Distributed Data Stream Processing Systems, DEBS'14 https://dl.acm.org/citation.cfm?id=2611294
- Elastic Scaling for Data Stream Processing, TPDS'14 http://hirzels.com/martin/papers/tpds14-elastic.pdf
- Dynamic Load Balancing for Ordered Data-Parallel Regions in Distributed Streaming Systems, Middleware'16 http://cse.unl.edu/~ylu/csce990/papers/Dynamic%20Load%20Balancing%20for%20Ordered%20Data-Parallel%20Regions%20in%20Distributed%20Streaming%20Systems.pdf
- A Comprehensive Survey on Parallelization and Elasticity in Stream Processing, ACM Computing Surveys'19 https://arxiv.org/pdf/1901.09716.pdf

## Deterministic Stream Processing
- Sequence Pattern Query Processing over Out-of-Order Event Streams, ICDE'09 https://dspace.mit.edu/openaccess-disseminate/1721.1/59844
- High-Performance Dynamic Pattern Matching over Disordered Streams, VLDB'10 http://vldb.org/pvldb/vldb2010/pvldb_vol3/R19.pdf
- Reliable speculative processing of out-of-order event streams in generic publish/subscribe middlewares, DEBS '13 https://dl.acm.org/citation.cfm?id=2488263
- FlameStream: Model and Runtime for Distributed Stream Processing, BeyondMR'18 https://dl.acm.org/citation.cfm?id=3209273
- Deterministic Model for Distributed Speculative Stream Processing, ADBIS'18 https://link.springer.com/chapter/10.1007/978-3-319-98398-1_16
- Maximizing Determinism in Stream Processing Under Latency Constraints, DEBS'17 https://dl.acm.org/citation.cfm?id=3093921
- Quality-Driven Disorder Handling for M-way Sliding Window Stream Joins, ICDE'16 https://ieeexplore.ieee.org/document/7498265
- Quality-driven disorder handling for concurrent windowed stream queries with shared operators, DEBS'16 https://dl.acm.org/citation.cfm?id=2933307
- An optimistic approach to handle out-of-order events within analytical stream processing, SEIM'18 http://ceur-ws.org/Vol-2135/SEIM_2018_paper_16.pdf

## AQP

- StreamApprox: Approximate Computing for Stream Analytics, Middleware'17 https://www.ruichuan.org/papers/streamapprox-middleware17.pdf
- Augmented Sketch: Faster and More Accurate Stream Processing, SIGMOD'16 http://www.ntu.edu.sg/home/arijit.khan/Papers/asketch.pdf
- An Online Approximate Stream Processing Framework with Customized Error Control, IEEE IWQoS'18 http://iwqos2018.ieee-iwqos.org/files/2018/05/An_Online_Approximate_Stream_Processing_Framework.pdf

## others
- P4CEP: Towards In-Network Complex Event Processing, NetCompute '18, https://dl.acm.org/citation.cfm?id=3229593
- NVStream: accelerating HPC workflows with NVRAM-based transport for streaming objects, HPDC '18 https://dl.acm.org/citation.cfm?id=3208061 NOTE: not stream processing.
- A Framework for Real-time Streaming Analytics using Machine Learning Approach, ICCST'14 https://ieeexplore.ieee.org/document/6987044/
- Online Machine Learning in Big Data Streams, arXiv'18 https://arxiv.org/pdf/1802.05872.pdf
- Online Learning and Stochastic Approximations, https://leon.bottou.org/publications/pdf/online-1998.pdf
