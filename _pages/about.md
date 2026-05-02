---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# About Me
<span class='anchor' id='about-me'></span>

I'm a graduate researcher at the **KTH Royal Institute of Technology**, finishing my MSc in Systems, Control & Robotics with a thesis at **ABB Robotics** on generative models for long-horizon manipulation under formal specifications.

My current work uses **flow matching steered by Signal Temporal Logic robustness gradients** to plan robot trajectories that satisfy task specifications without retraining for each new task. Before this, I worked on 3D scene graphs at **Ericsson Research** (lead author on two submissions to IMPROVE 2026 and ICPR 2026), and on deformable object manipulation with vision-language models at the **KTH Robotics, Perception & Learning lab** (presented at ROMADO @ IROS 2025).

I'm drawn to methods that compose — small, well-understood building blocks combined at inference time, rather than monolithic policies retrained per task. Before Sweden, I completed a Dual Degree (B.Tech Engineering Design + M.Tech Robotics) at **IIT Madras**, with hands-on experience deploying real robotic systems at Systemantics, Yaskawa, and Imaginate.


# Research Interests
<span class='anchor' id='research-interests'></span>

<div style="display:flex;flex-direction:column;gap:14px;margin:16px 0;">

<div style="background:#eff6ff;border-left:4px solid #3b82f6;border-radius:8px;padding:16px 20px;">
<p style="font-size:15px;font-weight:700;color:#1e3a8a;margin:0 0 8px 0;">🤖 Generative Models for Robot Control</p>
<p style="font-size:13px;color:#374151;margin:0 0 12px 0;">Using formal specifications and learning together — neither replaces the other.</p>
<div style="margin-bottom:8px;">
<span style="font-size:13px;color:#374151;font-weight:500;">Signal Temporal Logic + Flow Matching for long-horizon planning</span><br>
<a href="#projects" style="background:#dbeafe;color:#1e40af;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;margin:2px 3px 2px 0;display:inline-block;">Thesis</a>
</div>
<div style="margin-bottom:8px;">
<span style="font-size:13px;color:#374151;font-weight:500;">Vision-Language Models with structured taxonomies for manipulation</span><br>
<a href="https://sites.google.com/view/tax-guided-vlm?pli=1" target="_blank" style="background:#dbeafe;color:#1e40af;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;margin:2px 3px 2px 0;display:inline-block;">IROS 2025 ROMADO</a>
</div>
<div style="margin-bottom:0;">
<span style="font-size:13px;color:#374151;font-weight:500;">Behavior Trees + RL for compositional task execution</span><br>
<a href="#projects" style="background:#dbeafe;color:#1e40af;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;margin:2px 3px 2px 0;display:inline-block;">Project</a>
</div>
</div>

<div style="background:#faf5ff;border-left:4px solid #a855f7;border-radius:8px;padding:16px 20px;">
<p style="font-size:15px;font-weight:700;color:#581c87;margin:0 0 8px 0;">🗺️ Perception, Mapping &amp; Multi-Agent Planning</p>
<p style="font-size:13px;color:#374151;margin:0 0 12px 0;">Building the spatial substrate that learning-based control needs.</p>
<div style="margin-bottom:8px;">
<span style="font-size:13px;color:#374151;font-weight:500;">3D Scene Graphs and privacy-preserving real-time mapping</span><br>
<a href="#publications" style="background:#e9d5ff;color:#6b21a8;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;margin:2px 3px 2px 0;display:inline-block;">IMPROVE 2026</a>
<a href="#publications" style="background:#f3f4f6;color:#4b5563;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;margin:2px 3px 2px 0;display:inline-block;">ICPR 2026 (Under Review)</a>
</div>
<div style="margin-bottom:8px;">
<span style="font-size:13px;color:#374151;font-weight:500;">Open-vocabulary semantic mapping with foundation models</span><br>
<a href="#projects" style="background:#f3f4f6;color:#4b5563;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;margin:2px 3px 2px 0;display:inline-block;">Project</a>
</div>
<div style="margin-bottom:0;">
<span style="font-size:13px;color:#374151;font-weight:500;">Multi-Agent Path Finding with Conflict-Based Search</span><br>
<a href="#projects" style="background:#f3f4f6;color:#4b5563;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;margin:2px 3px 2px 0;display:inline-block;">Project</a>
</div>
</div>

