# 📒Awesome-SD-Inference
<div align='left'>
  <img src=https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg >
  <img src=https://img.shields.io/github/forks/DefTruth/Awesome-SD-Inference.svg?style=social >
  <img src=https://img.shields.io/github/stars/DefTruth/Awesome-SD-Inference.svg?style=social >
  <img src=https://img.shields.io/github/watchers/DefTruth/Awesome-SD-Inference.svg?style=social >
  <img src=https://img.shields.io/badge/Release-v0.2-brightgreen.svg >
  <img src=https://img.shields.io/badge/License-GPLv3.0-turquoise.svg >
 </div>   

📒A **small** curated list of Awesome **SD/DiT/ViT/Diffusion** Inference with **Distributed/Caching/Sampling**. For Awesome LLM Inference, please check 📖[Awesome-LLM-Inference](https://github.com/DefTruth/Awesome-LLM-Inference)  ![](https://img.shields.io/github/stars/DefTruth/Awesome-LLM-Inference.svg?style=social)

## 🤖Contents

- [📙Awesome SD Inference with Caching](#Caching)
- [📙Awesome SD Distributed Inference with Multi-GPUs](#Distributed)


## ©️Citations 

```BibTeX
@misc{Awesome-SD-Inference@2024,
  title={Awesome-SD-Inference: A small curated list of Awesome SD/DiT/ViT/Diffusion Inference with Distributed/Caching/Sampling.},
  url={https://github.com/DefTruth/Awesome-SD-Inference},
  note={Open-source software available at https://github.com/DefTruth/Awesome-SD-Inference},
  author={DefTruth},
  year={2024}
}
```


## 📙Awesome SD Inference with Caching  

<div id="Caching"></div>  

- **UNet Based (DeepCache)**

<img width="1645" alt="image" src="https://github.com/user-attachments/assets/a7257462-80d3-40af-a4ce-3550508fabe7">


- **DiT Based (Fast-Forward Caching)**
<img width="1119" alt="image" src="https://github.com/user-attachments/assets/fad8f187-d4ac-4290-9943-7b34116fed05">

|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2023.05|🔥🔥[**Cache-Enabled Sparse Diffusion**] Accelerating Text-to-Image Editing via Cache-Enabled Sparse Diffusion Inference(@pku.edu.cn etc)|[[pdf]](https://arxiv.org/pdf/2305.17423) |⚠️|⭐️⭐️ | 
|2023.12|🔥🔥[**DeepCache**] DeepCache: Accelerating Diffusion Models for Free(@nus.edu)|[[pdf]](https://arxiv.org/pdf/2312.00858) | [[DeepCache]](https://github.com/horseee/DeepCache) ![](https://img.shields.io/github/stars/horseee/DeepCache.svg?style=social)| ⭐️⭐️ |   
|2023.12|🔥🔥[**Block Caching**] Cache Me if You Can: Accelerating Diffusion Models through Block Caching(@Meta GenAI etc)|[[pdf]](https://arxiv.org/pdf/2312.03209) |⚠️|⭐️⭐️ | 
|2023.12|🔥🔥[**Approximate Caching**] Approximate Caching for Efficiently Serving Diffusion Models(@Adobe)|[[pdf]](https://arxiv.org/pdf/2312.04429) |⚠️|⭐️⭐️ |
|2024.06| 🔥🔥[**Layer Caching**] Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching(@nus.edu)  | [[pdf]](https://arxiv.org/pdf/2406.01733) | [[learning-to-cache]](https://github.com/horseee/learning-to-cache/) ![](https://img.shields.io/github/stars/horseee/learning-to-cache.svg?style=social)| ⭐️⭐️ | 
|2024.07|🔥[**ElasticCache-LVLM**] Efficient Inference of Vision Instruction-Following Models with Elastic Cache(@Tsinghua University etc)|[[pdf]](https://arxiv.org/pdf/2407.18121)|[[ElasticCache]](https://github.com/liuzuyan/ElasticCache) ![](https://img.shields.io/github/stars/liuzuyan/ElasticCache.svg?style=social)|⭐️ |
|2024.07| 🔥🔥[**Fast-Forward Caching(DiT)**] FORA: Fast-Forward Caching in Diffusion Transformer Acceleration(@microsoft.com etc) | [[pdf]](https://arxiv.org/pdf/2407.01425) | [[FORA]](https://github.com/prathebaselva/FORA) ![](https://img.shields.io/github/stars/prathebaselva/FORA.svg?style=social)|⭐️⭐️ |
|2024.07| 🔥🔥[**Faster I2V Generation**] Faster Image2Video Generation: A Closer Look at CLIP Image Embedding’s Impact on Spatio-Temporal Cross-Attentions(@Ashkan Taghipour etc)|[[pdf]](https://arxiv.org/pdf/2407.19205) |⚠️|⭐️⭐️ |

## 📙Awesome SD Distributed Inference with Multi-GPUs

<div id="Distributed"></div>  

- **UNet Based: Displaced Patch parallelism (DistriFusion)**

<img width="1677" alt="image" src="https://github.com/user-attachments/assets/aefb2ae7-73eb-4e9c-bf1a-ec540f4dfa7d">

- **DiT Based: Displaced Patch parallelism (PipeFusion)**

<img width="1346" alt="image" src="https://github.com/user-attachments/assets/692c5d54-19b3-4ce7-9613-9eb8bb035c7d">


|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2024.02|🔥🔥[**DistriFusion**] DistriFusion: Distributed Parallel Inference for High-Resolution Diffusion Models(@MIT etc)|[[pdf]](https://arxiv.org/abs/2402.19481) | [[distrifuser]](https://github.com/mit-han-lab/distrifuser) ![](https://img.shields.io/github/stars/mit-han-lab/distrifuser.svg?style=social)| ⭐️⭐️ |   
|2024.05|🔥🔥[**PipeFusion**] PipeFusion: Displaced Patch Pipeline Parallelism for Inference of Diffusion Transformer Models(@Tencent etc)|[[pdf]](https://arxiv.org/pdf/2405.14430) | [[xDiT]](https://github.com/xdit-project/xDiT) ![](https://img.shields.io/github/stars/xdit-project/xDiT.svg?style=social)| ⭐️⭐️ | 
|2024.06| 🔥🔥[**AsyncDiff**] AsyncDiff: Parallelizing Diffusion Models by Asynchronous Denoising(@nus.edu) | [[pdf]](https://arxiv.org/pdf/2406.06911) | [[AsyncDiff]](https://github.com/czg1225/AsyncDiff) ![](https://img.shields.io/github/stars/czg1225/AsyncDiff.svg?style=social)| ⭐️⭐️ |   
|2024.05 | 🔥🔥[**TensorRT-LLM SDXL**] SDXL Distributed Inference with TensorRT-LLM and synchronous comm(@Zars19) | [[pdf]](https://arxiv.org/abs/2402.19481) | [[SDXL-TensorRT-LLM]](https://github.com/NVIDIA/TensorRT-LLM/pull/1514) ![](https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM.svg?style=social)| ⭐️⭐️ | 
|2024.06| 🔥🔥[**Clip Parallelism**] Video-Infinity: Distributed Long Video Generation(@nus.edu)|[[pdf]](https://arxiv.org/pdf/2406.16260) | [[Video-Infinity]](https://github.com/Yuanshi9815/Video-Infinity) ![](https://img.shields.io/github/stars/Yuanshi9815/Video-Infinity.svg?style=social)|⭐️⭐️ | 
|2024.05| 🔥🔥[**FIFO-Diffusion**] FIFO-Diffusion: Generating Infinite Videos from Text without Training(@Seoul National University)|[[pdf]](https://arxiv.org/pdf/2405.11473) |  [[FIFO-Diffusion]](https://github.com/jjihwan/FIFO-Diffusion_public) ![](https://img.shields.io/github/stars/jjihwan/FIFO-Diffusion_public.svg?style=social) |⭐️⭐️ | 

## ©️License  

GNU General Public License v3.0  

## 🎉Contribute  

Welcome to star & submit a PR to this repo! 

<div align='center'>
<a href="https://star-history.com/#DefTruth/Awesome-SD-Inference&Date">
  <picture align='center'>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=DefTruth/Awesome-SD-Inference&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=DefTruth/Awesome-SD-Inference&type=Date" />
    <img width="350" height="250" alt="Star History Chart" src="https://api.star-history.com/svg?repos=DefTruth/Awesome-SD-Inference&type=Date" />
  </picture>
</a>
</div>
