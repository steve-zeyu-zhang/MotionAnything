<div align="center"><h1>Motion Anything: Any to Motion Generation<br>
<!-- <sub><sup><a href="">Preprint</a></sup></sub> -->
</h1>

[Zeyu Zhang](https://steve-zeyu-zhang.github.io)<sup>\*</sup>, [Yiran Wang](https://www.linkedin.com/in/yiran-wang-101739246/)<sup>\*</sup>, [Wei Mao](https://wei-mao-2019.github.io/home/), [Danning Li](https://www.linkedin.com/in/danning-li-448039229/), [Rui Zhao](https://www.linkedin.com/in/akira-zhao/), [Biao Wu](https://scholar.google.com/citations?user=Y3SBBWMAAAAJ&hl=en), [Zirui Song](https://ziruisongbest.github.io/), [Bohan Zhuang](https://bohanzhuang.github.io/), [Ian Reid](https://mbzuai.ac.ae/study/faculty/ian-reid/), [Richard Hartley](https://users.cecs.anu.edu.au/~hartley/)

<sup>*</sup>Equal contribution

[![Website](https://img.shields.io/badge/Website-Demo-fedcba?style=flat-square)](https://steve-zeyu-zhang.github.io/MotionAnything/) 
[![arXiv](https://img.shields.io/badge/arXiv-2503.06955-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.06955) 
[![Papers With Code](https://img.shields.io/badge/Papers%20With%20Code-555555.svg?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2aWV3Qm94PSIwIDAgNTEyIDUxMiIgd2lkdGg9IjUxMiIgIGhlaWdodD0iNTEyIiA+PHBhdGggZD0iTTg4IDEyOGg0OHYyNTZIODh6bTE0NCAwaDQ4djI1NmgtNDh6bS03MiAxNmg0OHYyMjRoLTQ4em0xNDQgMGg0OHYyMjRoLTQ4em03Mi0xNmg0OHYyNTZoLTQ4eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PHBhdGggZD0iTTEwNCAxMDRWNTZIMTZ2NDAwaDg4di00OEg2NFYxMDR6bTMwNC00OHY0OGg0MHYzMDRoLTQwdjQ4aDg4VjU2eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PC9zdmc+)](https://paperswithcode.com/paper/motion-anything-any-to-motion-generation) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-555555?style=flat-square)](https://huggingface.co/papers/2503.06955)
[![BibTeX](https://img.shields.io/badge/BibTeX-Citation-eeeeee?style=flat-square)](https://steve-zeyu-zhang.github.io/MotionAnything/static/scholar.html)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/motion-anything-any-to-motion-generation/motion-synthesis-on-humanml3d)](https://paperswithcode.com/sota/motion-synthesis-on-humanml3d?p=motion-anything-any-to-motion-generation)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/motion-anything-any-to-motion-generation/motion-synthesis-on-kit-motion-language)](https://paperswithcode.com/sota/motion-synthesis-on-kit-motion-language?p=motion-anything-any-to-motion-generation)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/motion-anything-any-to-motion-generation/motion-synthesis-on-aist)](https://paperswithcode.com/sota/motion-synthesis-on-aist?p=motion-anything-any-to-motion-generation)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/motion-anything-any-to-motion-generation/motion-synthesis-on-tmd)](https://paperswithcode.com/sota/motion-synthesis-on-tmd?p=motion-anything-any-to-motion-generation)


</div>

_Conditional motion generation has been extensively studied in computer vision, yet two critical challenges remain. First, while masked autoregressive methods have recently outperformed diffusion-based approaches, existing masking models lack a mechanism to prioritize dynamic frames and body parts based on given conditions. Second, existing methods for different conditioning modalities often fail to integrate multiple modalities effectively, limiting control and coherence in generated motion. To address these challenges, we propose <b>Motion Anything</b>, a multimodal motion generation framework that introduces an Attention-based Mask Modeling approach, enabling fine-grained spatial and temporal control over key frames and actions. Our model adaptively encodes multimodal conditions, including text and music, improving controllability. Additionally, we introduce <b>Text-Music-Dance</b> (<b>TMD</b>), a new motion dataset consisting of <b>2,153</b> pairs of text, music, and dance, making it <b>twice</b> the size of AIST++, thereby filling a critical gap in the community. Extensive experiments demonstrate that Motion Anything surpasses state-of-the-art methods across multiple benchmarks, achieving a <b>15%</b> improvement in FID on HumanML3D and showing consistent performance gains on AIST++ and TMD._

<div align="center">
<img src="https://github.com/steve-zeyu-zhang/MotionAnything/blob/website/static/images/main.png" style="width: 100%;">
</div>

<!-- 

## News

<b>(07/22/2024)</b> &#127881; Our paper was invited for a talk at <a href="https://www.mihoyo.com/"><b>miHoYo</b></a>. You can find our slides <a href="https://steve-zeyu-zhang.github.io/MotionMamba/static/pdfs/Motion_Mamba_Slides_miHoYo.pdf"><b>here</b></a>!

<b>(07/05/2024)</b> &#127881; Our paper has been highlighted twice by <a href="https://wx.zsxq.com/dweb2/index/topic_detail/5122458815888184"><b>CVer</b></a>!

<b>(07/02/2024)</b> &#127881; Our paper has been accepted to <a href="https://eccv2024.ecva.net/"><b>ECCV 2024</b></a>!

<b>(03/15/2024)</b> &#127881; Our paper has been highlighted by <a href="https://twitter.com/Marktechpost/status/1768770427680424176"><b>MarkTechPost</b></a>!

<b>(03/13/2024)</b> &#127881; Our paper has been featured in <a href="https://twitter.com/_akhaliq/status/1767750847239262532"><b>Daily Papers</b></a>!

<b>(03/13/2024)</b> &#127881; Our paper has been highlighted by <a href="https://wx.zsxq.com/dweb2/index/topic_detail/1522541851241522"><b>CVer</b></a>!


-->

## Citation

```
@article{zhang2025motion,
  title={Motion Anything: Any to Motion Generation},
  author={Zhang, Zeyu and Wang, Yiran and Mao, Wei and Li, Danning and Zhao, Rui and Wu, Biao and Song, Zirui and Zhuang, Bohan and Reid, Ian and Hartley, Richard},
  journal={arXiv preprint arXiv:2503.06955},
  year={2025}
}
```

