---
layout: page
title: ""
permalink: /
nav: false
---

<style>
  :root {
    --site-paper: #fffefa;
    --site-ink: #27251f;
    --site-muted: #77736b;
    --site-line: #e9e4d8;
    --site-accent: #b18426;
  }
  :root[data-theme="dark"] {
    --site-paper: #171816;
    --site-ink: #ece9df;
    --site-muted: #aaa69b;
    --site-line: #393a34;
    --site-accent: #d8b45d;
  }
  body { background: var(--site-paper); color: var(--site-ink); }
  main { max-width: 760px !important; margin-inline: auto; }
  .theme-toggle { align-items: center; background: transparent; border: 1px solid var(--site-line); border-radius: 50%; color: var(--site-ink); cursor: pointer; display: inline-flex; height: 40px; justify-content: center; position: fixed; right: max(1.25rem, calc((100vw - 900px) / 2)); top: 1.25rem; transition: background .2s, border-color .2s; width: 40px; z-index: 10; }
  .theme-toggle:hover { background: color-mix(in srgb, var(--site-accent) 12%, transparent); border-color: var(--site-accent); }
  .theme-toggle svg { height: 19px; width: 19px; }
  .theme-toggle .sun-icon { display: none; }
  :root[data-theme="dark"] .theme-toggle .moon-icon { display: none; }
  :root[data-theme="dark"] .theme-toggle .sun-icon { display: block; }
  .site-home { font-family: Georgia, 'Times New Roman', serif; font-size: 1.08rem; line-height: 1.7; }
  .site-home h1, .site-home h2, .site-home h3 { color: var(--site-ink); font-family: inherit; font-weight: 500; }
  .site-home h1 { font-size: clamp(2.3rem, 6vw, 3.2rem); letter-spacing: -.045em; line-height: 1.1; margin: .3rem 0 .55rem; }
  .site-home h2 { font-size: 1.55rem; letter-spacing: -.025em; margin: 3.2rem 0 1rem; }
  .site-home a { color: color-mix(in srgb, var(--site-accent) 75%, var(--site-ink)); text-decoration-color: var(--site-accent); text-underline-offset: .18em; }
  .site-home a:hover { color: var(--site-ink); }
  .site-home .eyebrow, .site-home .meta, .site-home .links, .site-home .date { font-family: system-ui, sans-serif; font-size: .88rem; }
  .site-home .eyebrow { color: var(--site-muted); letter-spacing: .08em; text-transform: uppercase; }
  .site-home .intro { align-items: center; display: flex; gap: 1.5rem; justify-content: space-between; }
  .site-home .intro-copy { min-width: 0; }
  .site-home .portrait { border-radius: 50%; height: 126px; object-fit: cover; object-position: center 24%; width: 126px; }
  .site-home .links { display: flex; flex-wrap: wrap; gap: 1.2rem; margin: 1.1rem 0 2.7rem; }
  .site-home .bio { max-width: 690px; }
  .site-home .paper { border-top: 1px solid var(--site-line); padding: 1.15rem 0 1.35rem; }
  .site-home .paper-title { font-size: 1.15rem; font-weight: 600; line-height: 1.4; }
  .site-home .authors, .site-home .venue { color: var(--site-muted); font-family: system-ui, sans-serif; font-size: .91rem; line-height: 1.6; margin: .35rem 0 0; }
  .site-home .authors u { color: var(--site-ink); text-decoration-color: var(--site-accent); text-underline-offset: .17em; }
  .site-home .vitae { border-left: 1px solid var(--site-line); margin-left: .35rem; padding-left: 1.4rem; }
  .site-home .entry { margin: 0 0 1.7rem; position: relative; }
  .site-home .entry:before { background: var(--site-accent); border-radius: 50%; content: ''; height: 7px; left: -1.67rem; position: absolute; top: .55rem; width: 7px; }
  .site-home .entry-head { align-items: center; display: flex; gap: 1rem; justify-content: space-between; }
  .site-home .entry h3 { font-size: 1.12rem; margin: 0; }
  .site-home .org-logo { height: 32px; max-width: 112px; object-fit: contain; opacity: .9; }
  .site-home .org-logo.square { height: 34px; width: 34px; }
  .site-home .org-logo.safari { height: 54px; max-width: 104px; object-fit: contain; width: 104px; }
  .site-home .entry p { margin: .2rem 0 0; }
  .site-home .date, .site-home .meta { color: var(--site-muted); }
  .site-home .contact { border-top: 1px solid var(--site-line); margin-top: 3rem; padding-top: 1rem; }
  @media (max-width: 640px) { .site-home { font-size: 1rem; } .site-home .portrait { height: 92px; width: 92px; } .site-home .intro { gap: 1rem; } .site-home .org-logo { max-width: 88px; } .site-home h2 { margin-top: 2.6rem; } }
