---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include about-homepage-header.html %}

I am a fourth-year undergraduate student at [Tianjin University of Technology](https://www.tjut.edu.cn/), advised by [Prof. Jianhua Zhang](https://cs.tjut.edu.cn/info/1226/1540.htm) and [Prof. Xu Cheng](https://cs.tjut.edu.cn/info/1211/2197.htm). I will pursue my M.S. degree at the [Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS)](https://www.ict.ac.cn), with research training at the [Institute of AI for Industry (IAII)](https://iaii.cas.cn/), under the supervision of [Prof. Chunhe Song](https://iaii.cas.cn/rcdw/yjy/202505/t20250522_7790187.html). I am also involved in research on world models and embodied intelligence with [Prof. Kai Xu](https://kevinkaixu.net/) at IAII, and work as a research assistant with [Prof. Hao Tang](https://ha0tang.github.io/) at Peking University.

🎯 My research interests include world models, embodied AI, and reinforcement learning. My long-term goal is to build generalizable world models for robotic agents, enabling them to better understand, predict, and interact with the physical world, and ultimately serve humans in real-world scenarios.




News
---------------
<section class="profile-list-section">
  <ul class="profile-list">
    <li class="profile-list__item">
      <span class="profile-list__date">2026/06</span>
      <span class="profile-list__content">🎉 PhysRAG have been accepted to ECCV 2026!</span>
    </li>
  </ul>
</section>

Experience
--------------

<div class="experience-container">
  <div class="experience-card">
      <img src="images/ICT.png" alt="ICT logo" class="experience-logo">
      <div class="experience-info">
          <strong>Institute of Computing Technology, Chinese Academy of Sciences</strong><br>
          Sep 2026 - <br>
          M.S. Student with research training at 
          <a href="https://iaii.cas.cn/" target="_blank"><em>IAII</em></a>
      </div>
  </div>
</div>

<div class="experience-card">
    <img src="images/PKU.png" alt="PKU logo" class="experience-logo">
    <div class="experience-info">
        <strong>Peking University</strong><br>
        Nov 2025 - May 2026<br>
        Research Assistant
    </div>
</div>

<div class="experience-card">
    <img src="images/tjut.png" alt="TJUT logo" class="experience-logo">
    <div class="experience-info">
        <strong>Tianjin University of Technology</strong><br>
        Sep 2022 - July 2026<br>
        B.E. in Data Science and Big Data Technology
    </div>
</div>



Publications
--------------
<div class="pub-button-container">
  <button class="pub-button active" onclick="showPublications('all')">All Publications</button>
  <button class="pub-button" onclick="showPublications('featured')">Selected Only</button>
</div>

<div class="publication-card featured">
  <div style="display: flex; align-items: center;">
    <img src="https://itheresaapocalypse.github.io/images/game-multiverse.png" alt="Game multiverse survey" width="200" height="100" style="margin-right: 20px; object-fit: cover;">
    <div>
        <strong>Towards Generalist Game Players: An Investigation of Foundation Models in the Game Multiverse</strong><br>
        <i style="font-size: 13px;">
            <a href="https://itheresaapocalypse.github.io/academicpages.github.io/" target="_blank">Kuan Zhang</a>*,
            <a href="https://li-battery-dc.github.io/" target="_blank">Dongchen Liu</a>*,
            <a href="" target="_blank">Qiyue Zhao</a>*,
            <a href="" target="_blank">Tianyu Xin</a>*,
            <a href="https://selen-suyue.github.io" target="_blank"><span class="self-author">Yue Su</span></a>*,
            <a href="" target="_blank">Haisheng Wang</a>,
            <a href="" target="_blank">Han Yin</a>,
            <a href="" target="_blank">Hongbo Ma</a>,
            <a href="" target="_blank">Peize Li</a>,
            ...,
            <a href="https://yimingli-page.github.io/" target="_blank">Yiming Li</a>&dagger;
        </i><br>
        A survey of foundation models as generalist game players across datasets, models, harnesses, and benchmarks.
        <br>
        <b><i style="color:#83a1c7;">ArXiv Preprint &nbsp;</i></b>
        <a href="https://arxiv.org/abs/2605.09965"><em>[arXiv]</em></a>
        <a href="https://github.com/THUSI-Lab/Awesome-LFMs-Play-Games"><em>[code]</em></a>
    </div>
  </div>
</div>


<div class="publication-card non-featured">
    <img src="images/scope.png" alt="SCOPE" width="200" height="100" style="margin-right: 20px;">
    <div>
        <strong>SCOPE: Simulating Cross-game Operations in Playable Environments for FPS World Models</strong><br>
        <i style="font-size: 13px;">
            Zizhao Tong<sup>†</sup>, 
            Yeying Jin<sup>†✉</sup>, 
            Hongfeng Lai<sup>†</sup>, 
            Zeqing Wang<sup>†</sup>, 
            Zhaohu Xing, 
            <span class="self-author">Kexu Cheng</span>, 
            Haoran Xu, 
            Zhao Pu, 
            Shangwen Zhu, 
            Ruili Feng, 
            Jian Zhao, 
            Yan Zhang, 
            Hao Tang, 
            Ling Shao<sup>✉</sup>
        </i><br>
        A playable FPS world model framework for simulating cross-game operations in interactive FPS environments.<br>
        <b><i style="color:#83a1c7;">ArXiv Preprint &nbsp;</i></b>
        <a href="https://arxiv.org/abs/2605.23345" target="_blank"><em>[arxiv]</em></a>
        <a href="https://z2tong.github.io/SCOPE/" target="_blank"><em>[project]</em></a>
    </div>
</div>

<div class="publication-card non-featured">
    <img src="images/paiworld.png" alt="PAIWorld" width="200" height="100" style="margin-right: 20px;">
    <div>
        <strong>PAIWorld: A 3D-Consistent World Foundation Model for Robotic Manipulation</strong><br>
        <i style="font-size: 13px;">
            Yuhang Huang, Xuan Lv, Junyan Xu, Zhiyuan Yu, ..., 
            Yan Zhang, <span class="self-author">Kexu Cheng</span>, ..., 
            Yunji Chen, Bin Wu, Haibin Yu, 
            Kai Xu<sup>✉</sup>
        </i><br>
        A 3D-consistent world foundation model for robotic manipulation with geometry-aware cross-view attention and 3D geometric priors.<br>
        <b><i style="color:#83a1c7;">ArXiv Preprint / Technical Report &nbsp;</i></b>
        <a href="https://arxiv.org/abs/2606.18375" target="_blank"><em>[arxiv]</em></a>
        <a href="https://guhuangai.github.io/PAIWorld-Proj" target="_blank"><em>[project]</em></a>
    </div>
</div>


<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>

Projects
--------
<div class="project-card">
 <div style="display: flex; align-items: center;">
    <img src="images/maniunicon.png" alt="Maniunicon" width="200" height="100" style="margin-right: 20px;">
    <div>
        <strong>ManiUniCon: A Unified Control Interface for Robotic Manipulation</strong><br>
ManiUniCon is a comprehensive, multi-process robotics control framework designed for robotic manipulation tasks. It provides a unified interface for controlling various robot arms, integrating sensors, and executing policies in real-time. <br>
      <b><i style="color:#83a1c7;">Universal-Control Team &nbsp;</i></b>
      <a href="https://github.com/Universal-Control/ManiUniCon"><em>[code]</em></a>
    </div>
</div>
</div>
<div class="project-card">
 <div style="display: flex; align-items: center;">
    <img src="images/MetaPalace.png" alt="MetaPalace" width="200" height="100" style="margin-right: 20px;">
    <div>
        <strong>MetaPalace: Let you in a meta world of The Palace Museum</strong><br>
We've done what the Old Palace official website couldn't: offering 3D artifact views with single-view reconstruction and an interactive LLM-powered tour guider using RAG technology. <br>
      <a href="https://metapalace.xj63.fun/"><em>[website]</em></a> 
      <a href="https://github.com/xj63/MetaPalaceSite"><em>[front-end code]</em></a>
      <a href="https://github.com/Selen-Suyue/MetaPalace"><em>[back-end code]</em></a>
    </div>
</div>
</div>


Awards
--------
<section class="profile-list-section">
  <ul class="profile-list">
    <li class="profile-list__item">
      <span class="profile-list__date">2025</span>
      <span class="profile-list__content">Xiaomi Outstanding Scholarship</span>
    </li>
    <li class="profile-list__item">
      <span class="profile-list__date">2025</span>
      <span class="profile-list__content">National Scholarship</span>
    </li>
    <li class="profile-list__item">
      <span class="profile-list__date">2025</span>
      <span class="profile-list__content">Outstanding Student, Xidian University</span>
    </li>
  </ul>
</section>

Talks
--------
<section class="profile-list-section">
  <ul class="profile-list">
    <li class="profile-list__item">
      <span class="profile-list__date">2026/03</span>
      <span class="profile-list__content">Invited to <a href="http://xhslink.com/o/74L1xM2Vw2f">Talk on RoboTion</a> about WoG.</span>
    </li>
    <li class="profile-list__item">
      <span class="profile-list__date">2025/12</span>
      <span class="profile-list__content">Invited to <a href="https://www.bilibili.com/video/BV1utBrBfED4?spm_id_from=333.788.videopod.episodes&p=9">Talk on NICE seminar</a> about Imitation Learning.</span>
    </li>
    <li class="profile-list__item">
      <span class="profile-list__date">2025/12</span>
      <span class="profile-list__content">Invited to <a href="https://b23.tv/We6FLQh">Talk on RL China</a> about DSPv2.</span>
    </li>
    <li class="profile-list__item">
      <span class="profile-list__date">2025/10</span>
      <span class="profile-list__content">Invited to <a href="https://b23.tv/PvLKNR1">Talk on 3D视觉工坊</a> about DSP and DSPv2.</span>
    </li>
  </ul>
</section>
