# README

## Publicly Available Repositories for Related Works

### Statistical Methods (Section III)

| Paper                                                        | Repository                                               |
| ------------------------------------------------------------ | -------------------------------------------------------- |
| [Hardt et al.](https://arxiv.org/abs/1012.4763)              | https://github.com/mrtzh/PrivateMultiplicativeWeights.jl |
| [Gaboardi et al.](https://proceedings.mlr.press/v32/gaboardi14.html) | https://github.com/ejgallego/dualquery                   |
| [Vietri et al.](https://proceedings.mlr.press/v119/vietri20b.html) | https://github.com/giusevtr/fem                          |
| [Chanyaswad et al.](https://sciendo.com/it/article/10.2478/popets-2019-0003) | https://github.com/inspire-group/RON-Gauss               |
| [Zhang et al.](https://dl.acm.org/doi/abs/10.1145/3134428)   | https://github.com/athenarc/PrivBayes                    |
| [Mckenna et al.](https://arxiv.org/abs/2108.04978)           | https://rb.gy/mlltjm                                     |
| [Cai et al.](https://dl.acm.org/doi/abs/10.14778/3476249.3476272) | https://github.com/caicre/PrivMRF                        |
| [Zhang et al.](https://www.usenix.org/system/files/sec21fall-zhang-zhikun.pdf) | https://github.com/agl-c/deid2_dpsyn                     |
| [Li et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4232968/) | https://github.com/alxxrg/copula-shirley                 |
| [Gambs et al.](https://petsymposium.org/2021/files/papers/issue3/paper128-2021-3-source.pdf) | https://github.com/alxxrg/copula-shirley                 |
| [Gursoy et al.](https://ieeexplore.ieee.org/ielaam/7755/8821494/8481494-aam.pdf) | https://github.com/nomalocaris/DP-Star                   |
| [Gursoy et al.](https://dl.acm.org/doi/abs/10.1145/3243734.3243741) | https://github.com/git-disl/AdaTrace                     |

### GANs (Section IV)

| Paper                                                        | Repository                                                   |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Xie et al.](https://arxiv.org/abs/1802.06739)               | https://github.com/lancopku/DPGAN                            |
| [Torkzadehmahani et al.](https://openaccess.thecvf.com/content_CVPRW_2019/html/CV-COPS/Torkzadehmahani_DP-CGAN_Differentially_Private_Synthetic_Data_and_Label_Generation_CVPRW_2019_paper.html) | https://github.com/reihaneh-torkzadehmahani/DP-CGAN          |
| [Harder et al.](http://proceedings.mlr.press/v130/harder21a.html) | https://github.com/frhrdr/dp-merf                            |
| [Liew et al.](https://arxiv.org/abs/2106.04590)              | https://github.com/lancopku/DPGAN                            |
| [Chen et al.](https://proceedings.neurips.cc/paper/2020/hash/9547ad6b651e2087bac67651aa92cd0d-Abstract.html) | https://github.com/DingfanChen/GS-WGAN                       |
| [Yoon et al.](https://openreview.net/forum?id=S1zk9iRqF7)    | https://github.com/vanderschaarlab/mlforhealthlabpub/tree/main/alg/pategan |
| [Long et al.](https://arxiv.org/abs/1906.09338)              | https://github.com/AI-secure/G-PATE                          |
| [Wang et al.](https://dl.acm.org/doi/abs/10.1145/3460120.3484579) | https://github.com/AI-secure/DataLens                        |
| [Hardy et al.](https://ieeexplore.ieee.org/abstract/document/8821025) | https://github.com/iDurugkar/GMAN                            |
| [Chang et al.](https://arxiv.org/abs/2012.08604)             | https://github.com/tommy-qichang/AsynDGAN                    |
| [Qu et al.](https://link.springer.com/chapter/10.1007/978-3-030-58583-9_11) | https://github.com/huiqu18/TDGAN-PyTorch                     |
| [Zhang et al.](https://arxiv.org/abs/2102.04655)             | https://github.com/yz422/UAGAN                               |
| [Augenstein et al.](https://arxiv.org/abs/1911.06679)        | https://github.com/google-research/federated/tree/master/gans |

### AEs (Section V)

| Paper                                                        | Repository                                                   |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Yang et al.](https://arxiv.org/abs/2005.00455)              | https://github.com/haonan3/Secure-Network-Release-with-Link-Privacy |
| [Choi et al.](http://proceedings.mlr.press/v68/choi17a)      | https://github.com/mp2893/medgan                             |
| [tantipongpipat et al.](https://ieeexplore.ieee.org/abstract/document/9555521) | https://github.com/DPautoGAN/DPautoGAN                       |
| [Kim et al.](https://ieeexplore.ieee.org/abstract/document/8744221) | https://github.com/tgisaturday/PPAP                          |
| [Kim et al.](https://www.mdpi.com/2079-9292/9/5/874)         | https://github.com/tgisaturday/PPSGAN                        |
| [Malekzadeh et al.](https://ieeexplore.ieee.org/abstract/document/8366986) | https://github.com/mmalekzadeh/replacement-autoencoder       |
| [Malekzadeh et al.](https://dl.acm.org/doi/abs/10.1145/3302505.3310068) | https://github.com/mmalekzadeh/motion-sense}                 |
| [Hajihassnai et al.](https://dl.acm.org/doi/abs/10.1145/3450268.3453534) | https://github.com/sustainable-computing/ObscureNet          |

## Data Utility Measures


### 1. Utility from downstream applications


We present various downstream applications that are used to evaluate the utility of synthetic data.


#### a) Query error for structured data

For structured data, one specific utility measure which appears throughout Section 3, is to choose a set of queries and consider the average/max query error that the synthetic dataset incurs on the queries compared to the real one. Formally, given a collection of queries $Q = {q\_1,\cdots, q\_k}$, an input dataset $D$ and the synthetic dataset $\widehat{D}$, the average and max query error are defined to be $
 \frac{1}{|Q|}\sum\_{j}\big|q\_j(D)-q\_j(\widehat{D})\big|$ and $
 \max\_{j}\big|q\_j(D)-q\_j(\widehat{D})\big|
$ respectively. Such definitions closely resemble the concept of $(\epsilon,\delta)$-usefulness defined in [Blum et al. (2013)](https://dl.acm.org/doi/abs/10.1145/2450142.2450148). Different choices of queries are used for different data types: range query ([Hardt et al., 2012](https://proceedings.neurips.cc/paper/2012/hash/208e43f0e45c4c78cafadb83d2888cb6-Abstract.html)) and parity query ([Gaboardi et al., 2014](https://proceedings.mlr.press/v32/gaboardi14.html)) for tabular data, count query ([Chen et al., 2012a](https://dl.acm.org/doi/abs/10.1145/2339530.2339564);[Chen et al., 2012b](https://dl.acm.org/doi/abs/10.1145/2382196.2382263);[Gursoy et al., 2018](https://ieeexplore.ieee.org/document/8481494?utm_source=researcher_app&utm_medium=referral&utm_campaign=RESR_MRKT_Researcher_inbound)) for trajectory data, and cut query ([Chen et al., 2014](https://link.springer.com/article/10.1007/s00778-013-0344-8)) for graph data. 


#### b) Training ML models


Another straightforward approach is to train an ML model based on the synthetic dataset and test it on the real test dataset, and use classical ML metrics (e.g., *accuracy*) to reflect the utility of data. This serves as a standard utility measure across different sections as well as different types of data. For *tabular data*, existing works consider simple ML models such as SVM ([Xu et al., 2017](https://www.semanticscholar.org/paper/DPPro%253A-Differentially-Private-High-Dimensional-Data-Xu-Ren/8055097795436399834579131de0de451295107a);[Abay et al., 2018](https://link.springer.com/chapter/10.1007/978-3-030-10925-7\_31)), random forest ([Tantipongpipat et al., 2021](https://arxiv.org/abs/1912.03250)), linear regression ([Gambs et al., 2021](https://petsymposium.org/2021/files/papers/issue3/popets-2021-0040.pdf)), clustering ([Chanyaswad et al., 2019](https://www.princeton.edu/ pmittal/publications/ron-gauss-pets19.pdf);[Acs et al., 2018](https://arxiv.org/abs/1709.04514)),
as well as complicated models such as (deep) neural networks (NNs) ([Edwards et al., 2016](https://arxiv.org/abs/1511.05897)). Regarding *unstructured data*, due to its intrinsic complexity, NNs are commonly adopted among these data types, e.g., handwritten digits classifier for image data ([Kim et al., 2020](https://www.mdpi.com/2079-9292/9/5/874);[Chen et al., 2018](https://arxiv.org/abs/1812.02274);[Long et al., 2019](https://arxiv.org/abs/1906.09338);[Yoon et al., 2019](https://openreview.net/forum%3Fid%3DS1zk9iRqF7);[Chen et al., 2020](https://arxiv.org/abs/2006.08265)), activity recognition classifier for sensor data ([Malekzadeh et al., 2019](https://arxiv.org/abs/1810.11546);[Hajihassani et al., 2020](https://ieeexplore.ieee.org/document/9111809)), and intent classifier for text data ([Krishna et al., 2021](https://arxiv.org/abs/2102.01502)).
For classification task, the corresponding metric is the **misclassification rate** ([Xu et al., 2017](https://www.semanticscholar.org/paper/DPPro%253A-Differentially-Private-High-Dimensional-Data-Xu-Ren/8055097795436399834579131de0de451295107a);[Abay et al., 2018](https://link.springer.com/chapter/10.1007/978-3-030-10925-7\_31);[Tantipongpipat et al., 2021](https://arxiv.org/abs/1912.03250);[Edwards et al., 2016](https://arxiv.org/abs/1511.05897)); for regression task, 
the metric is **root mean square error** (RMSE) ([Gambs et al., 2021](https://petsymposium.org/2021/files/papers/issue3/popets-2021-0040.pdf));
for clustering, the metrics include **Silhouette Coefficient** (S.C.) ([Rousseeuw et al., 1987](https://www.sciencedirect.com/science/article/pii/0377042787901257)) for $K$-means ([Chanyaswad et al., 2019](https://www.princeton.edu/ pmittal/publications/ron-gauss-pets19.pdf)) and **unsupervised clustering accuracy** (ACC) ([Xie et al., 2016](https://arxiv.org/abs/1511.06335)) for kernel $K$-means ([Acs et al., 2012](https://citeseerx.ist.psu.edu/viewdoc/download%3Fdoi%3D10.1.1.592.453%26rep%3Drep1%26type%3Dpdf)).


#### c) Utility in specific applications


We additionally introduce utility measures designed for specific applications, mainly covered in Section 5 due to the flexibility of autoencoders.
For the collaborative filtering on the user-item rating matrix, the evaluation metric is the RMSE between the original matrix and the synthetic matrix ([Ren et al., 2019](https://ieeexplore.ieee.org/iel7/8746989/8753824/08753955.pdf);[Liu et al., 2019](https://ieeexplore.ieee.org/document/8875344)).
For the anonymization of financial dataset, the utility is measured through a downstream task of anomalous subgroup discovery, where the preservation of utility is associated with the discovered anomalous features ([Maina et al., 2019](https://krvarshney.github.io/pubs/MainaBOVSCWS\_rafs2019.pdf);[Maina et al., 2019](http://arxiv.org/abs/1911.03674)).
For medical dataset, the utility measure is obtained via a human expert (as a discriminator) who provides assessments on the dataset composed of both real and synthesiz data ([Choi et al., 2017](https://arxiv.org/abs/1703.06490)).
For sensor data combined with third party applications, the utility is measured as the performance of the third party applications on the synthetic data ([Malekzadeh et al., 2018](https://arxiv.org/abs/1710.06564);[Hajihassnai et al., 2021](https://www-users.cselabs.umn.edu/classes/Fall-2021/csci8980-ec/papers/ObscureNet.pdf)).
For trajectory data, the performance on frequent pattern mining is used as the utility metrics ([He et al., 2015](http://www.vldb.org/pvldb/vol8/p1154-he.pdf);[Gursoy et al., 2018](https://ieeexplore.ieee.org/abstract/document/8481494))


### 2. Utility from Intrinsic Data Property


Now we will switch to the utility measures that focus on preserving the intrinsic properties of the data. We organize this section based on different data types. 


#### a) Tabular data


The most important structure of tabular data lies in its marginals (a.k.a. contingency tables). Therefore, a vast majority of works measure the quality of synthetic tabular data based on the accuracy of **$k$-way marginals**, and the metrics include total variance distance ([Zhang et al., 2017](http://dimacs.rutgers.edu/ graham/pubs/papers/PrivBayes.pdf)), Kullback-Leibler (KL) divergence ([Hardt et al., 2012](https://arxiv.org/abs/1012.4763)), and Jensen-Shannon divergence (JSD) ([Fuglede et al., 2004](http://ieeexplore.ieee.org/document/1365067/)). Other utility measures include the *per-attribute* **Kolmogorov-Smirnov distance** (KS distance) ([Gambs et al., 2021](https://petsymposium.org/2021/files/papers/issue3/popets-2021-0040.pdf)), which estimates the fidelity of the distributions of the synthetic data compared to the original data ([Massey Jr et al., 1951](https://www.jstor.org/stable/2280095)); the **Mean Correlation Delta** ([Gambs et al., 2021](https://petsymposium.org/2021/files/papers/issue3/popets-2021-0040.pdf)), which estimates the absolute difference of the correlation coefficients between the correlation matrices of the two datasets; and the **averaged $L\_2$-error** ([Xu et al., 2017](https://www.semanticscholar.org/paper/DPPro%253A-Differentially-Private-High-Dimensional-Data-Xu-Ren/8055097795436399834579131de0de451295107a))---a metric that measures the closeness of the pairwise $L\_2$-distance between different users.


#### b) Trajectory data


For trajectory data, the widely used utility measures examine the *spatial* properties and the *spatio-temporal* properties of trajectories. 
To measure the *locality resemblance*, **locations’ popularity ranking** ([Gursoy et al., 2018](https://dl.acm.org/doi/10.1145/3243734.3243741);[Bindschaedler et al., 2016](https://ieeexplore.ieee.org/document/7546522)) is introduced where the popularity of each location is defined as the number of times it is visited by trajectories in the dataset; and **Earth Mover’s Distance (EMD)** ([Rubner et al., 2000](https://link.springer.com/article/10.1023/A:1026543900054);[Roy et al., 2016](https://hal.inria.fr/hal-01633671)) is used to compare two spatial probability distributions ([Mir et al., 2013](https://mrmgroup.cs.princeton.edu/papers/bigdata13.pdf)).
In order to evaluate whether synthetic trajectories preserve the aggregated *spatio-temporal* properties of the original trajectories, a number of works measure the **length distribution** ([Zhang et al., 2016](https://arxiv.org/abs/1601.03229);[Gursoy et al., 2018](https://dl.acm.org/doi/10.1145/3243734.3243741);[Gursoy et al., 2020](https://arxiv.org/pdf/2009.06505)) which compares the distributions of sequence lengths via Total Variation Distance ([Sampson et al., 1992](https://www.jstor.org/stable/2290458)); **diameter distribution** ([He et al., 2015](http://www.vldb.org/pvldb/vol8/p1154-he.pdf);[Gursoy et al., 2018](https://dl.acm.org/doi/10.1145/3243734.3243741);[Mir et al., 2013](https://mrmgroup.cs.princeton.edu/papers/bigdata13.pdf)), where the diameter is the maximum distance between any pair of locations in one trajectory; and **trip distribution** ([He et al., 2015](http://www.vldb.org/pvldb/vol8/p1154-he.pdf);[Gursoy et al., 2018](https://dl.acm.org/doi/10.1145/3243734.3243741);[Gursoy et al., 2020](https://arxiv.org/pdf/2009.06505)), which is the distribution of the ending points of trajectories given a starting region. The error between the diameter distributions or trip distributions is measured by Jensen Shannon divergence ([Fuglede et al., 2004](http://ieeexplore.ieee.org/document/1365067/)). 
Other than the above two types of metrics that directly compare the original and synthetic trajectory datasets, some work directly compares each pair of original and synthetic trajectories ([Shao et al., 2013](https://www.researchgate.net/publication/290570291\_Publishing\_Trajectory\_with\_Differential\_Privacy\_A\_Priori\_vs\_A\_Posteriori\_Sampling\_Mechanisms)) via Dynamic Time Warping distance ([Sakoe et al., 1978](https://ieeexplore.ieee.org/document/1163055)), or the maximum of the distance between positions under the same timestamp ([Shao et al., 2013](https://www.researchgate.net/publication/290570291\_Publishing\_Trajectory\_with\_Differential\_Privacy\_A\_Priori\_vs\_A\_Posteriori\_Sampling\_Mechanisms)). For privacy principles beyond $\varepsilon$-DP, spatial and temporal granularity are evaluated for $k^{\tau,\epsilon}$- Anonymity ([Gramaglia et al., 2017](http://ieeexplore.ieee.org/abstract/document/8056979/)); performance on location-based services and geo-data analysis tasks are measured for plausible deniability ([Bindschaedler et al., 2016](https://ieeexplore.ieee.org/document/7546522)). 


#### c) Graph data


For general unlabeled graph, we mainly identify two types of utility measures: *degree-based measure* and *node-separation measure*. Degree-based measure describes the basic topological structures of the graph, and characterize how degrees are distributed among nodes as well as how nodes with particular degree connect with each other. Some popular metrics which are widely used in the literature include **degree distribution** ([Chen et al., 2014](https://dl.acm.org/doi/10.1007/s00778-013-0344-8)), which appears in the form of *normalized degree histogram* and is measured via Hellinger distance; **assortativity** ([Wang et al., 2013](https://dl.acm.org/doi/10.5555/2612167.2612168)), which describes the tendency that nodes with similar degree are connected to each other and is closely related to **joint degree distribution** ([Proserpio et al., 2012](https://dl.acm.org/doi/10.1145/2342549.2342553)); and **eigenvector centrality** ([Xiao et al., 2014](https://dl.acm.org/doi/10.1145/2623330.2623642)), aiming to find the most influential nodes which determine the global structure of the graph. Node-separation measure quantifies the inter-connectivity and density of the overall graph. It includes metrics such as **graph diameter** ([Nguyen et al., 2015](http://ieeexplore.ieee.org/abstract/document/7403602/)), which is the maximum distance among all path-connected pairs of vertices; **shortest/average path length** ([Xiao et al., 2014](https://dl.acm.org/doi/10.1145/2623330.2623642);[Wang et al., 2013](https://dl.acm.org/doi/10.5555/2612167.2612168)), referring to the average distance among all pairs of vertices that are path-connected; and **global/local clustering coefficient** ([Jorgensen et al., 2016](https://dl.acm.org/doi/10.1145/2882903.2915215)), which characterize the degree to which nodes in a graph tend to cluster together, with the former emphasizing the low-degree nodes while the latter emphasizing the high-degree nodes.
Going beyond unlabeled graph, **attribute-edge correlation** ([Jorgensen et al., 2016](https://dl.acm.org/doi/10.1145/2882903.2915215)) is introduced to characterize the relation between the feature vectors labeling a pair of vertices and the likelihood that these vertices are connected, and **precise/recall indices** are defined in ([Chen et al., 2020](https://arxiv.org/abs/1909.00280)) to measure the preservation of community structure. There are also cases where the goal is to perform **parameter estimation** in the graph model ([Snijders et al., 2006](https://journals.sagepub.com/doi/10.1111/j.1467-9531.2006.00176.x)).
We refer the readers to ([Costa et al., 2007](https://www.researchgate.net/publication/232874573\_Characterization\_of\_Complex\_Networks\_A\_Survey\_of\_measurements)) for a comprehensive survey of utility measures in graph.


#### d) Image data


For synthesized *image data* produced by generative models, the utility measure concerning the intrinsic data property is associated with *image quality*, characterized by Inception Score (IS) ([Kim et al., 2019](https://ieeexplore.ieee.org/document/8744221);[Kim et al., 2020](https://www.mdpi.com/2079-9292/9/5/874);[Salimans et al., 2016](https://arxiv.org/abs/1606.03498)), as well as the distribution similarity of the generated data and the real images used for training the generator, measured by Fréchet Inception Distance (FID) ([Heusel et al., 2017](https://arxiv.org/abs/1706.08500)). 