</style>

<div class="site-home" markdown="1">

<button class="theme-toggle" id="theme-toggle" type="button" aria-label="Switch to dark mode" title="Switch to dark mode">
  <svg class="moon-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M20.3 15.4A8.5 8.5 0 0 1 8.6 3.7 8.6 8.6 0 1 0 20.3 15.4Z"/></svg>
  <svg class="sun-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="4"/><path d="M12 2v2m0 16v2M4.93 4.93l1.42 1.42m11.3 11.3 1.42 1.42M2 12h2m16 0h2M4.93 19.07l1.42-1.42m11.3-11.3 1.42-1.42"/></svg>
</button>

<header class="intro">
  <div class="intro-copy">
    <p class="eyebrow">Computer architecture | Systems software</p>
    <h1>Vlad-Petru Nitu</h1>
    <p class="links"><a href="https://github.com/vlad-nitu">GitHub</a><a href="https://www.linkedin.com/in/vladnitu/">LinkedIn</a><a href="https://scholar.google.com/citations?user=HSTUFZQAAAAJ&amp;hl=en">Google Scholar</a><a href="/assets/pdf/Vlad-Petru_Nitu_CV.pdf">CV</a></p>
  </div>
  <img class="portrait" src="/assets/img/vlad-petru.png" alt="Portrait of Vlad-Petru Nitu">
</header>

<div class="bio">

I’m a Master’s student in Computer Science at ETH Zürich, working with the <a href="https://safari.ethz.ch/">SAFARI Research Group</a> under <a href="https://people.inf.ethz.ch/omutlu/">Prof. Onur Mutlu</a>. My research interests are at the hardware/software interface, in computer architecture and operating systems.

I recently interned as a software engineer at Optiver, working in a low-latency engineering team. Before ETH, I completed my BSc at TU Delft and interned as a software engineer at Bending Spoons.

Feel free to reach out: I’m always happy to chat about low-latency engineering, computer architecture research, or anything in between.

</div>

## Papers

<div class="paper">
  <div class="paper-title">Argus: Agentic, Reference-Calibrated, Tree-Guided, System-Software-Level Bottleneck Localization</div>
  <p class="authors"><u>Vlad-Petru Nitu</u>, Harsh Songara, Konstantinos Sgouras, Spiros Galanopoulos, Konstantinos Kanellopoulos, and Onur Mutlu</p>
  <p class="venue">Architecture 2.0 Workshop @ ISCA 2026 | <a href="https://arxiv.org/abs/2609.35508">arXiv</a> | <a href="https://github.com/CMU-SAFARI/Argus">Code</a></p>
</div>

<div class="paper">
  <div class="paper-title">Revelator: Rapid Data Fetching via System-Software-Guided Hash-based Speculative Address Translation</div>
  <p class="authors">Konstantinos Kanellopoulos, Konstantinos Sgouras, Harsh Songara, Andreas Kosmas Kakolyris, <u>Vlad-Petru Nitu</u>, Spiros Galanopoulos, Rahul Bera, Konstantina Koliogeorgi, Rakesh Kumar, and Onur Mutlu</p>
  <p class="venue">ISCA, 2026 | <a href="https://arxiv.org/abs/2508.02007">arXiv</a></p>
</div>

