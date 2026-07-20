---
permalink: /
title: "吴文彬"
excerpt: "华中科技大学电子信息专业硕士研究生，研究兴趣包括计算机视觉、声纹智能与具身世界模型。"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<p class="profile-lead">你好，我是吴文彬。目前就读于华中科技大学电子信息专业，即将于 2026 年 9 月开始硕士阶段学习。我关注让机器从视觉、声音和交互数据中理解世界，并将模型落地到可验证的系统中。</p>

<p class="profile-actions"><a class="btn btn--primary" href="{{ base_path }}/files/cv.pdf"><i class="fas fa-file-arrow-down" aria-hidden="true"></i> 下载简历</a> <a class="btn btn--inverse" href="mailto:u202210645@hust.edu.cn"><i class="fas fa-envelope" aria-hidden="true"></i> 联系我</a></p>

## 研究方向

计算机视觉（弱监督目标检测、自监督视觉表征）、声纹智能（异常检测与说话人识别）、具身智能（世界模型与机器人动作策略）。

## 关键成果

<div class="result-strip" aria-label="关键成果">
  <div class="result-item"><strong>1/20</strong><span>本科专业排名</span></div>
  <div class="result-item"><strong>+12.3</strong><span>VOC 2007 mAP 提升</span></div>
  <div class="result-item"><strong>92%</strong><span>RoboTwin2.0 平均成功率</span></div>
  <div class="result-item"><strong>99%</strong><span>声纹异常检测准确率</span></div>
</div>

## 项目经历
{: #projects}

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>本科生毕业设计 · 基于自监督视觉 Transformer 的弱监督目标检测研究</strong><span>2026.02 - 2026.06</span></div>
  <p>融合 DINOv3 自监督预训练模型，设计多源 CAM 融合、极值种子提取和空间网格采样策略；构建局部与全局语义相似度图，使用自适应 Otsu 多阈值分割生成高质量候选框，并在 OICR 多示例学习框架中完成训练。在 VOC 2007 上较基线提升 12.3 个百分点 mAP，并完成消融、对比实验和可视化分析。</p>
</div>

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>国家电网开放基金 · 换流变压器声纹异常检测与故障分类算法研究</strong><span>2024.09 - 2025.06</span></div>
  <p>搭建声纹采集模块并完成软硬件联调，基于 RTP 协议实时传输数据，使用 MFCC 提取特征并以正常样本训练 VAE 无监督异常检测模型，结合噪声分离算法完成在线部署与调试，检测准确率达 99%。项目获挑战杯全国特等奖，相关论文发表于 <i>Electric Power Systems Research</i>。</p>
</div>

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>省级大学生创新训练项目 · 基于深度学习的声纹识别算法研究与系统实现</strong><span>2024.02 - 2024.06</span></div>
  <p>面向 1 秒短时、任意文本语音输入，提取 Fbank 特征并采用轻量残差模型与孪生网络进行判别；参与开发前端展示页面和后端数据存储，并协助硬件部署验证，项目终期结题优秀。</p>
</div>

## 实习经历

<div class="resume-entry">
  <div class="resume-entry__heading"><strong>墨奇智能（远程） · 具身世界动作模型研究</strong><span>2025.12 - 2026.06</span></div>
  <p>调研 Cosmos Policy、DreamZero、Fast-WAM、Motus 等具身世界模型，处理 Calvin 与 RoboTwin 数据集并搭建标准化加载流水线；复现 VPP、Ge-act 等工作，比较 Transformer 层数和去噪步数对潜空间表征的影响，结合混合精度、模型编译、KV cache 与 pin_memory 优化训练，搭建 RoboTwin2.0 仿真评测环境，实现 92% 平均成功率。</p>
</div>

## 荣誉与奖励

- 第十九届“挑战杯”全国大学生课外学术科技作品竞赛 · 国家级特等奖
- 第九届华为 ICT 大赛 · 国家级二等奖
- 第十八届中国大学生计算机设计大赛 · 国家级二等奖
- 第十六届蓝桥杯软件与信息技术大赛 · 国家级三等奖
- 第十届华为软件精英挑战赛 · 省级二等奖
- 国家奖学金、校三好学生标兵、校本科特优生、校优秀毕业生

## 技能

熟悉 C、Python、Java，具备 Linux 操作系统与 Git 版本控制经验；了解 Diffusers 开源生态，能够使用 Claude Code、Codex 等工具进行快速原型开发。英语 CET-6 605 分。
