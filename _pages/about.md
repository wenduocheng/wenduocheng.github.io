---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>
# About Me

I am **Wenduo Cheng**, a 2nd-year Ph.D. student in the [Ray and Stephanie Lane Computational Biology Department](https://www.cmu.edu/cbd/) at Carnegie Mellon University. I am fortunate to be advised by [Jian Ma](https://www.cs.cmu.edu/~jianma/). Before my Ph.D., I completed an M.S. in Computational Biology at CMU and a B.S. in Genetics and Genomics at [Duke Kunshan University](https://www.dukekunshan.edu.cn/).

My background spans bioinformatic sequence analysis, evolutionary biology, environmental science, genome-wide association studies, and deep learning for computational biology. My current research interests lie in applying AI to accelerate biological discovery, particularly through biological foundation models and autonomous agents. My work centers on these directions:

- **Biological Foundation Models:** I build biologically meaningful "virtual cell" models that capture evolutionary and regulatory constraints, aiming for representations that generalize across cell types, modalities, and biological contexts.
- **Autonomous Agents for Science:** I develop large language models and autonomous agents that accelerate experimental design, computational analysis, and lab automation, turning open-ended scientific questions into reproducible, executable workflows.
- **Gene Regulation & Multimodal Modeling:** I study the principles of gene regulation through multimodal modeling, integrating sequence, structure, and functional signals to reveal how regulatory information is encoded and read out.



# 🔥 News

<div class="news-scroll" markdown="1">

*06/2026:* 🎉 Our [SKILLFOUNDRY](https://arxiv.org/abs/2604.03964) paper is accepted by COLM 2026!

*05/2026:* 💼 I will be joining Genentech as an intern starting 05/2026!

*05/2026:* 🎉 Our [AgentCo-op](https://arxiv.org/abs/2605.20425) preprint is now available on arXiv!

*11/2025:* 🎉 DNALongBench has been featured for the [Nature Communications Editors' Highlights collection -- Computational and Theoretical Biology](https://www.nature.com/collections/cfhfejghec)!

*09/2025:* 🎉 Our [DNALongBench](https://doi.org/10.1038/s41467-025-65077-4) work is accepted by Nature Communications!

*08/2025:* 🎉 Our [L2G](https://openreview.net/forum?id=5NM4guc90N) paper is accepted by TMLR 2025!

</div>

<style>
.news-scroll {
  max-height: 220px;
  overflow-y: auto;
  padding: 0.5em 0;
  margin-bottom: 1.5em;
}
.news-scroll p:first-child { margin-top: 0; }
.news-scroll p:last-child { margin-bottom: 0; }
.news-scroll a { text-decoration: none; }
.news-scroll a:hover { text-decoration: underline; }

.pub-search-wrap { position: relative; margin: 0.6em 0 1.1em; }
.pub-search {
  width: 100%;
  box-sizing: border-box;
  padding: 0.55em 0.9em 0.55em 2.2em;
  font-size: 0.95em;
  color: #222;
  border: 1px solid #dfe6ef;
  border-radius: 999px;
  background: #fff;
  outline: none;
  transition: border-color 0.2s ease, box-shadow 0.2s ease;
}
.pub-search:focus {
  border-color: rgba(58, 123, 213, 0.55);
  box-shadow: 0 0 0 3px rgba(58, 123, 213, 0.12);
}
.pub-search-wrap::before {
  content: "\1F50D";
  position: absolute;
  left: 0.85em;
  top: 50%;
  transform: translateY(-50%);
  font-size: 0.85em;
  opacity: 0.55;
  pointer-events: none;
}
.pub-controls {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.5em;
  font-size: 0.9em;
  margin: 0 0 1.1em;
}
.pub-sort-label { color: #888; }
.pub-sort-dropdown {
  padding: 0.35em 0.7em;
  font-size: 0.95em;
  color: #222;
  border: 1px solid #dfe6ef;
  border-radius: 6px;
  background: #fff;
  cursor: pointer;
  outline: none;
  transition: border-color 0.15s ease, box-shadow 0.15s ease;
}
.pub-sort-dropdown:focus {
  border-color: rgba(58, 123, 213, 0.55);
  box-shadow: 0 0 0 3px rgba(58, 123, 213, 0.12);
}
.pub-kw {
  text-decoration: none;
  color: #3a7bd5;
  padding: 0.1em 0.55em;
  border-radius: 999px;
  transition: all 0.15s ease;
  border: 1px solid rgba(58, 123, 213, 0.28);
  background: rgba(58, 123, 213, 0.06);
  font-weight: 600;
}
.pub-kw:hover { background: rgba(58, 123, 213, 0.13); }
.pub-kw.active { color: #fff; background: #3a7bd5; border-color: #3a7bd5; }
.pub-kw-sep { color: #ccc; }
.pub-noresult { color: #888; font-size: 0.92em; padding: 0.4em 0.2em; display: none; }
.publications { margin-bottom: 1.5em; }
.publications ol.bibliography {
  display: grid;
  gap: 1rem;
  list-style: none;
  padding: 0;
  margin: 0;
}
.publications ol.bibliography > li {
  position: relative;
  overflow: hidden;
  margin: 0;
  padding: 1.1rem 1.2rem;
  border: 1px solid #dfe6ef;
  border-radius: 8px;
  background: #fff;
  box-shadow: 0 8px 24px rgba(9, 35, 77, 0.04);
  transition: border-color 0.2s ease, background 0.2s ease, box-shadow 0.2s ease, transform 0.2s ease;
}
.publications ol.bibliography > li::before {
  content: "";
  position: absolute;
  inset: 0 auto 0 0;
  width: 3px;
  background: linear-gradient(180deg, #3a7bd5, #7aa5e0);
  opacity: 0.45;
  transition: opacity 0.2s ease, width 0.2s ease;
}
.publications ol.bibliography > li:hover {
  border-color: rgba(58, 123, 213, 0.4);
  background: linear-gradient(120deg, rgba(58, 123, 213, 0.035), rgba(58, 123, 213, 0.015)), #fff;
  box-shadow: 0 16px 34px rgba(9, 35, 77, 0.10);
  transform: translateY(-2px);
}
.publications ol.bibliography > li:hover::before { width: 4px; opacity: 0.85; }
.pub-row {
  display: flex;
  align-items: flex-start;
  gap: 1.2em;
}
.pub-row .abbr {
  flex: 0 0 230px;
  text-align: center;
}
.pub-row .abbr { overflow: hidden; border-radius: 6px; }
.pub-row .teaser {
  width: 100%;
  max-height: 150px;
  object-fit: cover;
  border-radius: 6px;
  border: 1px solid #e0e0e0;
  background: #f6f6f6;
  display: block;
  cursor: zoom-in;
  transition: transform 0.25s ease;
}
.pub-row .teaser:hover { transform: scale(1.06); }

/* Lightbox */
.pub-lightbox {
  display: none;
  position: fixed;
  inset: 0;
  z-index: 1000;
  background: rgba(0, 0, 0, 0.82);
  align-items: center;
  justify-content: center;
  padding: 3vh 3vw;
  cursor: zoom-out;
}
.pub-lightbox.open { display: flex; }
.pub-lightbox img {
  max-width: 96vw;
  max-height: 92vh;
  border-radius: 6px;
  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5);
  cursor: default;
}
.pub-lightbox-close {
  position: absolute;
  top: 1.2rem;
  right: 1.6rem;
  font-size: 2rem;
  line-height: 1;
  color: #fff;
  background: none;
  border: none;
  cursor: pointer;
  opacity: 0.8;
}
.pub-lightbox-close:hover { opacity: 1; }
.pub-row .pub-info { flex: 1 1 auto; min-width: 0; }
.pub-row .title { font-weight: 700; line-height: 1.35; }
.pub-row .title a { color: inherit; }
.pub-row .author { font-size: 0.92em; margin-top: 0.15em; }
.pub-row .periodical { font-size: 0.92em; color: #555; margin-top: 0.15em; }
.pub-row .links { margin-top: 0.55em; display: flex; flex-wrap: wrap; gap: 0.4em; }
.pub-row .links .btn {
  display: inline-flex;
  align-items: center;
  font-size: 0.76em;
  font-weight: 700;
  color: #3a7bd5;
  border: 1px solid rgba(58, 123, 213, 0.28);
  border-radius: 999px;
  background: rgba(58, 123, 213, 0.06);
  padding: 0.16em 0.65em;
  text-decoration: none;
  transition: all 0.15s ease;
}
.pub-row .links .btn:hover {
  border-color: rgba(58, 123, 213, 0.55);
  background: rgba(58, 123, 213, 0.13);
  transform: translateY(-1px);
}
@media (max-width: 600px) {
  .pub-row { flex-direction: column; gap: 0.5em; }
  .pub-row .abbr { flex-basis: auto; width: 100%; text-align: left; }
  .pub-row .teaser { max-height: 160px; }
}
</style>

# 📝 Selected Publications

A full list of publications is available [here](https://scholar.google.com/citations?user=zXicNrUAAAAJ&hl=en&inst=3203679203499159833). († indicates equal contribution.)

<div class="publications" markdown="0">
<div class="pub-search-wrap">
  <input type="text" id="pub-search" class="pub-search" spellcheck="false" autocomplete="off" placeholder="Type to filter publications…" aria-label="Filter publications">
</div>
<div class="pub-controls">
  <label class="pub-sort-label" for="pub-sort">Sort by:</label>
  <select id="pub-sort" class="pub-sort-dropdown">
    <option value="time-desc">Time (Newest)</option>
    <option value="time-asc">Time (Oldest)</option>
    <option value="name-asc">Name (A-Z)</option>
    <option value="name-desc">Name (Z-A)</option>
  </select>
  <span class="pub-kw-sep">·</span>
  <a href="#" class="pub-kw" data-kw="agent">agent</a>
  <a href="#" class="pub-kw" data-kw="genomics">genomics</a>
</div>
<div class="pub-noresult" id="pub-noresult">No publications match your search.</div>
<ol class="bibliography">

<li data-year="2026" data-keywords="agent">
<div class="pub-row">
  <div class="abbr">
    <img class="teaser" src="{{ '/images/pubs/agentco-op.png' | relative_url }}" alt="AgentCo-op teaser">
  </div>
  <div class="pub-info">
    <div class="title">AgentCo-op: Retrieval-Based Synthesis of Interoperable Multi-Agent Workflows</div>
    <div class="author">Shuaike Shen<sup>&dagger;</sup>, <strong>Wenduo Cheng<sup>&dagger;</sup></strong>, Shike Wang, Mingqian Ma, Jian Ma</div>
    <div class="periodical"><em>arXiv preprint</em> arXiv:2605.20425, 2026.</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2605.20425" class="btn" role="button" target="_blank">Paper</a>
      <a href="https://github.com/ma-compbio-lab/AgentCo-Op.git" class="btn" role="button" target="_blank">Code</a>
      <a href="https://ma-compbio-lab.github.io/AgentCo-Op/" class="btn" role="button" target="_blank">Project Page</a>
    </div>
  </div>
</div>
</li>

<li data-year="2026" data-keywords="agent">
<div class="pub-row">
  <div class="abbr">
    <img class="teaser" src="{{ '/images/pubs/skillfoundry.png' | relative_url }}" alt="SkillFoundry teaser">
  </div>
  <div class="pub-info">
    <div class="title">SKILLFOUNDRY: Building Self-Evolving Agent Skill Libraries from Heterogeneous Scientific Resources</div>
    <div class="author">Shuaike Shen<sup>&dagger;</sup>, <strong>Wenduo Cheng<sup>&dagger;</sup></strong>, Mingqian Ma, Alistair Turcan, Martin Jinye Zhang, Jian Ma</div>
    <div class="periodical"><em>Conference on Language Modeling (COLM)</em>, 2026.</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2604.03964" class="btn" role="button" target="_blank">Paper</a>
      <a href="https://github.com/ma-compbio-lab/SkillFoundry.git" class="btn" role="button" target="_blank">Code</a>
      <a href="https://ma-compbio-lab.github.io/SkillFoundry/#overview" class="btn" role="button" target="_blank">Project Page</a>
    </div>
  </div>
</div>
</li>

<li data-year="2025" data-keywords="genomics">
<div class="pub-row">
  <div class="abbr">
    <img class="teaser" src="{{ '/images/pubs/dnalongbench.png' | relative_url }}" alt="DNALongBench teaser">
  </div>
  <div class="pub-info">
    <div class="title">DNALONGBENCH: A Benchmark Suite for Long-Range DNA Prediction Tasks</div>
    <div class="author"><strong>Wenduo Cheng<sup>&dagger;</sup></strong>, Zhenqiao Song<sup>&dagger;</sup>, Yang Zhang<sup>&dagger;</sup>, Shike Wang, Danqing Wang, Muyu Yang, Lei Li, Jian Ma</div>
    <div class="periodical"><em>Nature Communications</em> 16, p.10108, 2025. Editors' Highlights.</div>
    <div class="links">
      <a href="https://doi.org/10.1038/s41467-025-65077-4" class="btn" role="button" target="_blank">Paper</a>
      <a href="https://github.com/ma-compbio/DNALONGBENCH.git" class="btn" role="button" target="_blank">Code</a>
    </div>
  </div>
</div>
</li>

<li data-year="2025" data-keywords="genomics">
<div class="pub-row">
  <div class="abbr">
    <img class="teaser" src="{{ '/images/pubs/l2g.png' | relative_url }}" alt="L2G teaser">
  </div>
  <div class="pub-info">
    <div class="title">L2G: Repurposing Language Models for Genomics Tasks</div>
    <div class="author"><strong>Wenduo Cheng</strong>, Junhong Shen, Mikhail Khodak, Jian Ma, Ameet Talwalkar</div>
    <div class="periodical"><em>Transactions on Machine Learning Research (TMLR)</em>, 2025.</div>
    <div class="links">
      <a href="https://openreview.net/forum?id=5NM4guc90N" class="btn" role="button" target="_blank">Paper</a>
      <a href="https://github.com/wenduocheng/L2G.git" class="btn" role="button" target="_blank">Code</a>
    </div>
  </div>
</div>
</li>

<li data-year="2025" data-keywords="genomics">
<div class="pub-row">
  <div class="abbr">
    <img class="teaser" src="{{ '/images/pubs/dasha.png' | relative_url }}" alt="Specialized Foundation Models teaser">
  </div>
  <div class="pub-info">
    <div class="title">Specialized Foundation Models Struggle to Beat Supervised Baselines</div>
    <div class="author">Zongzhe Xu, Ritvik Gupta, <strong>Wenduo Cheng</strong>, Alexander Shen, Junhong Shen, Ameet Talwalkar, Mikhail Khodak</div>
    <div class="periodical"><em>International Conference on Learning Representations (ICLR)</em>, 2025.</div>
    <div class="links">
      <a href="https://doi.org/10.48550/arXiv.2411.02796" class="btn" role="button" target="_blank">Paper</a>
      <a href="https://github.com/ritvikgupta199/DASHA.git" class="btn" role="button" target="_blank">Code</a>
    </div>
  </div>
</div>
</li>

<li data-year="2022" data-keywords="biology">
<div class="pub-row">
  <div class="abbr">
    <img class="teaser" src="{{ '/images/pubs/cyano-selection.png' | relative_url }}" alt="Cyanobacterial blooms selection teaser">
  </div>
  <div class="pub-info">
    <div class="title">Cyanobacterial Blooms Are Not a Result of Positive Selection by Freshwater Eutrophication</div>
    <div class="author">Yang Yu<sup>&dagger;</sup>, <strong>Wenduo Cheng<sup>&dagger;</sup></strong>, Xiaoyuan Chen, Qisen Guo, Huansheng Cao</div>
    <div class="periodical"><em>Microbiology Spectrum</em> 12(3), e03194–22, 2022.</div>
    <div class="links">
      <a href="https://doi.org/10.1128/spectrum.03194-22" class="btn" role="button" target="_blank">Paper</a>
    </div>
  </div>
</div>
</li>

</ol>
</div>

<div class="pub-lightbox" id="pub-lightbox">
  <button class="pub-lightbox-close" id="pub-lightbox-close" aria-label="Close preview">&times;</button>
  <img id="pub-lightbox-img" src="" alt="Publication figure preview">
</div>

<script>
(function () {
  var box = document.getElementById('pub-lightbox');
  var boxImg = document.getElementById('pub-lightbox-img');
  var closeBtn = document.getElementById('pub-lightbox-close');
  if (!box || !boxImg) return;
  function open(src, alt) {
    boxImg.src = src;
    boxImg.alt = alt || 'Publication figure preview';
    box.classList.add('open');
    document.body.style.overflow = 'hidden';
  }
  function close() {
    box.classList.remove('open');
    boxImg.src = '';
    document.body.style.overflow = '';
  }
  Array.prototype.forEach.call(document.querySelectorAll('.publications .teaser'), function (img) {
    img.addEventListener('click', function () { open(img.src, img.alt); });
  });
  box.addEventListener('click', function (e) {
    if (e.target === box || e.target === closeBtn) close();
  });
  if (closeBtn) closeBtn.addEventListener('click', close);
  document.addEventListener('keydown', function (e) {
    if (e.key === 'Escape' && box.classList.contains('open')) close();
  });
})();
</script>

<script>
(function () {
  var input = document.getElementById('pub-search');
  var list = document.querySelector('.publications ol.bibliography');
  if (!input || !list) return;
  var items = Array.prototype.slice.call(list.querySelectorAll('> li'));
  var noResult = document.getElementById('pub-noresult');
  var sortSelect = document.getElementById('pub-sort');
  var kwLinks = Array.prototype.slice.call(document.querySelectorAll('.pub-kw'));
  var state = { q: '', sort: 'time-desc', kw: '' };

  function titleOf(li) { return li.querySelector('.title').textContent.trim().toLowerCase(); }
  function yearOf(li) { return parseInt(li.getAttribute('data-year'), 10) || 0; }

  function apply() {
    // filter
    var shown = 0;
    items.forEach(function (li) {
      var text = li.textContent.toLowerCase();
      var kws = (li.getAttribute('data-keywords') || '').toLowerCase();
      var matchQ = state.q === '' || text.indexOf(state.q) !== -1;
      var matchKw = state.kw === '' || kws.split(/\s+/).indexOf(state.kw) !== -1;
      var match = matchQ && matchKw;
      li.style.display = match ? '' : 'none';
      if (match) shown++;
    });
    if (noResult) noResult.style.display = (shown === 0) ? 'block' : 'none';
    // sort (reorder in DOM)
    var sorted = items.slice().sort(function (a, b) {
      switch (state.sort) {
        case 'time-asc':  return yearOf(a) - yearOf(b);
        case 'name-asc':  return titleOf(a) < titleOf(b) ? -1 : titleOf(a) > titleOf(b) ? 1 : 0;
        case 'name-desc': return titleOf(a) < titleOf(b) ? 1 : titleOf(a) > titleOf(b) ? -1 : 0;
        default:          return yearOf(b) - yearOf(a); // time-desc, newest first
      }
    });
    sorted.forEach(function (li) { list.appendChild(li); });
  }

  input.addEventListener('input', function () {
    state.q = input.value.trim().toLowerCase();
    apply();
  });
  if (sortSelect) {
    sortSelect.addEventListener('change', function () {
      state.sort = sortSelect.value;
      apply();
    });
  }
  kwLinks.forEach(function (link) {
    link.addEventListener('click', function (e) {
      e.preventDefault();
      var kw = link.getAttribute('data-kw');
      if (state.kw === kw) {           // toggle off
        state.kw = '';
        link.classList.remove('active');
      } else {
        state.kw = kw;
        kwLinks.forEach(function (l) { l.classList.remove('active'); });
        link.classList.add('active');
      }
      apply();
    });
  });

  apply();
})();
</script>

<!-- Hidden from selected publications:
- The Special and General Mechanism of Cyanobacterial Harmful Algal Blooms. Microorganisms 11(4), p.987, 2023. https://www.mdpi.com/2076-2607/11/4/987
- Draft Genome Sequence of an Epibiotic Bacterium, Bacillus cereus, Isolated from Cyanobacterial Blooms in Lake Taihu, China. Microbiology Resource Announcements 12(3), e00936–22, 2023. https://doi.org/10.1128/mra.00936-22
- RNA-sequencing and Mathematical Modeling Identify Suite of Light-Sensitive Circadian Genes in an Orb-Web Weaving Spider. Research Square, 2021. https://doi.org/10.21203/rs.3.rs-1036447/v1
-->

# 🎓 Education

- 2024–present, **Ph.D. in Computational Biology**, Carnegie Mellon University
- 2022-2024, **M.S. in Computational Biology**, Carnegie Mellon University
- 2018-2022, **B.S. in Genetics and Genomics**, Duke Kunshan University

# 🎲 Miscellaneous
I’m obsessed with anything involving a racket (pickleball, tennis, squash, badminton, you name it), plus ultimate frisbee and climbing whenever I can sneak it in. I’m also competitive at board games (e.g., 狼人杀, 三国杀, 剧本杀). And I spend a lot of time in the kitchen, happily experimenting with Chinese cuisine.