</div>


# News
<span class='anchor' id='news'></span>

<div style="position:relative;padding-left:28px;margin:16px 0;">
<div style="position:absolute;left:8px;top:6px;bottom:6px;width:2px;background:#e5e7eb;border-radius:1px;"></div>

<div style="position:relative;margin-bottom:14px;">
<div style="position:absolute;left:-22px;top:4px;width:10px;height:10px;border-radius:50%;background:#6366f1;border:2px solid white;box-shadow:0 0 0 2px #6366f1;"></div>
<div><span style="font-size:11px;color:#9ca3af;font-weight:500;">2026.04</span>&nbsp;<span style="background:#e0e7ff;color:#3730a3;padding:1px 6px;border-radius:3px;font-size:10px;font-weight:600;">📄 Paper</span></div>
<div style="margin-top:3px;font-size:13px;color:#374151;">Working on STL-guided flow matching for long-horizon manipulation as my MSc thesis at <strong>ABB Robotics</strong>. Targeting submission to a top robotics venue.</div>
</div>

<div style="position:relative;margin-bottom:14px;">
<div style="position:absolute;left:-22px;top:4px;width:10px;height:10px;border-radius:50%;background:#3b82f6;border:2px solid white;box-shadow:0 0 0 2px #3b82f6;"></div>
<div><span style="font-size:11px;color:#9ca3af;font-weight:500;">2026.01</span>&nbsp;<span style="background:#dbeafe;color:#1e40af;padding:1px 6px;border-radius:3px;font-size:10px;font-weight:600;">👔 Position</span></div>
<div style="margin-top:3px;font-size:13px;color:#374151;">Started Master's Thesis research at <strong>ABB Robotics</strong>, focusing on generative models for safe long-horizon manipulation under formal specifications.</div>
</div>

<div style="position:relative;margin-bottom:14px;">
<div style="position:absolute;left:-22px;top:4px;width:10px;height:10px;border-radius:50%;background:#3b82f6;border:2px solid white;box-shadow:0 0 0 2px #3b82f6;"></div>
<div><span style="font-size:11px;color:#9ca3af;font-weight:500;">2025.10</span>&nbsp;<span style="background:#dbeafe;color:#1e40af;padding:1px 6px;border-radius:3px;font-size:10px;font-weight:600;">📄 Paper</span></div>
<div style="margin-top:3px;font-size:13px;color:#374151;">Presented our work on taxonomy-guided vision-language models at the <strong><a href="https://sites.google.com/view/tax-guided-vlm?pli=1" target="_blank">IROS 2025 ROMADO</a></strong> workshop.</div>
</div>

<div style="position:relative;margin-bottom:14px;">
<div style="position:absolute;left:-22px;top:4px;width:10px;height:10px;border-radius:50%;background:#10b981;border:2px solid white;box-shadow:0 0 0 2px #10b981;"></div>
<div><span style="font-size:11px;color:#9ca3af;font-weight:500;">2025.07</span>&nbsp;<span style="background:#d1fae5;color:#065f46;padding:1px 6px;border-radius:3px;font-size:10px;font-weight:600;">👔 Position</span></div>
<div style="margin-top:3px;font-size:13px;color:#374151;">Joined Device Research Internship analyzing 3D Scene Graphs at <strong>Ericsson Research</strong> in Lund, Sweden.</div>
</div>

