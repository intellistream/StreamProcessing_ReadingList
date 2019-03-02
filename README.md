Stream Processing Systems ReadingList
--
Reading list of research works at stream processing. PR are welcome!

## Overall Surveys



## Early Prototypes (before 2005)

- TelegraphCQ: Continuous Dataflow Processing for an Uncertain World, CIDR'03 http://db.csail.mit.edu/madden/html/TCQcidr03.pdf
- Aurora: a new model and architecture for data stream management, VLDBJ'03 http://cs.brown.edu/research/aurora/vldb03_journal.pdf
- The Design of the Borealis Stream Processing Engine, CIDR'05 http://cidrdb.org/cidr2005/papers/P23.pdf


## New Directions

- Chi: A Scalable and Programmable Control Plane for Distributed Stream Processing Systems, VLDB'18 http://shivaram.org/publications/chi-vldb18.pdf

## APIs

- Stream Processing Languages in the Big Data Era, SIGMOD rec'05 https://sigmodrecord.org/publications/sigmodRecord/1806/pdfs/05_Surveys_Hirzel.pdf
- The CQL Continuous Query Language: Semantic Foundations and Query Execution, VLDBJ'06 https://dl.acm.org/citation.cfm?id=1146463
- Towards a Streaming SQL Standard, VLDB'08 http://cs.brown.edu/~ugur/streamsql.pdf

## Cost Model and Query Optimization

- Rate-Based Query Optimization for Streaming Information Sources, SIGMOD'02 http://research.cs.wisc.edu/niagara/papers/rates_crc.pdf
- Modeling Performance of a Parallel Streaming Engine: Bridging Theory and Costs, ICPE'13 https://dl.acm.org/citation.cfm?id=2479895
- A Holistic View of Stream Partitioning Costs, VLDB'17 http://www.vldb.org/pvldb/vol10/p1286-katsipoulakis.pdf


## Execution Engine

- Out-of-Order Processing: A New Architecture for High-Performance Stream Systems, VLDB'08 http://www.vldb.org/pvldb/1/1453890.pdf
- Drizzle: Fast and Adaptable Stream Processing at Scale, SOSP'17 http://shivaram.org/publications/drizzle-sosp17.pdf
- Adaptive Stream Processing using Dynamic Batch Sizing, SoCC'14 https://dl.acm.org/citation.cfm?id=2670995


## State Management

- A Survey of State Management in Big Data Processing Systems, VLDBJ'18 https://arxiv.org/pdf/1702.01596.pdf

## Elasticity

- Latency-aware Elastic Scaling for Distributed Data Stream Processing Systems, DEBS'14 https://dl.acm.org/citation.cfm?id=2611294
- Elastic Scaling for Data Stream Processing, TPDS'14 http://hirzels.com/martin/papers/tpds14-elastic.pdf
- Dynamic Load Balancing for Ordered Data-Parallel Regions in Distributed Streaming Systems, Middleware'16 http://cse.unl.edu/~ylu/csce990/papers/Dynamic%20Load%20Balancing%20for%20Ordered%20Data-Parallel%20Regions%20in%20Distributed%20Streaming%20Systems.pdf
- A Comprehensive Survey on Parallelization and Elasticity in Stream Processing, ACM Computing Surveys'19 https://arxiv.org/pdf/1901.09716.pdf

## Deterministic Stream Processing

- FlameStream: Model and Runtime for Distributed Stream Processing, BeyondMR'18 https://dl.acm.org/citation.cfm?id=3209273
- Deterministic Model for Distributed Speculative Stream Processing, ADBIS'18 https://link.springer.com/chapter/10.1007/978-3-319-98398-1_16
- Maximizing Determinism in Stream Processing Under Latency Constraints, DEBS'17 https://dl.acm.org/citation.cfm?id=3093921
- Sequence Pattern Query Processing over Out-of-Order Event Streams, ICDE'09 https://dspace.mit.edu/openaccess-disseminate/1721.1/59844
- Quality-Driven Disorder Handling for M-way Sliding Window Stream Joins, ICDE'16 https://ieeexplore.ieee.org/document/7498265
- Quality-driven disorder handling for concurrent windowed stream queries with shared operators, DEBS'16 https://dl.acm.org/citation.cfm?id=2933307
- An optimistic approach to handle out-of-order events within analytical stream processing, SEIM'18 http://ceur-ws.org/Vol-2135/SEIM_2018_paper_16.pdf

## AQP

- StreamApprox: Approximate Computing for Stream Analytics, Middleware'17 https://www.ruichuan.org/papers/streamapprox-middleware17.pdf
- Augmented Sketch: Faster and More Accurate Stream Processing, SIGMOD'16 http://www.ntu.edu.sg/home/arijit.khan/Papers/asketch.pdf
- An Online Approximate Stream Processing Framework with Customized Error Control, IEEE IWQoS'18 http://iwqos2018.ieee-iwqos.org/files/2018/05/An_Online_Approximate_Stream_Processing_Framework.pdf


