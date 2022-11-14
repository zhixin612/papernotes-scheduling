

# Paper notes - Scheduling & Networked Systems

[![](https://img.shields.io/github/repo-size/gg-lc/papernotes-scheduling?label=repo%20size)](https://github.com/gg-lc/papernotes-scheduling) [![](https://img.shields.io/github/directory-file-count/gg-lc/papernotes-scheduling/paper?label=total%20papers&labelColor=gray&color=red)](paper)

### Materials

* CCF list 2019: [[chinese](materials/CCF_chinese.pdf)] [[international](materials/CCF_international.pdf)]

[//]: https://img.shields.io/static/v1.svg?label=abc&amp;message=abc&amp;color=blue&amp;labelColor=gray
[//]: https://blog.csdn.net/luo15242208310/article/details/114530777

### To read (learn)

* The Tail in Scale
* FA2 [source code]()
* (OSDI'20) **[Serving DNNs like Clockwork: Performance Predictability from the Bottom Up](https://www.usenix.org/conference/osdi20/presentation/gujarati)**  [![](https://img.shields.io/static/v1.svg?label=&logo=github&labelColor=gray&message=CODE/cpp&color=blue)](https://gitlab.mpi-sws.org/cld/ml/clockwork)
* (SC'20) **[BATCH: Machine Learning Inference Serving on Serverless Platforms with Adaptive Batching](https://ieeexplore.ieee.org/document/9355312)**
* (NSDI'17) **Clipper**: A Low-Latency Online Prediction Serving System
* (ATC'21) InFaas: Automated Model-less Inference Serving
* (OSDI'20) **AntMan**: Dynamic Scaling on GPU Clusters for Deep Learning
* (SoCC'21) Llama: A Heterogeneous & Serverless Framework for Auto-Tuning Video Analytics Pipelines
* (OSDI'18) **Gandiva**: introspective cluster scheduling for deep learning
* (Middleware'17) Swayam: distributed autoscaling to meet SLAs of machine learning inference services with resource efficiency
* **[partial]** Borg; RAS; Trarfik; Ngnix; [blog](https://logz.io/blog/best-open-source-load-balancers/)
* **[low priority]**: MapReduce; GFS; BigTable
* **[low priority]** Spanner(google); B4; Dynamo
* **[book]**: Designing Data-Intensive Applications

----

### 2022.11

* AntMan
* BATCH
* INFless
  * Problem
  * Insights
  * Solution
  * Other

* **[MArk: Exploiting Cloud Services for Cost-Effective, SLO-Aware Machine Learning Inference Serving]()** ![](https://img.shields.io/static/v1.svg?label=[A]&message=ATC'19&color=purple) [![](https://img.shields.io/static/v1.svg?label=&logo=github&labelColor=gray&message=CODE/py&color=blue)](https://github.com/marcoszh/MArk-Project)
  * Problem

  * Insights

  * Solution

  * Other

* [**Serverless**] :bookmark: **[Cloud Programming Simplified: A Berkeley View on Serverless Computing](https://arxiv.org/abs/1902.03383)** ![](https://img.shields.io/static/v1.svg?label=[-]&message=ArXiv&color=purple)
  * history of cloud computing
  * motivations for serverless computing
  * limitations of serverless
* [**Serverless**] **[Evaluation of Production Serverless Computing Environments](https://ieeexplore.ieee.org/abstract/document/8457830/)** ![](https://img.shields.io/static/v1.svg?label=[C]&message=CoCC'18&color=purple)
  * evaluates the performance of production serverless
  *  "serverless is powered by container technologies which have **near zero start-up delay and deleting latency**."
  * "a container is **deployed and terminated within a few milliseconds** for the function invocation **w/ pre warmup** policy"
* [**Serverless**] **[Serverless in the Wild: Characterizing and Optimizing the Serverless Workload at a Large Cloud Provider](https://www.usenix.org/conference/atc20/presentation/shahrad)** ![](https://img.shields.io/static/v1.svg?label=[A]&message=ATC'20&color=purple)
  * characterize the FaaS workload of Azure Functions
  * propose a practical resource management policy to **reduce the number of cold starts**
* [**Serverless**] :bookmark: **[Xanadu: Mitigating cascading cold starts in serverless function chain deployments](https://dl.acm.org/doi/10.1145/3423211.3425690)** ![](https://img.shields.io/static/v1.svg?label=[B]&message=Middleware'20&color=purple)
  * (pipeline) **deploy resources for the execution chain** before traffic bursts
  * **cascading cold start** increase linearly with chain length

### 2022.10

* **InferLine: latency-aware provisioning and scaling for prediction serving pipelines** ![](https://img.shields.io/static/v1.svg?label=[A]&message=SoCC'20&color=purple)
  * Problem

  * Insight

  * Solution

  * Other

* [**Spot instance**] **Tributary: spot-dancing for elastic services with latency SLOs** [![](https://img.shields.io/static/v1.svg?label=[A]&message=ATC'18&color=purple)](https://www.usenix.org/conference/atc18/presentation/harlap)
  * Transient Instance (AWS Spot Instance)
  * **Trace**: ClarkNet & WITS & ...

* [**Spot instance**] **Cocktail: A Multidimensional Optimization for Model Serving in Cloud** [![](https://img.shields.io/static/v1.svg?label=[A]&message=NSDI'22&color=purple)](https://www.usenix.org/conference/nsdi22/presentation/gunasekaran) [![](https://img.shields.io/static/v1.svg?label=&logo=github&labelColor=gray&message=CODE/py&color=blue)](https://github.com/jashwantraj92/cocktail)
  * Ensemble Learning
  * Transient Instance
  * "DeepAR-estimator"
  * **Trace**: Wikipedia & tweet


### 2022.09

* **Twine: A Unified Cluster Management System for Shared Infrastructure** [![](https://img.shields.io/static/v1.svg?label=[A]&message=OSDI'20&color=purple)](https://www.usenix.org/conference/osdi20/presentation/tang) [![](https://img.shields.io/static/v1.svg?label=📑&message=Blog&color=ffa000)](https://engineering.fb.com/2019/06/06/data-center-engineering/twine/)
* **Shard Manager: A Generic Shard Management Framework for Geo-distributed Applications** [![](https://img.shields.io/static/v1.svg?label=[A]&message=SOSP'21&color=purple)](https://dl.acm.org/doi/10.1145/3477132.3483546) [![](https://img.shields.io/static/v1.svg?label=📑&message=Blog&color=ffa000)](https://engineering.fb.com/2020/08/24/production-engineering/scaling-services-with-shard-manager/)
* **Autopilot: workload autoscaling at Google** [![](https://img.shields.io/static/v1.svg?label=[B]&message=EuroSys'20&color=purple)](https://dl.acm.org/doi/abs/10.1145/3342195.3387524)
* **Piccolo: ---**

### 2022

* **Scrooge: A Cost-Effective Deep Learning Inference System** [![](https://img.shields.io/static/v1.svg?label=[B]&message=SoCC'21&color=purple)](https://dl.acm.org/doi/10.1145/3472883.3486993)

* **Nexus: A GPU Cluster Engine for Accelerating DNN-Based Video Analysis** [![](https://img.shields.io/static/v1.svg?label=[A]&labelColor=gray&message=SOSP'19&color=purple)](https://dl.acm.org/doi/10.1145/3341301.3359658) [![](https://img.shields.io/static/v1.svg?label=&logo=github&labelColor=gray&message=CODE/cpp&color=blue)](https://github.com/uwsampl/nexus)

* **[AutoScale: Dynamic, Robust Capacity Management for Multi-Tier Data Centers](https://dl.acm.org/doi/10.1145/2382553.2382556)** ![](https://img.shields.io/static/v1.svg?label=[A]&labelColor=gray&message=TOCS'12&color=purple)

  

------


### Template:

* :smirk::heart::bookmark: [Template: An example](paper/xx.pdf) [GPU Scheduling] [![](https://img.shields.io/static/v1.svg?label=📑&message=NOTE&color=red)](notes/xxx.md) [![](https://img.shields.io/static/v1.svg?label=🌐&message=ArXiv&color=purple)](https://www.usenix.org/conference/osdi22) [![](https://img.shields.io/static/v1.svg?label=&logo=github&labelColor=gray&message=CODE&color=blue)](https://github.com/gg-lc/papernotes-rlsys) [![](https://img.shields.io/static/v1.svg?label=📺&message=slides&color=green)](/materials/xx.pdf) [![](https://img.shields.io/static/v1.svg?label=&labelColor=gray&logo=youtube&logoColor=red&message=TALK&color=yellow)](https://papertalk.org/index) [![](https://img.shields.io/static/v1.svg?label=📑&message=Blog&color=ffa000)](link)