<div style="position:relative;margin-bottom:14px;">
<div style="position:absolute;left:-22px;top:4px;width:10px;height:10px;border-radius:50%;background:#8b5cf6;border:2px solid white;box-shadow:0 0 0 2px #8b5cf6;"></div>
<div><span style="font-size:11px;color:#9ca3af;font-weight:500;">2024.08</span>&nbsp;<span style="background:#ede9fe;color:#4c1d95;padding:1px 6px;border-radius:3px;font-size:10px;font-weight:600;">🎓 Milestone</span></div>
<div style="margin-top:3px;font-size:13px;color:#374151;">Started Master of Science in Systems, Controls, and Robotics at <strong>KTH Royal Institute of Technology</strong>.</div>
</div>

<div style="position:relative;margin-bottom:14px;">
<div style="position:absolute;left:-22px;top:4px;width:10px;height:10px;border-radius:50%;background:#8b5cf6;border:2px solid white;box-shadow:0 0 0 2px #8b5cf6;"></div>
<div><span style="font-size:11px;color:#9ca3af;font-weight:500;">2024.05</span>&nbsp;<span style="background:#ede9fe;color:#4c1d95;padding:1px 6px;border-radius:3px;font-size:10px;font-weight:600;">🎓 Milestone</span></div>
<div style="margin-top:3px;font-size:13px;color:#374151;">Graduated with Dual Degree in Engineering Design and Robotics at <strong>IIT Madras</strong>, concluding a thesis on Structure from Motion using COLMAP.</div>
</div>

</div>


# Selected Publications
<span class='anchor' id='publications'></span>

<p style="font-size:13px;color:#374151;margin-bottom:16px;"><em>For the full publication list, see my <a href="https://scholar.google.com/citations?user=Qy-ByYcAAAAJ&hl=en" target="_blank">Google Scholar</a>.</em></p>

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 110px; BACKGROUND-COLOR: #e2eff9; padding:8px;">
      <a href="https://sites.google.com/view/tax-guided-vlm?pli=1" target="_blank">
        <img src="./images/pub-romado-2025.png" width="100" height="80" style="object-fit:cover;" onerror="this.src='./images/pdf.png';this.style.height='100px'">
      </a>
    </td>
    <td style="padding:10px 14px;">
      <span style="font-weight:700;font-size:13px;">Scene Understanding in Deformable Object Manipulation via Taxonomy-Guided Vision-Language Models</span>
      <br><span style="font-size:12px;color:#374151;"><b>Gawtam Chithra Ramesh</b>, David Blanco-Mulero, Yifei Dong, Júlia Borràs Sol, Carme Torras, Florian T. Pokorny</span>
      <br><em style="font-size:12px;">IROS 2025 ROMADO Workshop</em>
      <br style="margin-top:6px;">
      <a href="https://sites.google.com/view/tax-guided-vlm?pli=1" target="_blank" style="background:#dbeafe;color:#1e40af;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;margin:4px 3px 0 0;display:inline-block;">project page</a>
    </td>
  </tr>
  </tbody>
</table>

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 110px; BACKGROUND-COLOR: #e2eff9; padding:8px;">
      <img src="./images/pub-improve-2026.png" width="100" height="80" style="object-fit:cover;" onerror="this.src='./images/pdf.png';this.style.height='100px'">
    </td>
    <td style="padding:10px 14px;">
      <span style="font-weight:700;font-size:13px;">[GAWTAM_TO_FILL: real title from your IMPROVE 2026 draft]</span>
      <br><span style="font-size:12px;color:#374151;">[GAWTAM_TO_FILL: full author list, with <b>Gawtam Chithra Ramesh</b> bolded]</span>
      <br><em style="font-size:12px;">IMPROVE 2026 (Accepted)</em>
      <br style="margin-top:6px;">
      <span style="background:#d1fae5;color:#065f46;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;display:inline-block;margin:4px 3px 0 0;">paper – to appear</span>
      <br><span style="font-size:12px;color:#6b7280;margin-top:4px;display:block;">[GAWTAM_TO_FILL: 1–2 sentence description of the paper]</span>
    </td>
  </tr>
  </tbody>
