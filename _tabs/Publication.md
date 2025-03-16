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
</style>

## Conference Papers
<ul class="conference-papers">
<li>Alessio Bucaioni, Martin Weyssow, Junda He, **<u>Yunbo Lyu</u>**, David Lo. *"A Functional Software Reference Architecture for LLM-Integrated Systems"* 2025 IEEE 22nd International Conference on Software Architecture (ICSA). (5 pages, New and Emerging Ideas Track.)</li>
<li>**<u>Yunbo Lyu</u>**, Thanh Le-Cong, Hong Jin Kang, Ratnadira Widyasari, Zhipeng Zhao, Xuan-Bach D. Le, Ming Li, David Lo. *"CHRONOS: Time-Aware Zero-Shot Identification of Libraries from Vulnerability Reports"* 2023 IEEE/ACM 45th International Conference on Software Engineering (ICSE). (12 pages, Technical Track.)</li>
</ul>

## Journal Article
<ul class="journal-articles">
<li>**<u>Yunbo Lyu</u>**, Hong Jin Kang, Ratnadira Widyasari, Julia Lawall, David Lo. *"Evaluating SZZ Implementations: An Empirical Study on the Linux Kernel"* IEEE Transactions on Software Engineering</li>
</ul>

## Preprints
<ul class="preprints">
<li>**<u>Yunbo Lyu</u>**, Zhou Yang, Yuqing Niu, Jing Jiang, David Lo. *"Do Existing Testing Tools Really Uncover Gender Bias in Text-to-Image Models?"*</li>
<li>Zhou Yang, Zhensu Sun, **<u>Yunbo Lyu</u>**, Terry Zhuo Yue, Premkumar Devanbu, David Lo. *Robustness, security, privacy, explainability, efficiency, and usability of large language models for code.*</li>
<li>Hong Jin Kang, **<u>Yunbo Lyu</u>**, Pattarakrit Rattanukul, Stefanus Agus Haryono, Truong Giang Nguyen, Chaiyong Ragkhitwetsagul, Corina Pasareanu, David Lo. *"Active Learning-based Input Selection for Fuzzing Deep Learning Libraries"* (This work found vulnerabilities leading to the assignment of 23 CVEs)</li>
<li>Chengran Yang, Jiakun Liu, Bowen Xu, Christoph Treude, **<u>Yunbo Lyu</u>**, Junda He, Ming Li, David Lo. *"APIDocBooster: An Extract-Then-Abstract Framework Leveraging Large Language Models for Augmenting API Documentation"* (Under review at ICSME.)</li>
<li>Xin Zhou, Martin Weyssow, Ratnadira Widyasari, Ting Zhang, Junda He, **<u>Yunbo Lyu</u>**, Jianming Chang, Beiqi Zhang, Dan Huang, David Lo. *"LessLeak-Bench: A First Investigation of Data Leakage in LLMs Across 83 Software Engineering Benchmarks."* (Under review at TOSEM.)</li>
</ul>


<!-- ## Conference Paper
[1] Alessio Bucaioni, Martin Weyssow, Junda He, **<u>Yunbo Lyu</u>**, David Lo. <em>"A Functional Software Reference Architecture for LLM-Integrated Systems"</em> 2025 IEEE 22nd International Conference on Software Architecture (ICSA). (5 pages, New and Emerging Ideas Track.)

**<u>Yunbo Lyu</u>**, Thanh Le-Cong, Hong Jin Kang, Ratnadira Widyasari, Zhipeng Zhao, Xuan-Bach D. Le, Ming Li, David Lo. <em>"CHRONOS: Time-Aware Zero-Shot Identification of Libraries from Vulnerability Reports"</em> 2023 IEEE/ACM 45th International Conference on Software Engineering (ICSE). (12 pages, Technical Track.)

## Journal Article
**<u>Yunbo Lyu</u>**, Hong Jin Kang, Ratnadira Widyasari, Julia Lawall, David Lo. <em>"Evaluating SZZ Implementations: An Empirical Study on the Linux Kernel" </em> IEEE Transactions on Software Engineering 

## Preprints
**<u>Yunbo Lyu</u>**, Zhou Yang, Yuqing Niu, Jing Jiang, David Lo. <em>"Do Existing Testing Tools Really Uncover Gender Bias in Text-to-Image Models?"</em>

Zhou Yang, Zhensu Sun, **<u>Yunbo Lyu</u>**, Terry Zhuo Yue, Premkumar Devanbu, David Lo. <em>Robustness, security, privacy, explainability, efficiency, and usability of large language models for code.</em>

Hong Jin Kang, **<u>Yunbo Lyu</u>**, Pattarakrit Rattanukul, Stefanus Agus Haryono, Truong Giang Nguyen, Chaiyong Ragkhitwetsagul, Corina Pasareanu, David Lo. <em>"Active Learning-based Input Selection for Fuzzing Deep Learning Libraries"</em> (This work found vulnerabilities leading to the assignment of 23 CVEs)

Chengran Yang, Jiakun Liu, Bowen Xu, Christoph Treude, **<u>Yunbo Lyu</u>**, Junda He, Ming Li, David Lo. <em>"APIDocBooster: An Extract-Then-Abstract Framework Leveraging Large Language Models for Augmenting API Documentation"</em> (Under review at ICSME.)

Xin Zhou, Martin Weyssow, Ratnadira Widyasari, Ting Zhang, Junda He, **<u>Yunbo Lyu</u>**, Jianming Chang, Beiqi Zhang, Dan Huang, David Lo. <em>"LessLeak-Bench: A First Investigation of Data Leakage in LLMs Across 83 Software Engineering Benchmarks."</em> (Under review at TOSEM.) -->