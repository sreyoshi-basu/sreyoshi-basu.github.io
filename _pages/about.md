---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .about-wrap { display: flex; gap: 2.5em; align-items: flex-start; }
  .about-main { flex: 3; min-width: 0; text-align: justify; hyphens: auto; }
  .about-side { flex: 1.2; font-size: 0.85em; border-left: 3px solid rgba(128,128,128,0.4); padding-left: 1.2em; }
  .about-side h3 { margin-top: 0; }
  .about-side p { margin: 0 0 1em 0; line-height: 1.4; }
  .news-card { position: relative; border-radius: 10px; background: rgba(128,128,128,0.08); padding: 1em 1em 0 1em; }
  .news-card::after { content: ""; position: absolute; left: 0; right: 0; bottom: 0; height: 40px; border-radius: 0 0 10px 10px; pointer-events: none;
    background: linear-gradient(to bottom, transparent, var(--global-bg-color, #fff)); opacity: 0.9; }
  .tl { max-height: 240px; overflow-y: auto; padding: 0 0.5em 2em 1.4em; margin-left: 0.3em; border-left: 2px solid rgba(128,128,128,0.3); text-align: left;
    scrollbar-width: thin; scrollbar-color: rgba(128,128,128,0.4) transparent; }
  .tl::-webkit-scrollbar { width: 5px; }
  .tl::-webkit-scrollbar-thumb { background: rgba(128,128,128,0.4); border-radius: 5px; }
  .tl-item { position: relative; margin-bottom: 1em; }
  .tl-item::before { content: ""; position: absolute; left: -1.85em; top: 0.3em; width: 10px; height: 10px; border-radius: 50%;
    background: #52adc8; box-shadow: 0 0 0 3px rgba(82,173,200,0.2); }
  .tl-date { font-size: 0.7em; font-weight: 600; text-transform: uppercase; letter-spacing: 0.06em; color: #52adc8; }
  .tl-text { font-size: 0.92em; line-height: 1.35; }
  @media (max-width: 900px) { .about-wrap { flex-direction: column; } .about-side { border-left: none; padding-left: 0; } }
</style>

<div class="about-wrap">

<div class="about-main" markdown="1">

I am interested in how linguistic structure is represented and processed, combining theoretical and experimental methods.

**Syntax.** Scrambling and word-order flexibility in