</table>

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 110px; BACKGROUND-COLOR: #e2eff9; padding:8px;">
      <img src="./images/pub-icpr-2026.png" width="100" height="80" style="object-fit:cover;" onerror="this.src='./images/pdf.png';this.style.height='100px'">
    </td>
    <td style="padding:10px 14px;">
      <span style="font-weight:700;font-size:13px;">[GAWTAM_TO_FILL: real title from your ICPR 2026 draft]</span>
      <br><span style="font-size:12px;color:#374151;">[GAWTAM_TO_FILL: full author list, with <b>Gawtam Chithra Ramesh</b> bolded]</span>
      <br><em style="font-size:12px;">ICPR 2026 (Under Review)</em>
      <br><span style="font-size:12px;color:#6b7280;margin-top:4px;display:block;">[GAWTAM_TO_FILL: 1–2 sentence description of the paper]</span>
    </td>
  </tr>
  </tbody>
</table>


# Projects
<span class='anchor' id='projects'></span>

<div style="display:flex;flex-direction:column;gap:16px;margin:16px 0;">

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:10px;padding:16px 18px;display:flex;gap:16px;align-items:flex-start;flex-wrap:wrap;">
<img src="./images/proj-stl-fm.gif" alt="STL Flow Matching" style="width:130px;height:90px;object-fit:cover;border-radius:6px;flex-shrink:0;" onerror="this.style.display='none'">
<div style="flex:1;min-width:200px;">
<div style="font-weight:700;font-size:14px;color:#111827;margin-bottom:4px;">STL-Guided Flow Matching for Long-Horizon Manipulation</div>
<p style="font-size:13px;color:#374151;margin:0 0 8px 0;">Master's thesis at ABB Robotics. Steering a single flow-matching model with Signal Temporal Logic robustness gradients to satisfy diverse task specifications at inference time, without retraining. Built on top of SafeFlowMatcher with STLCG++ for differentiable STL evaluation. Currently working on Maze2D and OGBench Cube benchmarks; head-to-head against DAG-STL and ZSTP.</p>
<div style="display:flex;flex-wrap:wrap;gap:5px;margin-bottom:8px;">
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Flow Matching</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Signal Temporal Logic</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Manipulation</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">PyTorch</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">MuJoCo</span>
</div>
<span style="background:#f3f4f6;color:#6b7280;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;">code – coming June 2026</span>
</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:10px;padding:16px 18px;display:flex;gap:16px;align-items:flex-start;flex-wrap:wrap;">
<img src="./images/proj-semantic-mapping.png" alt="Semantic Mapping" style="width:130px;height:90px;object-fit:cover;border-radius:6px;flex-shrink:0;" onerror="this.style.display='none'">
<div style="flex:1;min-width:200px;">
<div style="font-weight:700;font-size:14px;color:#111827;margin-bottom:4px;">Open-Vocabulary 3D Semantic Mapping + VLA Deployment</div>
<p style="font-size:13px;color:#374151;margin:0 0 8px 0;">Built a 3D semantic mapping pipeline from RGB-D data using OwlV2 (detection), SAM (segmentation), and CLIP (semantic grounding). 2D-to-3D projection with depth fusion produces a queryable scene representation. Deployed a pretrained VLA model for manipulation inference from visual + language inputs, then analyzed generalization failure modes. KTH Robot Learning &amp; Embodied AI course project.</p>
<div style="display:flex;flex-wrap:wrap;gap:5px;margin-bottom:8px;">
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">OwlV2</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">SAM</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">CLIP</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">VLA</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">RGB-D</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">PyTorch</span>
</div>
<a href="[GAWTAM_TO_FILL: GitHub repo URL]" target="_blank" style="background:#dbeafe;color:#1e40af;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;">GitHub – [GAWTAM_TO_FILL: repo name]</a>
</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:10px;padding:16px 18px;display:flex;gap:16px;align-items:flex-start;flex-wrap:wrap;">
<img src="./images/proj-dom-vlm.png" alt="Deformable Object Manipulation" style="width:130px;height:90px;object-fit:cover;border-radius:6px;flex-shrink:0;" onerror="this.style.display='none'">
<div style="flex:1;min-width:200px;">
<div style="font-weight:700;font-size:14px;color:#111827;margin-bottom:4px;">Vision-Language Models for Deformable Object Manipulation</div>
<p style="font-size:13px;color:#374151;margin:0 0 8px 0;">Research at KTH RPL with Florian Pokorny. Built a prompt–taxonomy framework that gets Gemini and Qwen to produce structured, robot-parsable specifications from natural-language task descriptions of cloth manipulation scenes. Quantified failure modes to guide iterative taxonomy refinement. Presented at ROMADO @ IROS 2025.</p>
<div style="display:flex;flex-wrap:wrap;gap:5px;margin-bottom:8px;">
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Vision-Language Models</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Gemini</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Qwen</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Cloth Manipulation</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Taxonomy</span>
</div>
<a href="https://sites.google.com/view/tax-guided-vlm?pli=1" target="_blank" style="background:#dbeafe;color:#1e40af;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;margin-right:6px;">project page</a>
<a href="[GAWTAM_TO_FILL: GitHub repo URL]" target="_blank" style="background:#dbeafe;color:#1e40af;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;">GitHub – [GAWTAM_TO_FILL: repo name]</a>
</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:10px;padding:16px 18px;display:flex;gap:16px;align-items:flex-start;flex-wrap:wrap;">
<img src="./images/proj-mapf.gif" alt="Multi-Agent Path Finding" style="width:130px;height:90px;object-fit:cover;border-radius:6px;flex-shrink:0;" onerror="this.style.display='none'">
<div style="flex:1;min-width:200px;">
<div style="font-weight:700;font-size:14px;color:#111827;margin-bottom:4px;">Multi-Agent Path Finding in Unity3D</div>
<p style="font-size:13px;color:#374151;margin:0 0 8px 0;">Hybrid A* path planner + waypoint tracking for kinematically constrained vehicles, plus Conflict-Based Search to resolve collisions for 20+ heterogeneous agents (cars and drones) sharing one environment. Greedy dynamic goal assignment for the multi-agent 'bakery problem'. KTH course project.</p>
<div style="display:flex;flex-wrap:wrap;gap:5px;margin-bottom:8px;">
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">MAPF</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Conflict-Based Search</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Hybrid A*</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Unity3D</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">C#</span>
</div>
<a href="[GAWTAM_TO_FILL: GitHub repo URL]" target="_blank" style="background:#dbeafe;color:#1e40af;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;">GitHub – [GAWTAM_TO_FILL: repo name]</a>
</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:10px;padding:16px 18px;display:flex;gap:16px;align-items:flex-start;flex-wrap:wrap;">
<img src="./images/proj-pacman-ctf.gif" alt="Pacman CTF" style="width:130px;height:90px;object-fit:cover;border-radius:6px;flex-shrink:0;" onerror="this.style.display='none'">
<div style="flex:1;min-width:200px;">
<div style="font-weight:700;font-size:14px;color:#111827;margin-bottom:4px;">RL + Behavior Trees for Pacman Capture-The-Flag</div>
<p style="font-size:13px;color:#374151;margin:0 0 8px 0;">Hybrid AI for Pacman CTF in Unity3D: a Behavior Tree handles high-level strategy while role-specific PPO policies (attack, defend, escape) handle low-level actions. Trained via Unity ML-Agents with phased training, self-play, and curriculum learning. Studied adaptive behavior switching in a partially observable competitive multi-agent setting.</p>
<div style="display:flex;flex-wrap:wrap;gap:5px;margin-bottom:8px;">
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Reinforcement Learning</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">PPO</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Behavior Trees</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Unity ML-Agents</span>
</div>
<a href="[GAWTAM_TO_FILL: GitHub repo URL]" target="_blank" style="background:#dbeafe;color:#1e40af;padding:2px 7px;border-radius:4px;font-size:11px;font-weight:600;text-decoration:none;">GitHub – [GAWTAM_TO_FILL: repo name]</a>
</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:10px;padding:16px 18px;display:flex;gap:16px;align-items:flex-start;flex-wrap:wrap;">
<img src="./images/proj-systemantics.png" alt="Systemantics" style="width:130px;height:90px;object-fit:cover;border-radius:6px;flex-shrink:0;" onerror="this.style.display='none'">
<div style="flex:1;min-width:200px;">
<div style="font-weight:700;font-size:14px;color:#111827;margin-bottom:4px;">6-DoF Manipulator Trajectory Generation @ Systemantics</div>
<p style="font-size:13px;color:#374151;margin:0 0 8px 0;">Designed and shipped a real-time 6-DoF trajectory generation and control pipeline in C++ for a collaborative robot arm. Joint actuation via low-latency D-Bus and SocketCAN communication with motor controllers. Backward-chained Behavior Trees coordinated long-horizon task planning.</p>
<div style="display:flex;flex-wrap:wrap;gap:5px;margin-bottom:8px;">
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">C++</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">ROS2</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">SocketCAN</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">D-Bus</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Behavior Trees</span>
<span style="background:#f3f4f6;color:#374151;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600;">Real-Time Control</span>
</div>
<span style="font-size:12px;color:#9ca3af;font-style:italic;">No public repo — proprietary.</span>
</div>
</div>

