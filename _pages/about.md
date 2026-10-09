---
layout: about
title: about
permalink: /
# subtitle: Undergraduate Student in Electronic and Information Engineering at Imperial College London

profile:
  align: right
  image: pic.jpg  # Change this to your new image filename
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>London, United Kingdom</p>
    <p>zecheng.zhu23@imperial.ac.uk</p>
    <p>Imperial College London</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---



Hii! I'm a Master by Research student in AI and Machine Learning at Imperial College London, supervised by [Prfs. Stephen James](https://stepjam.github.io) at [Safe Whole-body Intelligent Robotics Lab (SWIRL)](https://www.swirl.uk/home). I completed my BEng in Electronic and Information Engineering at Imperial College London.

Prior to this, I did research with Berkeley Hybrid Robotics Lab, and interned at PsiBot on reinforcement learning post-training.



Find more in my [Curriculum Vitae](/assets/pdf/CV_Zecheng_Zhu.pdf).

<div style="clear: both;"></div>

<h2><a href="{{ '/projects/' | relative_url }}" style="color: inherit;">selected projects</a></h2>

<div class="publications">
  <ol class="bibliography">
    <li>
      <div class="row">
        <div class="col-sm-2 preview">
          <img src="{{ 'assets/img/bigym2.png' | relative_url }}" class="preview z-depth-1 rounded" style="width: 100%; min-width: 80px; max-width: 200px;" alt="bigym2" loading="lazy">
        </div>
        <div id="bigym2" class="col-sm-8">
        <div class="title">BiGym 2.0: Benchmarking Learned and Agent-Developed Policies for Humanoid Household Manipulation</div>
        <div class="author">Zexi Zhang*, <em><strong>Zecheng Zhu</strong></em>*, Zidong Chen, Zulkhuu Tuya, and Stephen James</div>
        <div class="periodical"><em>Under review</em></div>
        <div class="links">
          <a class="abstract btn btn-sm z-depth-0" role="button">Abs</a>
          <a href="https://arxiv.org/abs/2610.07594" class="btn btn-sm z-depth-0" role="button" rel="external nofollow noopener" target="_blank">arXiv</a>
          <a href="https://bigym2.github.io" class="btn btn-sm z-depth-0" role="button" rel="external nofollow noopener" target="_blank">Website</a>
        </div>
        <div class="abstract hidden"><p>A household-manipulation benchmark for a walking humanoid: BiGym adapted to the Unitree G1, with 20 tasks, 60 human virtual-reality demonstrations per task, and one shared whole-body controller. Under the same observations and actions, a cold-start coding agent averages 53% on nine tasks, close to a diffusion policy. Under review.</p></div>
        </div>
      </div>
    </li>
    <li>
      <div class="row">
        <div class="col-sm-2 preview">
          <img src="{{ 'assets/img/safeyield.png' | relative_url }}" class="preview z-depth-1 rounded" style="width: 100%; min-width: 80px; max-width: 200px;" alt="safeyield" loading="lazy">
        </div>
        <div id="safeyield" class="col-sm-8">
        <div class="title">SafeYield: A Generalizable Recovery Framework for Safe Robot Manipulation</div>
        <div class="author"><em><strong>Zecheng Zhu</strong></em> and Stephen James</div>
        <div class="periodical"><em>Under review</em></div>
        <div class="links">
          <a class="abstract btn btn-sm z-depth-0" role="button">Abs</a>
        </div>
        <div class="abstract hidden"><p>A recovery module on a frozen manipulation policy. It detects a person entering the workspace, yields, returns to the pre-interruption pose, and restores the policy so the task resumes instead of restarting. On 10 BiGym tasks, collisions fell from 78.8% to 1.6% and success rose from 57.6% to 75.6%. Under review.</p></div>
        </div>
      </div>
    </li>
    <li>
      <div class="row">
        <div class="col-sm-2 preview">
          <img src="{{ 'assets/img/fqc.png' | relative_url }}" class="preview z-depth-1 rounded" style="width: 100%; min-width: 80px; max-width: 200px;" alt="fqc" loading="lazy">
        </div>
        <div id="fqc" class="col-sm-8">
        <div class="title">Factored Q-Chunking</div>
        <div class="periodical"><em>Under review</em></div>
        <div class="links">
          <a class="abstract btn btn-sm z-depth-0" role="button">Abs</a>
        </div>
        <div class="abstract hidden"><p>In reinforcement learning from demonstrations, the slow part of the robot commits for a full action chunk while the fast part re-plans halfway, and each critic scores only the actions it executes. With the same actor and budget as Q-chunking, online fine-tuning success went from 0.102 to 0.327 on an arm and hand, and from 0.302 to 0.480 on a mobile base with two arms. Under review.</p></div>
        </div>
      </div>
    </li>
  </ol>
  <p style="font-size: 0.8rem;">* Equal contribution</p>
</div>

**Languages**: Python, C++, C, SQL, SystemVerilog  
**Skills**: Isaac Sim/Gym/Lab, PyTorch, ROS, Linux, Git, Embedded Platforms (ESP/STM)
