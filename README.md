# A field guide to phishing research

A reading collection for people beginning research on phishing attacks and detection. Start with a question below, or browse the bibliography by topic.

## Suggested reading paths

### How do phishing sites persuade people?

Read the original user study, then compare its findings with the longer review of how phishing experiments are designed.

[Why phishing works](https://doi.org/10.1145/1124772.1124861) → [Sixteen Years of Phishing User Studies: What Have We Learned?](https://doi.org/10.1109/tdsc.2022.3151103)

### What can a detector see?

Compare page content, URL characters, visual similarity and page interaction. For each paper, write down the minimum input needed for one prediction.

[Cantina: a content-based approach to detecting phishing web sites](https://doi.org/10.1145/1242572.1242659) → [URLNet: Learning a URL Representation with Deep Learning for Malicious URL Detection](https://arxiv.org/abs/1802.03162) → [VisualPhishNet: Zero-Day Phishing Website Detection by Visual Similarity](https://doi.org/10.1145/3372297.3417233) → [Inferring Phishing Intention via Webpage Appearance and Dynamics: A Deep Vision Based Approach](https://www.usenix.org/conference/usenixsecurity22/presentation/liu-ruofan)

### How should I evaluate a detector?

Trace when labels become available, how test examples are selected and how performance changes under different conditions.

[An Analysis of Phishing Blacklists: Google Safe Browsing, OpenPhish, and PhishTank](https://doi.org/10.1145/3373017.3373020) → [Towards benchmark datasets for machine learning based website phishing detection: An experimental study](https://doi.org/10.1016/j.engappai.2021.104347) → [Evaluating the Effectiveness and Robustness of Visual Similarity-based Phishing Detection Models](https://scholar.google.com/scholar?q=Evaluating%20the%20Effectiveness%20and%20Robustness%20of%20Visual%20Similarity-based%20Phishing%20Detection%20Models)

### Where do LLMs enter the decision?

Compare a site-level verdict with brand knowledge and email analysis. Which evidence can a reader independently check?

[Detecting Phishing Sites Using ChatGPT](https://doi.org/10.48550/arxiv.2306.05816) → [KnowPhish: Large Language Models Meet Multimodal Knowledge Graphs for Enhancing Reference-Based Phishing Detection](https://www.usenix.org/conference/usenixsecurity24/presentation/li-yuexin) → [MultiPhishGuard: An LLM-based Multi-Agent System for Phishing Email Detection](https://doi.org/10.48550/arxiv.2505.23803)

## Browse the bibliography

[Surveys and field guides](#surveys-and-field-guides) · [Datasets, feeds and benchmarks](#datasets-feeds-and-benchmarks) · [Attack measurement and robustness](#attack-measurement-and-robustness) · [People, warnings and authentication](#people-warnings-and-authentication) · [Email, SMS and social engineering](#email-sms-and-social-engineering) · [LLMs and multimodal reasoning](#llms-and-multimodal-reasoning) · [Blocklists, allowlists and reputation](#blocklists-allowlists-and-reputation) · [Visual identity and reference matching](#visual-identity-and-reference-matching) · [URLs, domains and lexical features](#urls-domains-and-lexical-features) · [Website content and classification](#website-content-and-classification)

178 distinct entries from the Zotero collection. Each entry appears under its first matching topic here. The searchable edition supports overlapping topics. Dates and venues follow the export. Entries without a source URL link to a title search.

## Surveys and field guides

Start here for terminology, threat models and comparisons across detection methods.

- [Phishing Detection: A Literature Survey](https://doi.org/10.1109/surv.2013.032213.00009) — 2013, IEEE Communications Surveys & Tutorials

- [Malicious URL Detection using Machine Learning: A Survey](https://arxiv.org/abs/1701.07179) — 2017, arXiv preprint arXiv:1701.07179

- [A recent review of conventional vs. automated cybersecurity anti-phishing techniques](https://doi.org/10.1016/j.cosrev.2018.05.003) — 2018, Computer Science Review

- [A survey of phishing attacks: Their types, vectors and technical approaches](https://doi.org/10.1016/j.eswa.2018.03.050) — 2018, Expert Systems with Applications

- [Review: Phishing Detection Approaches](https://doi.org/10.1109/ictcs.2019.8923069) — 2019, 2019 2nd International Conference on new Trends in Computing Sciences (ICTCS)

- [Heuristic-based strategy for Phishing prediction: A survey of URL-based approach](https://doi.org/10.1016/j.cose.2019.101613) — 2020, Computers & Security

- [SoK: A Comprehensive Reexamination of Phishing Research From the Security Perspective](https://doi.org/10.1109/comst.2019.2957750) — 2020, IEEE Communications Surveys & Tutorials

- [A survey of phishing attack techniques, defence mechanisms and open research challenges](https://doi.org/10.1080/17517575.2021.1896786) — 2022, Enterprise Information Systems

- [Applications of deep learning for phishing detection: a systematic literature review](https://doi.org/10.1007/s10115-022-01672-x) — 2022, Knowledge and Information Systems

- [A systematic literature review on phishing website detection techniques](https://doi.org/10.1016/j.jksuci.2023.01.004) — 2023, Journal of King Saud University - Computer and Information Sciences

- [Sixteen Years of Phishing User Studies: What Have We Learned?](https://doi.org/10.1109/tdsc.2022.3151103) — 2023, IEEE Transactions on Dependable and Secure Computing

- [SoK: PHILTER: Uncovering Security and Functional Gaps in AI-based Phishing Website Detection Literature via an LLM-based Reasoning Framework | USENIX](https://www.usenix.org/conference/usenixsecurity26/presentation/alam)

## Datasets, feeds and benchmarks

Check how examples were collected, labelled and split. A phishing feed records observed attacks, while an evaluation dataset also needs a sampling protocol.

- [Building Standard Offline Anti-phishing Dataset for Benchmarking](https://doi.org/10.14419/ijet.v7i4.31.23333) — 2018, International Journal of Engineering & Technology

- [Phishing Dataset for Machine Learning: Feature Evaluation](https://doi.org/10.17632/h3cgnj8hft.1) — 2018

- [A Feature Selection Comparative Study for Web Phishing Datasets](https://doi.org/10.1109/conecct50063.2020.9198349) — 2020, 2020 IEEE International Conference on Electronics, Computing and Communication Technologies (CONECCT)

- [PhishBench 2.0: A Versatile and Extendable Benchmarking Framework for Phishing](https://doi.org/10.1145/3372297.3420017) — 2020, Proceedings of the 2020 ACM SIGSAC Conference on Computer and Communications Security

- [Towards benchmark datasets for machine learning based website phishing detection: An experimental study](https://doi.org/10.1016/j.engappai.2021.104347) — 2021, Engineering Applications of Artificial Intelligence

- [Kaspersky's 2022 spam and phishing report](https://securelist.com/spam-phishing-scam-report-2022/108692/) — 2023

- [Wangjing1551/Logo-2k-plus-Dataset](https://github.com/Wangjing1551/Logo-2k-plus-Dataset) — 2024

- [2025 IC3 Annual Report](https://www.ic3.gov/AnnualReport/Reports/2025_IC3Report.pdf) — 2026

- [Phishing Activity Trends Report: 1st Quarter 2026](https://apwg.org/trendreports) — 2026

- [lindsey98/PhishingBaseline](https://github.com/lindsey98/PhishingBaseline) — 2026

- [2023 State of the Phish](https://scholar.google.com/scholar?q=2023%20State%20of%20the%20Phish)

- [APWG](https://apwg.org/trendreports?utm_source=chatgpt.com)

- [OpenPhish - Phishing Intelligence](https://www.openphish.com/)

- [PhishStorm - phishing / legitimate URL dataset](https://research.aalto.fi/en/datasets/phishstorm-phishing-legitimate-url-dataset) — Aalto University's research portal

- [PhishTank | Join the fight against phishing](https://phishtank.org/)

- [Q4 2022 Malware and Phishing Report: Phishing Volumes Increase 36% QoQ](https://www.vadesecure.com/en/blog/q4-2022-phishing-and-malware-report)

## Attack measurement and robustness

Compare the assumed attacker capabilities, the evidence evaluated and whether a study measures effects on users or on detectors.

- [Cracking Classifiers for Evasion: A Case Study on the Google's Phishing Pages Filter](https://doi.org/10.1145/2872427.2883060) — 2016, Proceedings of the 25th International Conference on World Wide Web

- [PhishFarm: A Scalable Framework for Measuring the Effectiveness of Evasion Techniques against Browser Phishing Blacklists](https://doi.org/10.1109/sp.2019.00049) — 2019, 2019 IEEE Symposium on Security and Privacy (SP)

- [Towards Adversarial Phishing Detection](https://www.usenix.org/conference/cset20/presentation/panum) — 2020

- [PDGAN: Phishing Detection With Generative Adversarial Networks](https://doi.org/10.1109/access.2022.3168235) — 2022, IEEE Access

- [PhishInPatterns: measuring elicited user interactions at scale on phishing websites](https://doi.org/10.1145/3517745.3561467) — 2022, Proceedings of the 22nd ACM Internet Measurement Conference

- [Reliability and Robustness analysis of Machine Learning based Phishing URL Detectors](https://doi.org/10.1109/tdsc.2022.3218043) — 2022, IEEE Transactions on Dependable and Secure Computing

- [Semi-supervised Conditional GAN for Simultaneous Generation and Detection of Phishing URLs: A Game theoretic Perspective](https://doi.org/10.48550/arxiv.2108.01852) — 2022

- [SpacePhish: The Evasion-space of Adversarial Attacks against Phishing Website Detectors using Machine Learning](https://doi.org/10.1145/3564625.3567980) — 2022, Proceedings of the 38th Annual Computer Security Applications Conference

- [Targeted Phishing Campaigns using Large Scale Language Models](http://arxiv.org/abs/2301.00665) — 2022

- [Devising and Detecting Phishing: Large Language Models vs. Smaller Human Models](http://arxiv.org/abs/2308.12287) — 2023

- [Evading Anti-Phishing Models: A Field Note Documenting an Experience in the Machine Learning Security Evasion Competition 2022](https://doi.org/10.1145/3603507) — 2023, Digital Threats: Research and Practice

- [Generating Personalized Phishing Emails for Social Engineering Training Based on Neural Language Models](https://doi.org/10.1007/978-3-031-20029-8_26) — 2023, Advances on Broad-Band Wireless Computing, Communication and Applications

- [Mitigating Adversarial Gray-Box Attacks Against Phishing Detectors](https://doi.org/10.1109/tdsc.2022.3210029) — 2023, IEEE Transactions on Dependable and Secure Computing

- [Raze to the Ground: Query-Efficient Adversarial HTML Attacks on Machine-Learning Phishing Webpage Detectors](https://doi.org/10.1145/3605764.3623920) — 2023, Proceedings of the 16th ACM Workshop on Artificial Intelligence and Security

- [Spear Phishing With Large Language Models](https://doi.org/10.48550/arxiv.2305.06972) — 2023

- ["Are Adversarial Phishing Webpages a Threat in Reality?" Understanding the Users' Perception of Adversarial Webpages](https://doi.org/10.1145/3589334.3645502) — 2024, Proceedings of the ACM Web Conference 2024

- [Attacking Logo-Based Phishing Website Detectors with Adversarial Perturbations](https://doi.org/10.1007/978-3-031-51479-1_9) — 2024, Computer Security – ESORICS 2023

- [Beneath the Phishing Scripts: A Script-Level Analysis of Phishing Kits and Their Impact on Real-World Phishing Websites](https://doi.org/10.1145/3634737.3657013) — 2024, Proceedings of the 19th ACM Asia Conference on Computer and Communications Security

- [Devising and Detecting Phishing Emails Using Large Language Models](https://doi.org/10.1109/access.2024.3375882) — 2024, IEEE Access

- [Fishing for Fraudsters: Uncovering Ethereum Phishing Gangs With Blockchain Data](https://doi.org/10.1109/tifs.2024.3359000) — 2024, IEEE Transactions on Information Forensics and Security

- [It Doesn’t Look Like Anything to Me: Using Diffusion Model to Subvert Visual Phishing Detectors](https://scholar.google.com/scholar?q=It%20Doesn%E2%80%99t%20Look%20Like%20Anything%20to%20Me%3A%20Using%20Diffusion%20Model%20to%20Subvert%20Visual%20Phishing%20Detectors) — 2024, USENIX2024

- [PhishinWebView: Analysis of Anti-Phishing Entities in Mobile Apps with WebView Targeted Phishing](https://doi.org/10.1145/3589334.3645708) — 2024, Proceedings of the ACM on Web Conference 2024

- [Evaluating the Effectiveness and Robustness of Visual Similarity-based Phishing Detection Models](https://scholar.google.com/scholar?q=Evaluating%20the%20Effectiveness%20and%20Robustness%20of%20Visual%20Similarity-based%20Phishing%20Detection%20Models) — 2025

- [Exposing the Roots of DNS Abuse: A Data-Driven Analysis of Key Factors Behind Phishing Domain Registrations](https://doi.org/10.1145/3719027.3744869) — 2025, Proceedings of the 2025 ACM SIGSAC Conference on Computer and Communications Security

- [From ML to LLM: Evaluating the Robustness of Phishing Web Page Detection Models against Adversarial Attacks](https://doi.org/10.1145/3737295) — 2025, Digital Threats: Research and Practice

- [CtPhishCapture: Uncovering Credential-Theft-Based Phishing Scams Targeting Cryptocurrency Wallets](https://www.ndss-symposium.org/ndss-paper/ctphishcapture-uncovering-credential-theft-based-phishing-scams-targeting-cryptocurrency-wallets/) — NDSS Symposium

- [Phishing in Wonderland: Evaluating Learning-Based Ethereum Phishing Transaction Detection and Pitfalls](https://www.ndss-symposium.org/ndss-paper/phishing-in-wonderland-evaluating-learning-based-ethereum-phishing-transaction-detection-and-pitfalls/) — NDSS Symposium

## People, warnings and authentication

Ask who makes the final decision and how the study measures comprehension, behaviour or susceptibility.

- [The battle against phishing: Dynamic Security Skins](https://doi.org/10.1145/1073001.1073009) — 2005, Proceedings of the 2005 symposium on Usable privacy and security

- [ViWiD : Visible Watermarking Based Defense Against Phishing](https://doi.org/10.1007/11551492_36) — 2005, Digital Watermarking

- [Do security toolbars actually prevent phishing attacks?](https://doi.org/10.1145/1124772.1124863) — 2006, Proceedings of the SIGCHI Conference on Human Factors in Computing Systems

- [Why phishing works](https://doi.org/10.1145/1124772.1124861) — 2006, Proceedings of the SIGCHI Conference on Human Factors in Computing Systems

- [You've been warned: an empirical study of the effectiveness of web browser phishing warnings](https://doi.org/10.1145/1357054.1357219) — 2008, Proceedings of the SIGCHI Conference on Human Factors in Computing Systems

- [A Multi-Modal Neuro-Physiological Study of Phishing Detection and Malware Warnings](https://doi.org/10.1145/2810103.2813660) — 2015, Proceedings of the 22nd ACM SIGSAC Conference on Computer and Communications Security

- [Preventing phishing attacks using text and image watermarking](https://doi.org/10.1002/cpe.5083) — 2019, Concurrency and Computation: Practice and Experience

- [The Phishing Funnel Model: A Design Artifact to Predict User Susceptibility to Phishing Websites](https://doi.org/10.1287/isre.2020.0973) — 2021, Information Systems Research

- [Real-Time, Evidence-Based Alerts for Protection from Phishing Attacks](https://doi.org/10.1109/tdsc.2024.3425908) — 2024, IEEE Transactions on Dependable and Secure Computing

- [URL Inspection Tasks: Helping Users Detect Phishing Links in Emails](https://www.usenix.org/conference/usenixsecurity25/presentation/lain) — 2025

- [PHAD- A Phishing Avoidance and Detection Tool Using Invisible Digital Watermarking](https://scholar.google.com/scholar?q=PHAD-%20A%20Phishing%20Avoidance%20and%20Detection%20Tool%20Using%20Invisible%20Digital%20Watermarking)

- [Phinding Phish: An Evaluation of Anti-Phishing Toolbars](https://www.ndss-symposium.org/ndss2007/phinding-phish-evaluation-anti-phishing-toolbars/) — NDSS Symposium

- [Supporting the Design of Phishing Education, Training and Awareness interventions: an LLM-based approach](https://scholar.google.com/scholar?q=Supporting%20the%20Design%20of%20Phishing%20Education%2C%20Training%20and%20Awareness%20interventions%3A%20an%20LLM-based%20approach)

- [Two-level authentication approach to protect from phishing attacks in real time](https://link.springer.com/article/10.1007/s12652-017-0616-z)

## Email, SMS and social engineering

Follow the message from delivery to the requested action. Look for evidence from wording, sender identity and links.

- [Learning to detect phishing emails](https://doi.org/10.1145/1242572.1242660) — 2007, Proceedings of the 16th international conference on World Wide Web

- [LogoSENSE: A companion HOG based logo detection scheme for phishing web page and E-mail brand recognition](https://doi.org/10.1016/j.cose.2020.101855) — 2020, Computers & Security

- [Phishing Email Detection Using Persuasion Cues](https://doi.org/10.1109/tdsc.2021.3118931) — 2022, IEEE Transactions on Dependable and Secure Computing

- [Can You Walk Me Through It? Explainable SMS Phishing Detection using LLM-based Agents](https://www.usenix.org/conference/soups2025/presentation/wang) — 2025

- [MultiPhishGuard: An LLM-based Multi-Agent System for Phishing Email Detection](https://doi.org/10.48550/arxiv.2505.23803) — 2025, arXiv preprint arXiv:2505.23803

- [Paladin: Defending LLM-enabled Phishing Emails with a New Trigger-Tag Paradigm](https://doi.org/10.48550/arxiv.2509.07287) — 2025, NDSS Symposium

- [LMs go Phishing: Adapting Pre-trained Language Models to Detect Phishing Emails](https://ieeexplore.ieee.org/abstract/document/10101955?casa_token=5_6Rm8LdVc0AAAAA:XXCwPcDBXQ5QGHoEgju7DydUlRx-cgBiQx4p8bhh6FPNIPejF9m1caLJBTbhu_CgT3r8I0U)

## LLMs and multimodal reasoning

Compare the inputs each model sees and the evidence it gives for a verdict.

- [Detecting Phishing Sites Using ChatGPT](https://doi.org/10.48550/arxiv.2306.05816) — 2024

- [KnowPhish: Large Language Models Meet Multimodal Knowledge Graphs for Enhancing Reference-Based Phishing Detection](https://www.usenix.org/conference/usenixsecurity24/presentation/li-yuexin) — 2024, 33rd USENIX Security Symposium (USENIX Security 24)

- [PhishAgent: A Robust Multimodal Agent for Phishing Webpage Detection](https://doi.org/10.1609/aaai.v39i27.35003) — 2025, Proceedings of the AAAI Conference on Artificial Intelligence

- [PhishIntentionLLM: Uncovering Phishing Website Intentions through Multi-Agent Retrieval-Augmented Generation](https://arxiv.org/abs/2507.15419) — 2025, arXiv preprint arXiv:2507.15419

- [MemoPhishAgent: Memory-Augmented Multi-Modal LLM Agent for Phishing URL Detection](https://arxiv.org/abs/2602.21394) — 2026, arXiv preprint arXiv:2602.21394

## Blocklists, allowlists and reputation

Ask when an address first became known and how that timing affects coverage.

- [Anti-phishing based on automated individual white-list](https://doi.org/10.1145/1456424.1456434) — 2008, Proceedings of the 4th ACM workshop on Digital identity management

- [Beyond blacklists: learning to detect malicious web sites from suspicious URLs](https://doi.org/10.1145/1557019.1557153) — 2009, Proceedings of the 15th ACM SIGKDD international conference on Knowledge discovery and data mining

- [PhishNet: Predictive Blacklisting to Detect Phishing Attacks](https://doi.org/10.1109/infcom.2010.5462216) — 2010, 2010 Proceedings IEEE INFOCOM

- [Jail-Phish: An improved search engine based phishing detection system](https://doi.org/10.1016/j.cose.2019.02.011) — 2019, Computers & Security

- [An Analysis of Phishing Blacklists: Google Safe Browsing, OpenPhish, and PhishTank](https://doi.org/10.1145/3373017.3373020) — 2020, Proceedings of the Australasian Computer Science Week Multiconference

- [Adopting automated whitelist approach for detecting phishing attacks](https://doi.org/10.1016/j.cose.2021.102328) — 2021, Computers & Security

- [An Empirical Analysis of Phishing Blacklists](https://scholar.google.com/scholar?q=An%20Empirical%20Analysis%20of%20Phishing%20Blacklists)

- [An Enhanced Blacklist Method to Detect Phishing Websites](https://doi.org/10.1007/978-3-319-72598-7_20) — ResearchGate

## Visual identity and reference matching

Look at what is matched across pages, how the claimed brand is identified and how the domain is checked.

- [Detection of phishing webpages based on visual similarity](https://doi.org/10.1145/1062745.1062868) — 2005

- [An antiphishing strategy based on visual similarity assessment](https://doi.org/10.1109/mic.2006.23) — 2006, IEEE Internet Computing

- [Detecting Phishing Web Pages with Visual Similarity Assessment Based on Earth Mover's Distance (EMD)](https://doi.org/10.1109/tdsc.2006.50) — 2006, IEEE Transactions on Dependable and Secure Computing

- [A layout-similarity-based approach for detecting phishing pages](https://doi.org/10.1109/seccom.2007.4550367) — 2007, 2007 Third International Conference on Security and Privacy in Communications Networks and the Workshops - SecureComm 2007

- [Visual-Similarity-Based Phishing Detection](https://doi.org/10.1145/1460877.1460905) — 2008

- [Fighting Phishing with Discriminative Keypoint Features](https://doi.org/10.1109/mic.2009.59) — 2009, IEEE Internet Computing

- [GoldPhish: Using Images for Content-Based Phishing Analysis](https://doi.org/10.1109/icimp.2010.24) — 2010, 2010 Fifth International Conference on Internet Monitoring and Protection

- [Mitigate web phishing using site signatures](https://doi.org/10.1109/tencon.2010.5686582) — 2010, TENCON 2010 - 2010 IEEE Region 10 Conference

- [PhishZoo: Detecting Phishing Websites by Looking at Them](https://doi.org/10.1109/icsc.2011.52) — 2011, 2011 IEEE Fifth International Conference on Semantic Computing

- [Textual and Visual Content-Based Anti-Phishing: A Bayesian Approach](https://doi.org/10.1109/tnn.2011.2161999) — 2011, IEEE transactions on neural networks / a publication of the IEEE Neural Networks Council

- [BaitAlarm: Detecting Phishing Sites Using Similarity in Fundamental Visual Features](https://doi.org/10.1109/incos.2013.151) — 2013, 2013 5th International Conference on Intelligent Networking and Collaborative Systems

- [Phishing Detection via Identification of Website Identity](https://doi.org/10.1109/icitcs.2013.6717870) — 2013, 2013 International Conference on IT Convergence and Security (ICITCS)

- [Web phishing detection based on page spatial layout similarity](https://scholar.google.com/scholar?q=Web%20phishing%20detection%20based%20on%20page%20spatial%20layout%20similarity) — 2013, Informatica (Slovenia)

- [A Computer Vision Technique to Detect Phishing Attacks](https://doi.org/10.1109/csnt.2015.68) — 2015, 2015 Fifth International Conference on Communication Systems and Network Technologies

- [Utilisation of website logo for phishing detection](https://doi.org/10.1016/j.cose.2015.07.006) — 2015, Computers & Security

- [Phishing-Alarm: Robust and Efficient Phishing Detection via Page Component Similarity](https://doi.org/10.1109/access.2017.2743528) — 2017, IEEE Access

- [Visual Similarity-Based Phishing Detection Scheme Using Image and CSS with Target Website Finder](https://doi.org/10.1109/glocom.2017.8254506) — 2017, GLOBECOM 2017 - 2017 IEEE Global Communications Conference

- [Detecting Phishing Websites via Aggregation Analysis of Page Layouts](https://doi.org/10.1016/j.procs.2018.03.053) — 2018, Procedia Computer Science

- [Phish-IRIS: A New Approach for Vision Based Brand Prediction of Phishing Web Pages via Compact Visual Descriptors](https://doi.org/10.1109/ismsit.2018.8567299) — 2018, 2018 2nd International Symposium on Multidisciplinary Studies and Innovative Technologies (ISMSIT)

- [Phishing page detection via learning classifiers from page layout feature](https://doi.org/10.1186/s13638-019-1361-0) — 2019, EURASIP Journal on Wireless Communications and Networking

- [Cost-Effective OCR Implementation to Prevent Phishing on Mobile Platforms](https://doi.org/10.1109/cybersecurity49315.2020.9138873) — 2020, 2020 International Conference on Cyber Security and Protection of Digital Services (Cyber Security)

- [VisualPhishNet: Zero-Day Phishing Website Detection by Visual Similarity](https://doi.org/10.1145/3372297.3417233) — 2020, Proceedings of the 2020 ACM SIGSAC Conference on Computer and Communications Security

- [Combining Text and Visual Features to Improve the Identification of Cloned Webpages for Early Phishing Detection](https://doi.org/10.1145/3465481.3470112) — 2021, Proceedings of the 16th International Conference on Availability, Reliability and Security

- [Phishpedia: A Hybrid Deep Learning Based Approach to Visually Identify Phishing Webpages](https://www.usenix.org/conference/usenixsecurity21/presentation/lin) — 2021, 30th USENIX Security Symposium (USENIX Security 21)

- [Webpage visual feature extraction and similarity algorithm](https://doi.org/10.1145/3444370.3444552) — 2021, Proceedings of the 2020 International Conference on Cyberspace Innovation of Advanced Technologies

- [Inferring Phishing Intention via Webpage Appearance and Dynamics: A Deep Vision Based Approach](https://www.usenix.org/conference/usenixsecurity22/presentation/liu-ruofan) — 2022, 31st USENIX Security Symposium (USENIX Security 22)

- [Knowledge Expansion and Counterfactual Interaction for Reference-Based Phishing Detection](https://www.usenix.org/conference/usenixsecurity23/presentation/liu-ruofan) — 2022, 32nd USENIX Security Symposium (USENIX Security 23)

- [Phishing Attack Detection with ML-Based Siamese Empowered ORB Logo Recognition and IP Mapper](https://doi.org/10.1109/infocomwkshps54753.2022.9798203) — 2022, IEEE INFOCOM 2022 - IEEE Conference on Computer Communications Workshops (INFOCOM WKSHPS)

- [Hybrid phishing detection using joint visual and textual identity](https://doi.org/10.1016/j.eswa.2023.119723) — 2023, Expert Systems with Applications

- [Less Defined Knowledge and More True Alarms: Reference-based Phishing Detection without a Pre-defined Reference List](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-ruofan) — 2024, 33rd USENIX Security Symposium (USENIX Security 24)

- [PhishDecloaker: Detecting CAPTCHA-cloaked Phishing Websites via Hybrid Vision-based Interactive Models](https://www.usenix.org/conference/usenixsecurity24/presentation/teoh) — 2024

- [PhishIntel: Toward Practical Deployment of Reference-based Phishing Detection](https://doi.org/10.48550/arxiv.2412.09057) — 2024

- [Phishing Vs. Legit: Comparative Analysis of Client-Side Resources of Phishing and Target Brand Websites](https://doi.org/10.1145/3589334.3645535) — 2024, Proceedings of the ACM on Web Conference 2024

- [Phishing webpage detection based on global and local visual similarity](https://doi.org/10.1016/j.eswa.2024.124120) — 2024, Expert Systems with Applications

## URLs, domains and lexical features

Identify which signals can be computed from the address alone and which require external lookups or page content.

- [LEARNING TO DETECT PHISHING URLS](https://doi.org/10.15623/ijret.2014.0306003) — 2014, International Journal of Research in Engineering and Technology

- [PhishStorm: Detecting Phishing With Streaming Analytics](https://doi.org/10.1109/tnsm.2014.2377295) — 2014, IEEE Transactions on Network and Service Management

- [Detecting Homoglyph Attacks with a Siamese Neural Network](https://doi.org/10.1109/spw.2018.00012) — 2018, 2018 IEEE Security and Privacy Workshops (SPW)

- [URLNet: Learning a URL Representation with Deep Learning for Malicious URL Detection](https://arxiv.org/abs/1802.03162) — 2018, arXiv preprint arXiv:1802.03162

- [A stacking model using URL and HTML features for phishing webpage detection](https://doi.org/10.1016/j.future.2018.11.004) — 2019, Future Generation Computer Systems

- [Detecting Malicious URLs via a Keyword-Based Convolutional Gated-Recurrent-Unit Neural Network](https://doi.org/10.1109/access.2019.2895751) — 2019, IEEE Access

- [Machine learning based phishing detection from URLs](https://doi.org/10.1016/j.eswa.2018.09.029) — 2019, Expert Systems with Applications

- [Accurate and fast URL phishing detector: A convolutional neural network approach](https://doi.org/10.1016/j.comnet.2020.107275) — 2020, Computer Networks

- [A novel approach for phishing URLs detection using lexical based machine learning in a real-time environment](https://doi.org/10.1016/j.comcom.2021.04.023) — 2021, Computer Communications

- [Light gradient boosting machine-based phishing webpage detection model using phisher website features of mimic URLs](https://doi.org/10.1016/j.patrec.2021.09.018) — 2021, Pattern Recognition Letters

- [URLTran: Improving Phishing URL Detection Using Transformers](https://doi.org/10.1109/milcom52596.2021.9653028) — 2021, MILCOM 2021 - 2021 IEEE Military Communications Conference (MILCOM)

- [An effective detection approach for phishing websites using URL and HTML features](https://doi.org/10.1038/s41598-022-10841-5) — 2022, Scientific Reports

- [Intelligent Deep Machine Learning Cyber Phishing URL Detection Based on BERT Features Extraction](https://doi.org/10.3390/electronics11223647) — 2022, Electronics

- [Robust Detection of Malicious URLs With Self-Paced Wide & Deep Learning](https://doi.org/10.1109/tdsc.2021.3121388) — 2022, IEEE Transactions on Dependable and Secure Computing

- [A Large-Scale Pretrained Deep Model for Phishing URL Detection](https://doi.org/10.1109/icassp49357.2023.10095719) — 2023, ICASSP 2023 - 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)

- [Automated phishing detection using urls and webpages](https://scholar.google.com/scholar?q=Automated%20phishing%20detection%20using%20urls%20and%20webpages) — 2024, arXiv preprint arXiv:2408.01667

- [Look before you leap: Detecting phishing web pages by exploiting raw URL and HTML characteristics](https://doi.org/10.1016/j.eswa.2023.121183) — 2024, Expert Systems with Applications

- [Toward More Generalized Malicious URL Detection Models](https://doi.org/10.1609/aaai.v38i19.30161) — 2024, Proceedings of the AAAI Conference on Artificial Intelligence

## Website content and classification

Compare the evidence available to each detector, including HTML, page behaviour and engineered features.

- [A comparison of machine learning techniques for phishing detection](https://doi.org/10.1145/1299015.1299021) — 2007, Proceedings of the anti-phishing working groups 2nd annual eCrime researchers summit

- [Cantina: a content-based approach to detecting phishing web sites](https://doi.org/10.1145/1242572.1242659) — 2007, Proceedings of the 16th international conference on World Wide Web

- [A new fast associative classification algorithm for detecting phishing websites](https://doi.org/10.1016/j.asoc.2016.08.005) — 2016, Applied Soft Computing

- [DeltaPhish: Detecting Phishing Webpages in Compromised Websites](https://doi.org/10.1007/978-3-319-66402-6_22) — 2017, Computer Security – ESORICS 2017

- [Towards detection of phishing websites on client-side using machine learning based approach](https://doi.org/10.1007/s11235-017-0414-0) — 2018, Telecommunication Systems

- [Web Phishing Detection Using a Deep Learning Framework](https://doi.org/10.1155/2018/4678746) — 2018, Wireless Communications and Mobile Computing

- [A Deep-Learning-Driven Light-Weight Phishing Detection Sensor](https://doi.org/10.3390/s19194258) — 2019, Sensors

- [A new hybrid ensemble feature selection framework for machine learning-based phishing detection system](https://doi.org/10.1016/j.ins.2019.01.064) — 2019, Information Sciences

- [Deep Learning with Convolutional Neural Network and Long Short-Term Memory for Phishing Detection](https://doi.org/10.1109/skima47702.2019.8982427) — 2019, 2019 13th International Conference on Software, Knowledge, Information Management and Applications (SKIMA)

- [Detection of phishing websites using an efficient feature-based machine learning framework](https://doi.org/10.1007/s00521-017-3305-0) — 2019, Neural Computing and Applications

- [Phishing Website Detection Based on Multidimensional Features Driven by Deep Learning](https://doi.org/10.1109/access.2019.2892066) — 2019, IEEE Access

- [CNN–MHSA: A Convolutional Neural Network and multi-head self-attention combined approach for detecting phishing websites](https://doi.org/10.1016/j.neunet.2020.02.013) — 2020, Neural Networks

- [DTOF-ANN: An Artificial Neural Network phishing detection model based on Decision Tree and Optimal Features](https://doi.org/10.1016/j.asoc.2020.106505) — 2020, Applied Soft Computing

- [Development of anti-phishing browser based on random forest and rule of extraction framework](https://doi.org/10.1186/s42400-020-00059-1) — 2020, Cybersecurity

- [High Accuracy Phishing Detection Based on Convolutional Neural Networks](https://doi.org/10.1109/iccais48893.2020.9096869) — 2020, 2020 3rd International Conference on Computer Applications & Information Security (ICCAIS)

- [Machine Learning-Based Phishing Attack Detection](https://doi.org/10.14569/ijacsa.2020.0110945) — 2020, International Journal of Advanced Computer Science and Applications

- [PhiDMA – A phishing detection model with multi-filter approach](https://doi.org/10.1016/j.jksuci.2017.07.005) — 2020, Journal of King Saud University - Computer and Information Sciences

- [Phishing Web Page Detection Using Optimised Machine Learning](https://doi.org/10.1109/trustcom50675.2020.00072) — 2020, 2020 IEEE 19th International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom)

- [A heuristic technique to detect phishing websites using TWSVM classifier](https://doi.org/10.1007/s00521-020-05354-z) — 2021, Neural Computing and Applications

- [An improved ELM-based and data preprocessing integrated approach for phishing detection considering comprehensive features](https://doi.org/10.1016/j.eswa.2020.113863) — 2021, Expert Systems with Applications

- [Intelligent cyber-phishing detection for online](https://doi.org/10.1016/j.cose.2020.102123) — 2021, Computers & Security

- [Similarity measure fuzzy soft set for phishing detection](https://doi.org/10.26555/ijain.v7i1.605) — 2021, International Journal of Advances in Intelligent Informatics

- [A Deep Learning-Based Framework for Phishing Website Detection](https://doi.org/10.1109/access.2021.3137636) — 2022, IEEE Access

- [An Efficient Phishing Attack Detection using Machine Learning Algorithms](https://doi.org/10.1109/assic55218.2022.10088399) — 2022, 2022 International Conference on Advancements in Smart, Secure and Intelligent Computing (ASSIC)

- [MOE/RF: A Novel Phishing Detection Model Based on Revised Multiobjective Evolution Optimization Algorithm and Random Forest](https://doi.org/10.1109/tnsm.2022.3162885) — 2022, IEEE Transactions on Network and Service Management

- [Modeling Hybrid Feature-Based Phishing Websites Detection Using Machine Learning Techniques](https://doi.org/10.1007/s40745-022-00379-8) — 2022, Annals of Data Science

- [Phishing Website Detection With Semantic Features Based on Machine Learning Classifiers](https://doi.org/10.4018/ijswis.297032) — 2022, International Journal on Semantic Web and Information Systems

- [A Good Fishman Knows All the Angles: A Critical Evaluation of Google's Phishing Page Classifier](https://doi.org/10.1145/3576915.3623199) — 2023, Proceedings of the 2023 ACM SIGSAC Conference on Computer and Communications Security

- [CCBLA: a Lightweight Phishing Detection Model Based on CNN, BiLSTM, and Attention Mechanism](https://doi.org/10.1007/s12559-022-10024-4) — 2023, Cognitive Computation

- [Metaheuristics with deep learning driven phishing detection for sustainable and secure environment](https://doi.org/10.1016/j.seta.2023.103114) — 2023, Sustainable Energy Technologies and Assessments

- [Detecting Malicious Websites From the Perspective of System Provenance Analysis](https://doi.org/10.1109/tdsc.2023.3277613) — 2024, IEEE Transactions on Dependable and Secure Computing

- [PDHF: Effective phishing detection model combining optimal artificial and automatic deep features](https://doi.org/10.1016/j.cose.2023.103561) — 2024, Computers & Security

- [A Phishing Website Detection System Based on Hybrid Feature Engineering with SHAP Explainable Artificial Intelligence Technique](https://doi.org/10.1007/978-981-96-1483-7_1) — 2025, Web Information Systems Engineering – WISE 2024 PhD Symposium, Demos and Workshops

- [Feature Selection for Improved Phishing Detection](https://link.springer.com/chapter/10.1007/978-3-642-31087-4_27)

- [Large-Scale Automatic Classification of Phishing Pages](https://www.ndss-symposium.org/ndss2010/large-scale-automatic-classification-phishing-pages/) — NDSS Symposium

- [PhishLang: A Real-Time, Fully Client-Side Phishing Detection Framework Using MobileBERT](https://www.ndss-symposium.org/ndss-paper/phishlang-a-real-time-fully-client-side-phishing-detection-framework-using-mobilebert/) — NDSS Symposium

- [Phishing-Aware: A Neuro-Fuzzy Approach for Anti-Phishing on Fog Networks](https://ieeexplore.ieee.org/document/8352739)