</div>


# Work Experiences
<span class='anchor' id='work-experiences'></span>

<div style="display:flex;flex-direction:column;gap:12px;margin:16px 0;">

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Master's Thesis Researcher</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">ABB Robotics</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Mentors: Matthew Lock, Jonathan Styrud</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">01/2026 – 06/2026</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Västerås, Sweden</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">STL-guided flow matching for long-horizon industrial manipulation.</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Graduate Research Assistant</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">KTH Robotics, Perception &amp; Learning Lab</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Advisor: Florian T. Pokorny</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">01/2025 – 11/2025</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Stockholm, Sweden</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">Taxonomy-guided VLMs for deformable object manipulation. Presented at ROMADO @ IROS 2025.</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Device Research Intern (3D Scene Graphs)</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">Ericsson Research</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Mentors: Püren Güler, Hector Caltenco</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">07/2025 – 12/2025</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Lund, Sweden</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">3D Scene Graph pipelines with instance segmentation, tracking, and privacy-preserving RGB-D inpainting. Lead author on IMPROVE 2026 (accepted) and ICPR 2026 (under review).</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Graduate Robotics Intern (Modular Collaborative Robots)</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">Systemantics India Pvt. Ltd.</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Mentor: Jagannath Raju</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">12/2022 – 07/2023</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Bangalore, India</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">Real-time 6-DoF trajectory generation in C++ over D-Bus/SocketCAN. Backward-chained Behavior Trees for long-horizon planning.</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Graduate Teaching Assistant — Field &amp; Service Robotics (ID4060)</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">IIT Madras</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Mentor: Bijo Sebastian</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">08/2023 – 11/2023</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Chennai, India</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">Designed and evaluated ROS + CoppeliaSim assignments for 40 students.</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Dual Degree Project — Structure from Motion for Autonomous Ultrasound</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">INSPIRE Lab, IIT Madras</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Advisor: Nirav Patel</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">01/2024 – 05/2024</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Chennai, India</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">COLMAP-based 3D torso reconstruction from monocular RGB; ROS + MoveIt motion planning for a 5-DoF arm to enable accessible ultrasound.</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Young Research Fellow — UAV Motion Planning &amp; Control</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">IIT Madras</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Advisor: Satadal Ghosh</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">09/2021 – 04/2022</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Chennai, India</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">Target-driven motion planning + obstacle avoidance for UAVs. 20% faster than classical aerospace baselines using proportional navigation + acceleration-velocity obstacles.</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Robotics Intern (Pallet Handling)</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">Yaskawa</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Mentor: Manju Tiwari</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">06/2021 – 07/2021</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Gurgaon, India</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">3D palletizing for mixed carton sizes using MotoSim and teach pendant. Memory-efficient C++ data transfer to robot.</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">MOT Research Intern</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">Blurgs Research Labs</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">06/2021 – 07/2021</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Remote, India</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">Benchmarked SiamMOT and FairMOT for drone + CCTV surveillance, for the startup's first product with the Indian Navy.</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Hyperloop Battery Pack — Avishkar Hyperloop</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">IIT Madras</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Advisors: Satya Chakravarthy, T.M. Muruganandam</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">10/2020 – 06/2021</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Chennai, India</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">Designed a high-discharge battery pack with aluminum heat sink for thermal management. Top 24 globally for European Hyperloop Week, Valencia.</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:14px 18px;">
<div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;">
<div>
<div style="font-weight:700;font-size:14px;color:#111827;">Software Development Intern</div>
<div style="font-size:13px;color:#4b5563;margin-top:3px;">Imaginate Software Labs</div>
</div>
<div style="text-align:right;">
<div style="font-size:12px;font-weight:600;color:#374151;">05/2020 – 08/2020</div>
<div style="font-size:12px;color:#6b7280;margin-top:2px;">Remote, India</div>
</div>
</div>
<div style="font-size:12px;color:#6b7280;margin-top:8px;">Unity3D + C# VR toolkit using Autodesk Forge APIs to import 60+ 3D file formats into VR in real time.</div>
</div>

