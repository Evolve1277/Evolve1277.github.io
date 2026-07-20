---
permalink: /
title: ""
excerpt: "Master of Engineering student at Huazhong University of Science and Technology, with research interests in computer vision, acoustic intelligence, and embodied AI."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<p class="profile-lead">I am a Master of Engineering student in Electronic Information at <a href="https://www.hust.edu.cn/">Huazhong University of Science and Technology</a> (HUST). I received my Bachelor of Engineering in Electronic Information Engineering from HUST in 2026, ranking first in my cohort.</p>

My research explores how intelligent systems learn robust representations from visual, acoustic, and embodied interaction data. I am particularly interested in weakly supervised learning, self-supervised representation learning, acoustic anomaly detection, and world models for robotic decision-making.

# Publications

{% comment %}Publication entries will be added here.{% endcomment %}

# Research Experience

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>Weakly Supervised Object Detection with Self-Supervised Vision Transformers</strong><span>Feb. 2026 - Jun. 2026</span></div>
  <p>Undergraduate thesis. Developed a proposal-generation framework that combines DINOv3 representations with multi-source class activation maps, extremal seed extraction, spatial grid sampling, and adaptive Otsu thresholding. Integrated the resulting proposals into an OICR multiple-instance learning pipeline and improved mAP on PASCAL VOC 2007 by 12.3 percentage points over the baseline. Conducted ablation studies, comparative experiments, and qualitative visualization analyses.</p>
</div>

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>Acoustic Anomaly Detection and Fault Classification for Converter Transformers</strong><span>Sep. 2024 - Jun. 2025</span></div>
  <p>State Grid Open Fund project. Built and validated an acoustic data acquisition pipeline with real-time RTP transmission, extracted MFCC features, and developed a VAE-based unsupervised anomaly detector trained exclusively on normal samples. The deployed system achieved 99% detection accuracy and incorporated noise separation for online inference. The project received the National Grand Prize in the Challenge Cup competition and contributed to a publication in <i>Electric Power Systems Research</i>.</p>
</div>

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>Deep-Learning-Based Short-Utterance Speaker Recognition</strong><span>Feb. 2024 - Jun. 2024</span></div>
  <p>Provincial Undergraduate Innovation Program. Investigated text-independent speaker recognition from one-second utterances using Fbank features, a lightweight residual encoder, and a Siamese learning architecture. Contributed to the web interface, backend data management, and hardware deployment. The project received an Excellent rating at its final review.</p>
</div>

# Honors and Awards

- National Grand Prize, 19th Challenge Cup National Undergraduate Extracurricular Academic Science and Technology Competition
- National Second Prize, 9th Huawei ICT Competition
- National Second Prize, 18th Chinese Collegiate Computing Competition
- National Third Prize, 16th Lanqiao Cup National Software and Information Technology Competition
- Provincial Second Prize, 10th Huawei Software Elite Challenge
- National Scholarship; HUST Outstanding Student Model; HUST Distinguished Undergraduate; HUST Outstanding Graduate

# Education

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>Master of Engineering in Electronic Information, Huazhong University of Science and Technology</strong><span>2026 - 2029</span></div>
  <p>Expected graduation: June 2029.</p>
</div>

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>Bachelor of Engineering in Electronic Information Engineering, Huazhong University of Science and Technology</strong><span>2022 - 2026</span></div>
  <p>Ranked 1st out of 20 students. Selected coursework includes Machine Learning, Software Engineering, Intelligent Robotics, Deep Learning, and C Programming.</p>
</div>

# Industry Research Experience

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>Research Intern, Moqi Intelligence (Remote)</strong><span>Dec. 2025 - Jun. 2026</span></div>
  <p>Extended the Genie Envisioner/GE-Act codebase for action-conditioned world modeling and robotic manipulation. Built LeRobot-compatible multi-view data pipelines for CALVIN, RoboTwin2.0, and RoboDojo with relative joint actions, six-frame observation histories, 17-frame future sequences, and 102-step action chunks. Diagnosed and corrected an off-by-one indexing error between state, action, and future-video supervision, and aligned validation sampling with the corrected training contract.</p>
  <p>Developed action-safe joint video-action training with history-only action cross-attention, causal video masking, terminal-hold handling at episode boundaries, and cosine-scheduled replacement of ground-truth conditions with model-generated action proposals. Added deployment-aligned two-step action rollout, controllable video-to-action gradient flow, action-intervention experiments, and aligned/sliding-window FVD evaluation. Optimized distributed training with bfloat16, TF32, DeepSpeed ZeRO-2, metadata caching, and data-loader tuning, and established a RoboTwin2.0 simulation benchmark with a 92% average task success rate.</p>
</div>
