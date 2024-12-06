<div align="center"><h1>Motion Anything: One Prompt for Multimodal Motion and Avatar Generation<br>
<!-- <sub><sup><a href="">Preprint</a></sup></sub> -->
</h1>

[Zeyu Zhang](https://steve-zeyu-zhang.github.io), [Yiran Wang](https://www.linkedin.com/in/yiran-wang-101739246/), [Wei Mao](https://wei-mao-2019.github.io/home/), [Danning Li](https://www.linkedin.com/in/danning-li-448039229/), [Rui Zhao](https://www.linkedin.com/in/akira-zhao/), [Biao Wu](https://scholar.google.com/citations?user=Y3SBBWMAAAAJ&hl=en), [Zirui Song](https://ziruisongbest.github.io/), [Bohan Zhuang](https://bohanzhuang.github.io/), [Ian Reid](https://mbzuai.ac.ae/study/faculty/ian-reid/), [Richard Hartley](https://users.cecs.anu.edu.au/~hartley/)

[![Website](https://img.shields.io/badge/Website-Demo-fedcba?style=flat-square)](https://steve-zeyu-zhang.github.io/MotionAnything/) 
<!-- [![arXiv](https://img.shields.io/badge/arXiv-2400.00000-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2000.00000) [![Papers With Code](https://img.shields.io/badge/Papers%20With%20Code-555555.svg?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2aWV3Qm94PSIwIDAgNTEyIDUxMiIgd2lkdGg9IjUxMiIgIGhlaWdodD0iNTEyIiA+PHBhdGggZD0iTTg4IDEyOGg0OHYyNTZIODh6bTE0NCAwaDQ4djI1NmgtNDh6bS03MiAxNmg0OHYyMjRoLTQ4em0xNDQgMGg0OHYyMjRoLTQ4em03Mi0xNmg0OHYyNTZoLTQ4eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PHBhdGggZD0iTTEwNCAxMDRWNTZIMTZ2NDAwaDg4di00OEg2NFYxMDR6bTMwNC00OHY0OGg0MHYzMDRoLTQwdjQ4aDg4VjU2eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PC9zdmc+)]() [![BibTeX](https://img.shields.io/badge/BibTeX-Citation-eeeeee?style=flat-square)]() -->


</div>

_Motion generation conditioned on inputs such as text and music has been extensively studied in computer vision. While specialized models exist for text-to-motion (T2M) or music-to-dance (M2D) generation, and some unified models handle multimodal conditioning, they are limited to processing only one type of input at a time and cannot generate avatars or background music. To address these challenges, our paper introduces several key contributions. (1) Firstly, we propose <b>Motion Anything</b>, a pioneering method capable of tackling multiple modalities simultaneously to generate 4D avatars with background music and text queries. (2) Additionally, we designed the <b>Temporal Adaptive Transformer</b>, which adaptively aligns different modalities of conditions to control motion generation in a time-sensitive manner. Meanwhile, our <b>Spatial Aligning Transformer</b> maps action text to specific body-part movements and aligns music genres with corresponding dance styles. (3) Furthermore, we developed an <b>attention-based spatial and temporal mask modeling</b> approach for more effective autoregressive generation. (4) In addition, we introduced a <b>Selective Rigging Mechanism</b> for improved automatic rigging of 3D meshes with skeletons. (5) We also created a new dataset named <b>Text-Music-Dance</b> (<b>TMD</b>), consisting of <b>2,153</b> paired samples of text, music, and dance, making it <b>twice</b> as large as AIST++. (6) Lastly, we conducted extensive experiments on standard benchmarks across various motion generation tasks. Our method achieved a <b>15%</b> improvement in FID on HumanML3D and showed consistent performance gains on AIST++._

<div align="center">
<!-- <img src="static/images/main.svg" style="width: 100%;">
<img src="static/images/block.svg" style="width: 80%;"> -->
</div>

<!-- 

## News

<b>(07/22/2024)</b> &#127881; Our paper was invited for a talk at <a href="https://www.mihoyo.com/"><b>miHoYo</b></a>. You can find our slides <a href="https://steve-zeyu-zhang.github.io/MotionMamba/static/pdfs/Motion_Mamba_Slides_miHoYo.pdf"><b>here</b></a>!

<b>(07/05/2024)</b> &#127881; Our paper has been highlighted twice by <a href="https://wx.zsxq.com/dweb2/index/topic_detail/5122458815888184"><b>CVer</b></a>!

<b>(07/02/2024)</b> &#127881; Our paper has been accepted to <a href="https://eccv2024.ecva.net/"><b>ECCV 2024</b></a>!

<b>(03/15/2024)</b> &#127881; Our paper has been highlighted by <a href="https://twitter.com/Marktechpost/status/1768770427680424176"><b>MarkTechPost</b></a>!

<b>(03/13/2024)</b> &#127881; Our paper has been featured in <a href="https://twitter.com/_akhaliq/status/1767750847239262532"><b>Daily Papers</b></a>!

<b>(03/13/2024)</b> &#127881; Our paper has been highlighted by <a href="https://wx.zsxq.com/dweb2/index/topic_detail/1522541851241522"><b>CVer</b></a>!

## Citation

```
@article{zhang2024motion,
  title={Motion Mamba: Efficient and Long Sequence Motion Generation with Hierarchical and Bidirectional Selective SSM},
  author={Zhang, Zeyu and Liu, Akide and Reid, Ian and Hartley, Richard and Zhuang, Bohan and Tang, Hao},
  journal={arXiv preprint arXiv:2403.07487},
  year={2024}
}
```

-->