</div>


# Skills
<span class='anchor' id='skills'></span>

<div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:12px;margin:16px 0;">

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:12px 16px;">
<div style="font-size:12px;font-weight:700;color:#374151;margin-bottom:8px;text-transform:uppercase;letter-spacing:0.05em;">Languages</div>
<div style="display:flex;flex-wrap:wrap;gap:5px;">
<span style="background:#dbeafe;color:#1e40af;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">Python</span>
<span style="background:#dbeafe;color:#1e40af;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">C++</span>
<span style="background:#dbeafe;color:#1e40af;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">C</span>
<span style="background:#dbeafe;color:#1e40af;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">C#</span>
</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:12px 16px;">
<div style="font-size:12px;font-weight:700;color:#374151;margin-bottom:8px;text-transform:uppercase;letter-spacing:0.05em;">Robotics</div>
<div style="display:flex;flex-wrap:wrap;gap:5px;">
<span style="background:#d1fae5;color:#065f46;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">ROS2</span>
<span style="background:#d1fae5;color:#065f46;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">MuJoCo</span>
<span style="background:#d1fae5;color:#065f46;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">Unity3D</span>
<span style="background:#d1fae5;color:#065f46;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">MATLAB</span>
<span style="background:#d1fae5;color:#065f46;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">Gazebo</span>
<span style="background:#d1fae5;color:#065f46;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">MoveIt</span>
</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:12px 16px;">
<div style="font-size:12px;font-weight:700;color:#374151;margin-bottom:8px;text-transform:uppercase;letter-spacing:0.05em;">ML / DL</div>
<div style="display:flex;flex-wrap:wrap;gap:5px;">
<span style="background:#ede9fe;color:#4c1d95;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">PyTorch</span>
<span style="background:#ede9fe;color:#4c1d95;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">JAX</span>
<span style="background:#ede9fe;color:#4c1d95;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">OpenCV</span>
<span style="background:#ede9fe;color:#4c1d95;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">W&amp;B</span>
<span style="background:#ede9fe;color:#4c1d95;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">CUDA</span>
</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:12px 16px;">
<div style="font-size:12px;font-weight:700;color:#374151;margin-bottom:8px;text-transform:uppercase;letter-spacing:0.05em;">Tools</div>
<div style="display:flex;flex-wrap:wrap;gap:5px;">
<span style="background:#fef3c7;color:#78350f;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">Docker</span>
<span style="background:#fef3c7;color:#78350f;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">Git</span>
<span style="background:#fef3c7;color:#78350f;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">Slurm</span>
<span style="background:#fef3c7;color:#78350f;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">LaTeX</span>
<span style="background:#fef3c7;color:#78350f;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">VS Code</span>
</div>
</div>

