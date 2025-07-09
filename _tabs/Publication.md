---
layout: page
icon: fas fa-archive
order: 1
---

<style>
.conference-papers {
  counter-reset: conference-counter;
}
.conference-papers li {
  list-style-type: none;
  position: relative;
  padding-left: 30px;
  margin-bottom: 10px;
}
.conference-papers li:before {
  content: "[" counter(conference-counter) "]";
  counter-increment: conference-counter;
  position: absolute;
  left: 0;
}

.journal-articles {
  counter-reset: journal-counter;
}
.journal-articles li {
  list-style-type: none;
  position: relative;
  padding-left: 30px;
  margin-bottom: 10px;
}
.journal-articles li:before {
  content: "[" counter(journal-counter) "]";
  counter-increment: journal-counter;
  position: absolute;
  left: 0;
}

.preprints {
  counter-reset: preprint-counter;
}
.preprints li {
  list-style-type: none;
  position: relative;
  padding-left: 30px;
  margin-bottom: 10px;
}
.preprints li:before {
  content: "[" counter(preprint-counter) "]";
  counter-increment: preprint-counter;
  position: absolute;
  left: 0;
}

.author-highlight {
  font-weight: bold;
  text-decoration: underline;
}

.paper-title {
  font-style: italic;
}
</style>

## Conference Papers
<ul class="conference-papers">
<li><span class="author-highlight">Yunbo Lyu</span>, Zhou Yang, Yuqing Niu, Jing Jiang, David Lo. <span class="paper-title">"Do Existing Testing Tools Really Uncover Gender Bias in Text-to-Image Models?"</span> 2025 33rd ACM International Conference on Multimedia (ACMMM). (8 pages, Regular Papers)</li>
<li>Chengran Yang, Jiakun Liu, Bowen Xu, Christoph Treude, <span class="author-highlight">Yunbo Lyu</span>, Junda He, Ming Li, David Lo. <span class="paper-title">"APIDocBooster: An Extract-Then-Abstract Framework Leveraging Large Language Models for Augmenting API Documentation"</span> 2025 International Conference on Software Maintenance and Evolution (ICSME). (12 pages, Research Papers Track)</li>
<li>Alessio Bucaioni, Martin Weyssow, Junda He, <span class="author-highlight">Yunbo Lyu</span>, David Lo. <span class="paper-title">"Artificial Intelligence for Software Architecture: Literature Review and the Road Ahead"</span> FSE 2025 - 2030 Software Engineering Workshop. (11 pages)</li>
<li>Alessio Bucaioni, Martin Weyssow, Junda He, <span class="author-highlight">Yunbo Lyu</span>, David Lo. <span class="paper-title">"A Functional Software Reference Architecture for LLM-Integrated Systems"</span> 2025 IEEE 22nd International Conference on Software Architecture (ICSA). (5 pages, New and Emerging Ideas Track.)</li>
<li><span class="author-highlight">Yunbo Lyu</span>, Thanh Le-Cong, Hong Jin Kang, Ratnadira Widyasari, Zhipeng Zhao, Xuan-Bach D. Le, Ming Li, David Lo. <span class="paper-title">"CHRONOS: Time-Aware Zero-Shot Identification of Libraries from Vulnerability Reports"</span> 2023 IEEE/ACM 45th International Conference on Software Engineering (ICSE). (12 pages, Technical Track.)</li>
</ul>

## Journal Article
<ul class="journal-articles">
<li><span class="author-highlight">Yunbo Lyu</span>, Hong Jin Kang, Ratnadira Widyasari, Julia Lawall, David Lo. <span class="paper-title">"Evaluating SZZ Implementations: An Empirical Study on the Linux Kernel"</span> IEEE Transactions on Software Engineering, FSE 2025 Journal-First</li>
</ul>

## Preprints
<ul class="preprints">
<li>Zhou Yang, Zhensu Sun, <span class="author-highlight">Yunbo Lyu</span>, Terry Zhuo Yue, Premkumar Devanbu, David Lo. <span class="paper-title">Robustness, security, privacy, explainability, efficiency, and usability of large language models for code.</span></li>
<li>Hong Jin Kang, <span class="author-highlight">Yunbo Lyu</span>, Pattarakrit Rattanukul, Stefanus Agus Haryono, Truong Giang Nguyen, Chaiyong Ragkhitwetsagul, Corina Pasareanu, David Lo. <span class="paper-title">"Active Learning-based Input Selection for Fuzzing Deep Learning Libraries"</span> (This work found vulnerabilities leading to the assignment of 23 CVEs)</li>
<li>Xin Zhou, Martin Weyssow, Ratnadira Widyasari, Ting Zhang, Junda He, <span class="author-highlight">Yunbo Lyu</span>, Jianming Chang, Beiqi Zhang, Dan Huang, David Lo. <span class="paper-title">"LessLeak-Bench: A First Investigation of Data Leakage in LLMs Across 83 Software Engineering Benchmarks."</span> (Under review at TOSEM.)</li>
</ul>