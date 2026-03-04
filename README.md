# 计算成像（Computational Imaging）

1.方法
| 方法 | 论文标题 | 期刊或会议 | 年份 | 论文 | 代码 |
|:----:|:----:|:----:|:----:|:----:|:----:|
| GAP-TV | Generalized alternating projection based total variation minimization for compressive sensing | ICIP | 2016 |[论文](https://ieeexplore.ieee.org/document/7532817)|[代码](https://github.com/mq0829/DL-CACTI/tree/master/PnP_algorithm)|
| DeSCI | Rank minimization for snapshot compressive imaging | TPAMI | 2019 |[论文](https://ieeexplore.ieee.org/abstract/document/8481592)|[代码](https://github.com/liuyang12/DeSCI) |
| λ-Net | lambda-Net: Reconstruct Hyperspectral Images From a Snapshot Measurement | ICCV | 2019 |[论文](https://ieeexplore.ieee.org/document/9010044)|[代码](https://github.com/caiyuanhao1998/MST) |
| MST | Mask-guided spectral-wise transformer for efficient hyper- spectral image reconstruction | CVPR | 2022 |[论文](https://ieeexplore.ieee.org/document/9878871)|[代码](https://github.com/caiyuanhao1998/MST) |
| SPECAT | Specat: Spatial-spectral cumulative-attention transformer for high-resolution hyper- spectral image reconstruction | CVPR | 2024 |[论文](https://ieeexplore.ieee.org/document/10657166)|[代码](https://github.com/THU-luvision/SPECAT) |
| DGSMP | Deep Gaussian scale mixture prior for spectral compressive imaging | CVPR | 2021 |[论文](https://arxiv.org/abs/2103.07152)|[代码](https://github.com/TaoHuang95/DGSMP) |
| HerosNet  | Herosnet: Hyperspectral explicable reconstruction and optimal sampling deep network for snapshot compressive imaging | CVPR | 2022 |[论文](https://arxiv.org/abs/2112.06238)|[代码](https://github.com/jianzhangcs/HerosNet) |
| DAUHST | Degradation-aware unfolding half-shuffle transformer for spectral compressive imaging | NeurIPS | 2022 |[论文](https://dl.acm.org/doi/10.5555/3600270.3603006)|[代码](https://github.com/caiyuanhao1998/MST) |
| PADUT  | Pixel adaptive deep unfolding transformer for hyperspectral image reconstruction | ICCV | 2023 |[论文](https://ieeexplore.ieee.org/document/10377584)|[代码](https://github.com/MyuLi/PADUT) |
| RDLUF | Residual degradation learning unfolding framework with mixing priors across spectral and spatial for compressive spectral imaging | CVPR | 2023 |[论文](https://ieeexplore.ieee.org/document/10204755)|[代码](https://github.com/ShawnDong98/RDLUF_MixS2) |
| S2Former | S2-Transformer for Mask-Aware Hyperspectral Image Reconstruction | TPAMI | 2025 |[论文](https://ieeexplore.ieee.org/document/10899382)|[代码](https://github.com/Jiamian-Wang/S2-transformer-HSI) |CVPR
| LADE-DUN | Latent diffusion prior enhanced deep unfolding for snapshot spectral compressive imaging | ECCV | 2024 |[论文](https://link.springer.com/chapter/10.1007/978-3-031-73414-4_10)|[代码](https://github.com/Zongliang-Wu/LADE-DUN) |ECCV


2.数据集
| 数据集 | 下载链接 |
|:----:|:----:|
|CAVE|https://cave.cs.columbia.edu/repository/Multispectral|
|KAIST|https://vclab.kaist.ac.kr/siggraphasia2017p1/kaistdataset.html|
|ICVL|https://icvl.cs.bgu.ac.il/hyperspectral|

3.评价指标

如文件夹“Quality_Metrics”中所示，包含以下评价指标：

·峰值信噪比（peak signal to noise ratio，PSNR）

·结构相似度（structural similarity index metric，SSIM）

·光谱角（spectral angle mapper，SAM）

·均方根误差（root mean square error，RMSE）

·空谱全局误差（erreur relative globale adimensionnelle de synthèse，ERGAS）

·结构相关指数（structural correlation coefficient，SCC）