<div style="background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;padding:12px 16px;">
<div style="font-size:12px;font-weight:700;color:#374151;margin-bottom:8px;text-transform:uppercase;letter-spacing:0.05em;">CAD / Simulation</div>
<div style="display:flex;flex-wrap:wrap;gap:5px;">
<span style="background:#fee2e2;color:#7f1d1d;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">Fusion 360</span>
<span style="background:#fee2e2;color:#7f1d1d;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">SolidWorks</span>
<span style="background:#fee2e2;color:#7f1d1d;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">ANSYS</span>
<span style="background:#fee2e2;color:#7f1d1d;padding:2px 8px;border-radius:4px;font-size:12px;font-weight:600;">COMSOL</span>
</div>
</div>

</div>


# Honors and Awards
<span class='anchor' id='honors-and-awards'></span>

<div style="display:flex;flex-direction:column;gap:10px;margin:16px 0;">

<div style="background:#fffbeb;border-left:4px solid #f59e0b;border-radius:6px;padding:12px 16px;display:flex;align-items:center;gap:12px;">
<span style="font-size:20px;line-height:1;">🏆</span>
<span style="font-size:13px;color:#374151;font-weight:500;"><strong>IIT Madras Young Research Fellowship</strong> — selected among 30 of 800+ students based on research potential (2021)</span>
</div>

