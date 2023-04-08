---
title: CHRONOS Time-Aware Zero-Shot Identification of Libraries from Vulnerability Reports
date: 2022-12-09 08:51:00 +0800
categories: [publication, '2023']
tags: [zero-shot learning, library identification, unseen labels, extreme multi-label classification, vulnerability reports, ICSE 2023]     # TAG names should always be lowercase
---
# Abstract
Tools that alert developers about library vulnerabilities depend on accurate, up-to-date vulnerability databases which are maintained by security researchers. These databases record the libraries related to each vulnerability. However, the vulnerability reports may not explicitly list every library and human analysis is required to determine all the relevant libraries. Human analysis may be slow and expensive, which motivates the need for automated approaches. Researchers and practitioners have proposed to automatically identify libraries from vulnerability reports using extreme multi-label learning (XML).

While state-of-the-art XML techniques showed promising performance, their experiment settings do not practically fit what happens in reality. Previous studies randomly split the vulnerability reports data for training and testing their models without considering the chronological order of the reports. This may unduly train the models on chronologically newer reports while testing the models on chronologically older ones. However, in practice, one often receives chronologically new reports, which may be related to previously unseen libraries. Under this practical setting, we observe that the performance of current XML techniques declines substantially, e.g., F1 decreased from 0.7 to 0.24 under experiments without and with consideration of chronological order of vulnerability reports.

We propose a practical library identification approach, namely CHRONOS, based on zero-shot learning. The novelty of CHRONOS is three-fold. First, CHRONOS fits into the practical pipeline by considering the chronological order of vulnerability reports. Second, CHRONOS enriches the data of the vulnerability descriptions and labels using a carefully designed data enhancement step. Third, CHRONOS exploits the temporal ordering of the vulnerability reports using a cache to prioritize prediction of...