<div class="paper">
  <div class="paper-title">Valinor: Architectural Support for Fast, Energy-Efficient and Programmable Physical Memory Allocation</div>
  <p class="authors">Konstantinos Kanellopoulos, Spiros Galanopoulos, Konstantinos Sgouras, <u>Vlad-Petru Nitu</u>, Ilias Papalamprou, Andreas Kosmas Kakolyris, Rahul Bera, Dimosthenis Masouros, Dimitrios Soudris, and Onur Mutlu</p>
  <p class="venue">arXiv preprint, 2026 | <a href="https://arxiv.org/abs/2607.14789">arXiv</a></p>
</div>

## Vitae

<div class="vitae">
  <div class="entry"><p class="date">Jun 2026 – Sep 2026</p><div class="entry-head"><h3>Optiver</h3><img class="org-logo" src="/assets/img/logos/optiver.png" alt="Optiver logo"></div><p>Software Engineering Intern | C++ | Low Latency Engineering</p></div>
  <div class="entry"><p class="date">Sep 2024 – Mar 2027 (expected)</p><div class="entry-head"><h3>ETH Zürich</h3><img class="org-logo" src="/assets/img/logos/eth-zurich.svg" alt="ETH Zürich logo"></div><p>MSc in Computer Science | GPA: 5.7/6.0 (expected)</p><p class="meta">Secure &amp; Reliable Systems major | Systems Software minor</p><p class="meta">Relevant coursework: Advanced Operating Systems, Compiler Design, Advanced Computer Architecture, Hardware Security, HPC, Advanced Systems Lab, Synthesis of Digital Circuits</p></div>
  <div class="entry"><p class="date">Jun 2025 – Aug 2025 | Feb 2026 – Jun 2026 | Sep 2026 – present</p><div class="entry-head"><h3>SAFARI Research Group | ETH Zürich</h3><img class="org-logo safari" src="/assets/img/logos/safari.jpg" alt="SAFARI Research Group logo"></div><p>Research student | Computer architecture and operating systems</p></div>
  <div class="entry"><p class="date">Aug 2023 – Dec 2023</p><div class="entry-head"><h3>University of Illinois Urbana-Champaign</h3><img class="org-logo square" src="/assets/img/logos/uiuc-block-i.svg" alt="University of Illinois logo"></div><p>GPA: 4.0/4.0 | Dean’s List</p><p class="meta">Relevant coursework: Systems Programming, Computer System Organization</p></div>
  <div class="entry"><p class="date">Jul 2024 – Sep 2024</p><div class="entry-head"><h3>Bending Spoons</h3><img class="org-logo" src="/assets/img/logos/bending-spoons.svg" alt="Bending Spoons logo"></div><p>Software Engineering Intern | Backend &amp; Infrastructure Engineering</p></div>
  <div class="entry"><p class="date">Sep 2021 – Jun 2024</p><div class="entry-head"><h3>TU Delft</h3><img class="org-logo" src="/assets/img/logos/tudelft.svg" alt="TU Delft logo"></div><p>BSc in Computer Science | GPA: 9.07/10.0 | Top 2%</p><p class="meta">Graduated with distinction and honors</p></div>
</div>

<p class="contact">Zurich, Switzerland | <a href="mailto:nituvladpetru@gmail.com">Email</a></p>
<p class="last-updated">Last Updated: <time>{{ site.time | date: "%B %-d, %Y" }}</time></p>

</div>

<script>
  (() => {
    const root = document.documentElement;
    const button = document.getElementById('theme-toggle');
    const savedTheme = localStorage.getItem('vlad-theme');
    if (savedTheme === 'dark') root.setAttribute('data-theme', 'dark');
    button.addEventListener('click', () => {
      const dark = root.getAttribute('data-theme') !== 'dark';
      if (dark) root.setAttribute('data-theme', 'dark');
      else root.removeAttribute('data-theme');
      localStorage.setItem('vlad-theme', dark ? 'dark' : 'light');
      button.setAttribute('aria-label', `Switch to ${dark ? 'light' : 'dark'} mode`);
      button.setAttribute('title', `Switch to ${dark ? 'light' : 'dark'} mode`);
    });
    if (savedTheme === 'dark') {
      button.setAttribute('aria-label', 'Switch to light mode');
      button.setAttribute('title', 'Switch to light mode');
    }
  })();
</script>