## Stream Processing on New Hardware

### Cell Processor (died?)
- CellJoin: a parallel stream join operator for the cell processor, VLDB'09 https://dl.acm.org/citation.cfm?id=1527463

### FPGA
- A Computing Origami: Folding Streams in FPGAs, DAC'09 https://www.comp.nus.edu.sg/~wongwf/papers/DAC09_Andrei.pdf
- An FPGA-based High-Throughput Stream Join Architecture https://www.extrahpc.eu/media/public/publicity/publication/an-fpga-based-high-throughput-stream-join-architecture.pdf
- Streams on Wires — A Query Compiler for FPGAs, VLDB'09 https://dl.acm.org/citation.cfm?id=1687654

### GPU

- GStream: A General-Purpose Data Streaming Framework on GPU Clusters, ICPP'11 http://optout.csc.ncsu.edu/~mueller/ftp/pub/mueller/papers/icpp11-1.pdf
- A Scalable Software Framework for Stateful Stream Data Processing on Multiple GPUs and Applications, GPU Computing and Applications'14  https://link.springer.com/chapter/10.1007/978-981-287-134-3_7
- G-Storm: GPU-enabled high-throughput online data processing in Storm, BIG DATA '15 https://dl.acm.org/citation.cfm?id=2878053
- Communication-aware mapping of stream graphs for multi-GPU platforms, CGO’16 https://dl.acm.org/citation.cfm?id=2854055
- GStreamMiner: A GPU-accelerated Data Stream Mining Framework, CIKM'16 https://dl.acm.org/citation.cfm?id=2983341
- SABER: Window-Based Hybrid Stream Processing for Heterogeneous Architectures, SIGMOD'16 https://www.matthiasweidlich.com/paper/saber_SIGMOD_2016.pdf
- TerseCades: Efficient Data Compression in Stream Processing, ATC'18 https://www.usenix.org/system/files/conference/atc18/atc18-pekhimenko.pdf

### Multicore, Manycore processor
- Auto-pipelining for Data Stream Processing, TPDS'13 https://tristartom.github.io/docs/tpds13.pdf
- Low Power and Scalable Many-Core Architecture for Big-Data Stream Computing,VLSI'14, http://medianetlab.ee.ucla.edu/papers/ISVLSI_FINAL.pdf
- Trill: A High-Performance Incremental Query Processor for Diverse Analytics, VLDB'14 https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/trill-vldb2015.pdf
- A Cost Model for Data Stream Processing on Modern Hardware, ADMS'17 https://pdfs.semanticscholar.org/4806/7dc25203e351444a60e502adab45bf543c9d.pdf
- Revisiting the Design of Data Stream Processing Systems on Multi-Core Processors, ICDE'17 https://www.comp.nus.edu.sg/~hebs/pub/shuhaoICDE17a.pdf
- StreamBox: Modern Stream Processing on a Multicore Machine, ATC'17 https://www.usenix.org/system/files/conference/atc17/atc17-miao.pdf
- Scaling Ordered Stream Processing on Shared-Memory Multicores, 	arXiv'18 https://arxiv.org/abs/1803.11328
- Exploiting Manycore Architectures for Parallel Data Stream Processing, GI-Workshop'18, http://ceur-ws.org/Vol-1858/paper13.pdf
- Hammer Slide: Work- and CPU-efficient Streaming Window Aggregation, ADMS'18 https://spiral.imperial.ac.uk/bitstream/10044/1/62249/2/SIMDWindowPaper_ADMS.pdf

### Infiniband
- Low latency stream processing: Apache Heron with Infiniband & Intel Omni-Path, UCC’17 http://dsc.soic.indiana.edu/publications/Heron_Infiniband.pdf

### SSD
- High-Performance Stateful Stream Processing on Solid-State Drives, APSys'18 http://spl.snu.ac.kr/wp-content/uploads/2012/07/a9-lee.pdf

### HBM
- StreamBox-HBM: Stream Analytics on High Bandwidth Hybrid Memory, ASPLOS'19 https://arxiv.org/pdf/1901.01328.pdf
- Stream Processing on High-Bandwidth Memory, GI-Workshop'18 http://ceur-ws.org/Vol-2126/paper6.pdf

## Stream Processing with Machine Learning

- A Framework for Real-time Streaming Analytics using Machine Learning Approach, ICCST'14 https://ieeexplore.ieee.org/document/6987044/
- Online Machine Learning in Big Data Streams, arXiv'18 https://arxiv.org/pdf/1802.05872.pdf