<div style="background:#f9fafb;border-left:4px solid #9ca3af;border-radius:6px;padding:12px 16px;display:flex;align-items:center;gap:12px;">
<span style="font-size:20px;line-height:1;">🎖️</span>
<span style="font-size:13px;color:#374151;font-weight:500;">Secured 99.10 percentile in JEE Mains, 97.64 percentile in JEE Advanced (1.5M candidates), and AIR 52 in UCEED (50k candidates).</span>
</div>

</div>


# Services and Responsibilities
<span class='anchor' id='services'></span>

<div style="margin:16px 0;">

<div style="font-size:13px;font-weight:700;color:#374151;margin-bottom:8px;">Academic &amp; Mentorship</div>
<div style="display:flex;flex-direction:column;gap:6px;">
<div style="display:flex;align-items:baseline;gap:12px;">
<span style="font-size:12px;font-weight:700;color:#9ca3af;min-width:34px;">2023</span>
<span style="font-size:13px;color:#374151;">Graduate Teaching Assistant, Field and Service Robotics (IIT Madras). Evaluated ROS and CoppeliaSim assignments.</span>
</div>
<div style="display:flex;align-items:baseline;gap:12px;">
<span style="font-size:12px;font-weight:700;color:#9ca3af;min-width:34px;">2025</span>
<span style="font-size:13px;color:#374151;">Student Buddy, THS International Winter Reception (KTH). Onboarded international students.</span>
</div>
</div>

<div style="font-size:13px;font-weight:700;color:#374151;margin:16px 0 8px 0;">Leadership</div>
<div style="display:flex;flex-direction:column;gap:4px;font-size:13px;color:#374151;">
<div>Head of Industrial and Public Relations, Dept. of Engineering Design (IIT Madras, 2021–2022). Mentored placement and internship processes for over 1,200 students.</div>
<div>Strategist, Computer Vision and Intelligence Group (IIT Madras, 2020–2021). Co-mentored Image Analysis projects and organized DL Summer School.</div>
</div>

</div>


# Educations
<span class='anchor' id='educations'></span>
  08/2024 - 07/2026

  Master of Science in Systems, Controls, and Robotics

  KTH Royal Institute of Technology, Sweden


  <hr style="border: none; border-top: 1px solid #e5e7eb; margin: 12px 0;">


  08/2019 - 07/2024

  Dual Degree (B.Tech in Engineering Design and M.Tech in Robotics)

  Indian Institute of Technology Madras, India
