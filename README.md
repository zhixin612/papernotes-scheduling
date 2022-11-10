

# Paper notes - Scheduling & Networked Systems

[![](https://img.shields.io/github/repo-size/gg-lc/papernotes-scheduling?label=repo%20size)](https://github.com/gg-lc/papernotes-scheduling) [![](https://img.shields.io/github/directory-file-count/gg-lc/papernotes-scheduling/paper?label=total%20papers&labelColor=gray&color=red)](paper)

### Materials

* CCF list 2019: [[chinese](materials/CCF_chinese.pdf)] [[international](materials/CCF_international.pdf)]

[//]: https://img.shields.io/static/v1.svg?label=abc&amp;message=abc&amp;color=blue&amp;labelColor=gray
[//]: https://blog.csdn.net/luo15242208310/article/details/114530777

### To read (learn)

* The Tail in Scale
* FA2 [source code]()
* INFLess: ...
  * problem: whether severless can reduce or eliminate the model cold start time?

* Clipper: A Low-Latency Online Prediction Serving System ![](https://img.shields.io/static/v1.svg?label=[A]&message=NSDI'17&color=purple)
* InFaas: Automated Model-less Inference Serving ![](https://img.shields.io/static/v1.svg?label=[A]&message=ATC'21&color=purple)
* AntMan: Dynamic Scaling on GPU Clusters for Deep Learning ![](https://img.shields.io/static/v1.svg?label=[A]&message=OSDI'20&color=purple)
* 
* Llama: A Heterogeneous & Serverless Framework for Auto-Tuning Video Analytics Pipelines ![](https://img.shields.io/static/v1.svg?label=[A]&message=SoCC'21&color=purple)
* Gandiva: introspective cluster scheduling for deep learning ![](https://img.shields.io/static/v1.svg?label=[A]&message=OSDI'18&color=purple)
* Swayam: distributed autoscaling to meet SLAs of machine learning inference services with resource efficiency ![](https://img.shields.io/static/v1.svg?label=[B]&message=Middleware'17&color=purple)
* MArk: Exploiting Cloud Services for Cost-Effective, SLO-Aware Machine Learning Inference Serving ![](https://img.shields.io/static/v1.svg?label=[A]&message=ATC'19&color=purple)
* **[partial]** Borg; RAS; Trarfik; Ngnix; [blog](https://logz.io/blog/best-open-source-load-balancers/)
* **[low priority]**: MapReduce; GFS; BigTable
* **[low priority]** Spanner(google); B4; Dynamo
* **[book]**: Designing Data-Intensive Applications

----

### 2022.11

* INFless
* MArk

* [Serverless] **[Cloud Programming Simplified: A Berkeley View on Serverless Computing](https://arxiv.org/abs/1902.03383)**
  * history of cloud computing
  * motivations for serverless computing
  * limitations of serverless
* ![](https://img.shields.io/static/v1.svg?label=&message=Serverless&color=red)**[Evaluation of Production Serverless Computing Environments](https://ieeexplore.ieee.org/abstract/document/8457830/)** ![](https://img.shields.io/static/v1.svg?label=[C]&message=CoCC'18&color=purple)
  * evaluates the performance of production serverless
  *  "serverless is powered by container technologies which have **near zero start-up delay and deleting latency**."
  * "a container is **deployed and terminated within a few milliseconds** for the function invocation **w/ pre warmup** policy"
* ![](https://img.shields.io/static/v1.svg?label=&message=Serverless&color=red)**[Serverless in the Wild: Characterizing and Optimizing the Serverless Workload at a Large Cloud Provider](https://www.usenix.org/conference/atc20/presentation/shahrad)** [![](https://img.shields.io/static/v1.svg?label=[A]&message=ATC'20&color=purple)](https://www.usenix.org/conference/atc20/presentation/shahrad) [![](https://img.shields.io/static/v1.svg?label=📺&message=slides&color=green)](https://www.usenix.org/system/files/atc20-paper593-slides-shahrad.pdf) [![](https://img.shields.io/static/v1.svg?label=&labelColor=gray&logo=youtube&logoColor=red&message=TALK&color=yellow)](https://youtu.be/fzjO8hL_Av4)
  * characterize the FaaS workload of Azure Functions
  * propose a practical resource management policy to **reduce the number of cold starts**
* [serverless]
* [serverless]

### 2022.10

* A paper from ToN: ---
  
* **InferLine: latency-aware provisioning and scaling for prediction serving pipelines** ![](https://img.shields.io/static/v1.svg?label=[A]&message=SoCC'20&color=purple)
  
* **Tributary: spot-dancing for elastic services with latency SLOs** [![](https://img.shields.io/static/v1.svg?label=[A]&message=ATC'18&color=purple)](https://www.usenix.org/conference/atc18/presentation/harlap) [![](https://img.shields.io/static/v1.svg?label=📺&message=slides&color=green)](https://www.usenix.org/sites/default/files/conference/protected-files/atc18_slides_harlap.pdf) [![](https://img.shields.io/static/v1.svg?label=&labelColor=gray&logo=youtube&logoColor=red&message=TALK&color=yellow)](https://www.usenix.org/conference/atc18/presentation/harlap)
  * Transient Instance (AWS Spot Instance)
  * **Trace**: ClarkNet & WITS & ...

* **Cocktail: A Multidimensional Optimization for Model Serving in Cloud** [![](https://img.shields.io/static/v1.svg?label=[A]&message=NSDI'22&color=purple)](https://www.usenix.org/conference/nsdi22/presentation/gunasekaran) [![](https://img.shields.io/static/v1.svg?label=&logo=github&labelColor=gray&message=CODE&color=blue)](https://github.com/jashwantraj92/cocktail) [![](https://img.shields.io/static/v1.svg?label=📺&message=slides&color=green)](https://www.usenix.org/system/files/nsdi22_slides_gunasekaran.pdf) [![](https://img.shields.io/static/v1.svg?label=&labelColor=gray&logo=youtube&logoColor=red&message=TALK&color=yellow)](https://youtu.be/VAsB1XBuRZ0)
  * Ensemble Learning
  * Transient Instance
  * "DeepAR-estimator"
  * **Trace**: Wikipedia & tweet


### 2022.09

* **Twine: A Unified Cluster Management System for Shared Infrastructure** [![](https://img.shields.io/static/v1.svg?label=[A]&message=OSDI'20&color=purple)](https://www.usenix.org/conference/osdi20/presentation/tang) [![](https://img.shields.io/static/v1.svg?label=📺&message=slides&color=green)](https://www.usenix.org/sites/default/files/conference/protected-files/osdi20_slides_tang.pdf) [![](https://img.shields.io/static/v1.svg?label=&labelColor=gray&logo=youtube&logoColor=red&message=TALK&color=yellow)](https://papertalk.org/papertalks/22334) [![](https://img.shields.io/static/v1.svg?label=📑&message=Blog&color=ffa000)](https://engineering.fb.com/2019/06/06/data-center-engineering/twine/)
* **Shard Manager: A Generic Shard Management Framework for Geo-distributed Applications** [![](https://img.shields.io/static/v1.svg?label=📝&message=NOTE&color=red)](notes/shard_manager.md) [![](https://img.shields.io/static/v1.svg?label=[A]&message=SOSP'21&color=purple)](https://dl.acm.org/doi/10.1145/3477132.3483546) [![](https://img.shields.io/static/v1.svg?label=📺&message=slides&color=green)](materials/xx.pdf) [![](https://img.shields.io/static/v1.svg?label=&labelColor=gray&logo=youtube&logoColor=red&message=TALK&color=yellow)](https://youtu.be/OMI52r-thFA) [![](https://img.shields.io/static/v1.svg?label=📑&message=Blog&color=ffa000)](https://engineering.fb.com/2020/08/24/production-engineering/scaling-services-with-shard-manager/)
* **Autopilot: workload autoscaling at Google** [![](https://img.shields.io/static/v1.svg?label=📝&message=NOTE&color=red)](notes/autopilot.md) [![](https://img.shields.io/static/v1.svg?label=[B]&message=EuroSys'20&color=purple)](https://dl.acm.org/doi/abs/10.1145/3342195.3387524) [![](https://img.shields.io/static/v1.svg?label=📺&message=slides&color=green)](materials/autopilot.pdf) [![](https://img.shields.io/static/v1.svg?label=&labelColor=gray&logo=youtube&logoColor=red&message=TALK&color=yellow)](https://youtu.be/RVXvMgNG10w)
* **Piccolo: ---**

### 2022

* **Scrooge: A Cost-Effective Deep Learning Inference System** [![](https://img.shields.io/static/v1.svg?label=[B]&message=SoCC'21&color=purple)](https://dl.acm.org/doi/10.1145/3472883.3486993) [![](https://img.shields.io/static/v1.svg?label=&labelColor=gray&logo=youtube&logoColor=red&message=TALK&color=yellow)](https://dl.acm.org/doi/10.1145/3472883.3486993#video_stream_uuid%3Af352c203-6b14-4ec0-a71a-860dc0b345f6)

* **Nexus: A GPU Cluster Engine for Accelerating DNN-Based Video Analysis** [![](https://img.shields.io/static/v1.svg?label=[A]&labelColor=gray&message=SOSP'19&color=purple)](https://dl.acm.org/doi/10.1145/3341301.3359658) [![](https://img.shields.io/static/v1.svg?label=📺&message=slides&color=green)](materials/nexus.pdf) [![](https://img.shields.io/static/v1.svg?label=📹&labelColor=gray&message=TALK&color=yellow)](https://sosp19.rcs.uwaterloo.ca/videos/D2-S2-P3.mp4)

* **AutoScale: Dynamic, Robust Capacity Management for Multi-Tier Data Centers** [![](https://img.shields.io/static/v1.svg?label=📝&message=NOTE&color=red)](notes/autoscale.md) [![](https://img.shields.io/static/v1.svg?label=[A]&labelColor=gray&message=TOCS'12&color=purple)](https://dl.acm.org/doi/10.1145/2382553.2382556)

  

------


### Template:

* :smirk::heart::bookmark: [Template: An example](paper/xx.pdf) [GPU Scheduling] [![](https://img.shields.io/static/v1.svg?label=📑&message=NOTE&color=red)](notes/xxx.md) [![](https://img.shields.io/static/v1.svg?label=🌐&message=ArXiv&color=purple)](https://www.usenix.org/conference/osdi22) [![](https://img.shields.io/static/v1.svg?label=&logo=github&labelColor=gray&message=CODE&color=blue)](https://github.com/gg-lc/papernotes-rlsys) [![](https://img.shields.io/static/v1.svg?label=📺&message=slides&color=green)](/materials/xx.pdf) [![](https://img.shields.io/static/v1.svg?label=&labelColor=gray&logo=youtube&logoColor=red&message=TALK&color=yellow)](https://papertalk.org/index) [![](https://img.shields.io/static/v1.svg?label=📑&message=Blog&color=ffa000)](link)

