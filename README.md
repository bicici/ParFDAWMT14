ParFDAWMT
==========

Parallel FDA5 (ParFDA) WMT'14 Datasets

We make the English, Czech, German, and Russian datasets available used when building ParFDA Moses SMT systems for research purposes. Downloadable from:

https://drive.google.com/folderview?id=0B6Jae6trZb1aVzJvSnZ5UncxTEE&usp=sharing

Results are presented in the citation provided below.

Citation:

Ergun Biçici, Qun Liu, and Andy Way. Parallel FDA5 for Fast Deployment of Accurate Statistical Machine Translation Systems. In Proceedings of the Ninth Workshop on Statistical Machine Translation, Baltimore, USA, June 2014. Association for Computational Linguistics.


The datasets and the SMT results can serve as a benchmark for SMT research where further linguistic processing can be performed to see whether the results can be improved. The datasets allow fast deployment of accurate SMT systems and can be used for benchmarking the performance of SMT systems. 

Language models were built using SRILM (http://www.speech.sri.com/projects/srilm/). Language model corpora used contain 15M sentences some of which are selected from LDC Gigaword corpora by the Parallel FDA5 algorithm: 

[4 use the LDC English Gigaword 5th edition]
- Czech - English: 2.13 million sentences from LDC English Gigaword, ~1.69 %.
- French - English: 2.49 million sentences from LDC English Gigaword, ~1.97 %
- German - English: 2.57 million sentences from LDC English Gigaword, ~2.03 %
- Russian - English: 3.34 million sentences from LDC English Gigaword, ~2.64 %

[1 use the LDC French Gigaword 3rd edition]
- English - French: 0.47 million sentences from LDC French Gigaword, ~1.93 %


Work using the datasets:
------------------------
- Ergun Biçici and Lucia Specia. QuEst for High Quality Machine Translation. The Prague Bulletin of Mathematical Linguistics, 103, 2015.
- Ergun Biçici, Qun Liu, and Andy Way. Parallel FDA5 for Fast Deployment of Accurate Statistical Machine Translation Systems. In Proceedings of the Ninth Workshop on Statistical Machine Translation, Baltimore, USA, June 2014. Association for Computational Linguistics.
- Ergun Biçici (contributor), “Quality Estimation for Extending Good Translations”, QTLaunchPad Deliverable: 
http://www.qt21.eu/launchpad/deliverable/quality-estimation-extending-good-translations
- Ergun Biçici, High Quality Machine Translation with ITERPE, 2014. Note: Dublin City University Invention Disclosure.


LICENSE: Dublin City University License for Open Data allowing use for research and academic purposes.
