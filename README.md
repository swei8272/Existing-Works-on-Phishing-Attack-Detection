# 🎣 Phishing attacks and detection

Explore 178 papers, datasets and research resources on phishing. Browse by detection method, study how phishing affects people, or follow a guided reading path.

[Detection methods](#detection-methods) · [Attacks and human factors](#attacks-and-people) · [Surveys and resources](#surveys-and-resources) · [Reading paths](#suggested-reading-paths) · [Download searchable guide](<https://github.com/swei8272/Existing-Works-on-Phishing-Attack-Detection/raw/refs/heads/main/index.html>)

<a id="browse-the-bibliography"></a>

## 🗂️ Topic index

**Detection methods**  
[Blocklists, allowlists and reputation](<#blocklists-allowlists-and-reputation>) · [URLs, domains and lexical features](<#urls-domains-and-lexical-features>) · [Website content and classification](<#website-content-and-classification>) · [Visual identity and reference matching](<#visual-identity-and-reference-matching>) · [Email, SMS and social engineering](<#email-sms-and-social-engineering>) · [LLMs and multimodal reasoning](<#llms-and-multimodal-reasoning>)

**Attacks and human factors**  
[Attack measurement and robustness](<#attack-measurement-and-robustness>) · [People, warnings and authentication](<#people-warnings-and-authentication>)

**Surveys, datasets and benchmarks**  
[Surveys and field guides](<#surveys-and-field-guides>) · [Datasets, feeds and benchmarks](<#datasets-feeds-and-benchmarks>)

The first column names the system or describes the study focus. A title search opens a lookup for records that lack a direct source link.

<a id="detection-methods"></a>

## 🔎 Detection methods

<a id="blocklists-allowlists-and-reputation"></a>

### Blocklists, allowlists and reputation

Ask when an address first became known and how that timing affects coverage.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **Personal allowlist** | Anti-phishing based on automated individual white-list | Proceedings of the 4th ACM workshop on Digital identity management · 2008 | [Paper](<https://doi.org/10.1145/1456424.1456434>) |
| **PhishNet** | PhishNet: Predictive Blacklisting to Detect Phishing Attacks | 2010 Proceedings IEEE INFOCOM · 2010 | [Paper](<https://doi.org/10.1109/infcom.2010.5462216>) |
| **Jail-Phish** | Jail-Phish: An improved search engine based phishing detection system | Computers &amp; Security · 2019 | [Paper](<https://doi.org/10.1016/j.cose.2019.02.011>) |
| **Feed comparison** | An Analysis of Phishing Blacklists: Google Safe Browsing, OpenPhish, and PhishTank | Proceedings of the Australasian Computer Science Week Multiconference · 2020 | [Paper](<https://doi.org/10.1145/3373017.3373020>) |
| **Automated allowlist** | Adopting automated whitelist approach for detecting phishing attacks | Computers &amp; Security · 2021 | [Paper](<https://doi.org/10.1016/j.cose.2021.102328>) |
| **Blocklist measurement** | An Empirical Analysis of Phishing Blacklists | — | [Title search](<https://scholar.google.com/scholar?q=An%20Empirical%20Analysis%20of%20Phishing%20Blacklists>) |
| **Blocklist extension** | An Enhanced Blacklist Method to Detect Phishing Websites | ResearchGate | [Paper](<https://doi.org/10.1007/978-3-319-72598-7_20>) |

[↑ Topic index](#browse-the-bibliography)

<a id="urls-domains-and-lexical-features"></a>

### URLs, domains and lexical features

Identify which signals can be computed from the address alone and which require external lookups or page content.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **URL classification** | Beyond blacklists: learning to detect malicious web sites from suspicious URLs | Proceedings of the 15th ACM SIGKDD international conference on Knowledge discovery and data mining · 2009 | [Paper](<https://doi.org/10.1145/1557019.1557153>) |
| **URL classification** | LEARNING TO DETECT PHISHING URLS | International Journal of Research in Engineering and Technology · 2014 | [Paper](<https://doi.org/10.15623/ijret.2014.0306003>) |
| **PhishStorm** | PhishStorm: Detecting Phishing With Streaming Analytics | IEEE TNSM · 2014 | [Paper](<https://doi.org/10.1109/tnsm.2014.2377295>) |
| **Siamese network** | Detecting Homoglyph Attacks with a Siamese Neural Network | 2018 IEEE Security and Privacy Workshops (SPW) · 2018 | [Paper](<https://doi.org/10.1109/spw.2018.00012>) |
| **URLNet** | URLNet: Learning a URL Representation with Deep Learning for Malicious URL Detection | arXiv · 2018 | [Paper](<https://arxiv.org/abs/1802.03162>) · [Code](<https://github.com/Antimalweb/URLNet>) |
| **Stacked classifiers** | A stacking model using URL and HTML features for phishing webpage detection | Future Generation Computer Systems · 2019 | [Paper](<https://doi.org/10.1016/j.future.2018.11.004>) |
| **Keyword-based CNN–GRU** | Detecting Malicious URLs via a Keyword-Based Convolutional Gated-Recurrent-Unit Neural Network | IEEE Access · 2019 | [Paper](<https://doi.org/10.1109/access.2019.2895751>) |
| **URL classification** | Machine learning based phishing detection from URLs | Expert Systems with Applications · 2019 | [Paper](<https://doi.org/10.1016/j.eswa.2018.09.029>) |
| **URL-based CNN** | Accurate and fast URL phishing detector: A convolutional neural network approach | Computer Networks · 2020 | [Paper](<https://doi.org/10.1016/j.comnet.2020.107275>) |
| **Lexical features** | A novel approach for phishing URLs detection using lexical based machine learning in a real-time environment | Computer Communications · 2021 | [Paper](<https://doi.org/10.1016/j.comcom.2021.04.023>) |
| **Gradient boosting** | Light gradient boosting machine-based phishing webpage detection model using phisher website features of mimic URLs | Pattern Recognition Letters · 2021 | [Paper](<https://doi.org/10.1016/j.patrec.2021.09.018>) |
| **URLTran** | URLTran: Improving Phishing URL Detection Using Transformers | MILCOM 2021 - 2021 IEEE Military Communications Conference (MILCOM) · 2021 | [Paper](<https://doi.org/10.1109/milcom52596.2021.9653028>) |
| **URL and HTML** | An effective detection approach for phishing websites using URL and HTML features | Scientific Reports · 2022 | [Paper](<https://doi.org/10.1038/s41598-022-10841-5>) |
| **BERT features** | Intelligent Deep Machine Learning Cyber Phishing URL Detection Based on BERT Features Extraction | Electronics · 2022 | [Paper](<https://doi.org/10.3390/electronics11223647>) |
| **Wide &amp; deep learning** | Robust Detection of Malicious URLs With Self-Paced Wide &amp; Deep Learning | IEEE TDSC · 2022 | [Paper](<https://doi.org/10.1109/tdsc.2021.3121388>) |
| **URL pretraining** | A Large-Scale Pretrained Deep Model for Phishing URL Detection | ICASSP 2023 - 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) · 2023 | [Paper](<https://doi.org/10.1109/icassp49357.2023.10095719>) |
| **URL and webpage analysis** | Automated phishing detection using urls and webpages | arXiv · 2024 | [Title search](<https://scholar.google.com/scholar?q=Automated%20phishing%20detection%20using%20urls%20and%20webpages>) |
| **URL and HTML** | Look before you leap: Detecting phishing web pages by exploiting raw URL and HTML characteristics | Expert Systems with Applications · 2024 | [Paper](<https://doi.org/10.1016/j.eswa.2023.121183>) |
| **URL generalization** | Toward More Generalized Malicious URL Detection Models | AAAI · 2024 | [Paper](<https://doi.org/10.1609/aaai.v38i19.30161>) |

[↑ Topic index](#browse-the-bibliography)

<a id="website-content-and-classification"></a>

### Website content and classification

Compare the evidence available to each detector, including HTML, page behaviour and engineered features.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **Classifier comparison** | A comparison of machine learning techniques for phishing detection | Proceedings of the anti-phishing working groups 2nd annual eCrime researchers summit · 2007 | [Paper](<https://doi.org/10.1145/1299015.1299021>) |
| **CANTINA** | Cantina: a content-based approach to detecting phishing web sites | WWW · 2007 | [Paper](<https://doi.org/10.1145/1242572.1242659>) |
| **Associative classification** | A new fast associative classification algorithm for detecting phishing websites | Applied Soft Computing · 2016 | [Paper](<https://doi.org/10.1016/j.asoc.2016.08.005>) |
| **DeltaPhish** | DeltaPhish: Detecting Phishing Webpages in Compromised Websites | Computer Security – ESORICS 2017 · 2017 | [Paper](<https://doi.org/10.1007/978-3-319-66402-6_22>) |
| **Client-side detection** | Towards detection of phishing websites on client-side using machine learning based approach | Telecommunication Systems · 2018 | [Paper](<https://doi.org/10.1007/s11235-017-0414-0>) |
| **Deep learning** | Web Phishing Detection Using a Deep Learning Framework | Wireless Communications and Mobile Computing · 2018 | [Paper](<https://doi.org/10.1155/2018/4678746>) |
| **Lightweight detection** | A Deep-Learning-Driven Light-Weight Phishing Detection Sensor | Sensors · 2019 | [Paper](<https://doi.org/10.3390/s19194258>) |
| **Feature selection** | A new hybrid ensemble feature selection framework for machine learning-based phishing detection system | Information Sciences · 2019 | [Paper](<https://doi.org/10.1016/j.ins.2019.01.064>) |
| **CNN and LSTM** | Deep Learning with Convolutional Neural Network and Long Short-Term Memory for Phishing Detection | 2019 13th International Conference on Software, Knowledge, Information Management and Applications (SKIMA) · 2019 | [Paper](<https://doi.org/10.1109/skima47702.2019.8982427>) |
| **Feature engineering** | Detection of phishing websites using an efficient feature-based machine learning framework | Neural Computing and Applications · 2019 | [Paper](<https://doi.org/10.1007/s00521-017-3305-0>) |
| **Multidimensional features** | Phishing Website Detection Based on Multidimensional Features Driven by Deep Learning | IEEE Access · 2019 | [Paper](<https://doi.org/10.1109/access.2019.2892066>) |
| **CNN–MHSA** | CNN–MHSA: A Convolutional Neural Network and multi-head self-attention combined approach for detecting phishing websites | Neural Networks · 2020 | [Paper](<https://doi.org/10.1016/j.neunet.2020.02.013>) |
| **Browser-based detection** | Development of anti-phishing browser based on random forest and rule of extraction framework | Cybersecurity · 2020 | [Paper](<https://doi.org/10.1186/s42400-020-00059-1>) |
| **DTOF-ANN** | DTOF-ANN: An Artificial Neural Network phishing detection model based on Decision Tree and Optimal Features | Applied Soft Computing · 2020 | [Paper](<https://doi.org/10.1016/j.asoc.2020.106505>) |
| **Convolutional network** | High Accuracy Phishing Detection Based on Convolutional Neural Networks | 2020 3rd International Conference on Computer Applications &amp; Information Security (ICCAIS) · 2020 | [Paper](<https://doi.org/10.1109/iccais48893.2020.9096869>) |
| **Machine learning** | Machine Learning-Based Phishing Attack Detection | International Journal of Advanced Computer Science and Applications · 2020 | [Paper](<https://doi.org/10.14569/ijacsa.2020.0110945>) |
| **PhiDMA** | PhiDMA – A phishing detection model with multi-filter approach | Journal of King Saud University - Computer and Information Sciences · 2020 | [Paper](<https://doi.org/10.1016/j.jksuci.2017.07.005>) |
| **Model optimization** | Phishing Web Page Detection Using Optimised Machine Learning | 2020 IEEE 19th International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom) · 2020 | [Paper](<https://doi.org/10.1109/trustcom50675.2020.00072>) |
| **Twin SVM** | A heuristic technique to detect phishing websites using TWSVM classifier | Neural Computing and Applications · 2021 | [Paper](<https://doi.org/10.1007/s00521-020-05354-z>) |
| **Extreme learning machine** | An improved ELM-based and data preprocessing integrated approach for phishing detection considering comprehensive features | Expert Systems with Applications · 2021 | [Paper](<https://doi.org/10.1016/j.eswa.2020.113863>) |
| **Online detection** | Intelligent cyber-phishing detection for online | Computers &amp; Security · 2021 | [Paper](<https://doi.org/10.1016/j.cose.2020.102123>) |
| **Fuzzy sets** | Similarity measure fuzzy soft set for phishing detection | International Journal of Advances in Intelligent Informatics · 2021 | [Paper](<https://doi.org/10.26555/ijain.v7i1.605>) |
| **Deep learning** | A Deep Learning-Based Framework for Phishing Website Detection | IEEE Access · 2022 | [Paper](<https://doi.org/10.1109/access.2021.3137636>) |
| **Classifier comparison** | An Efficient Phishing Attack Detection using Machine Learning Algorithms | 2022 International Conference on Advancements in Smart, Secure and Intelligent Computing (ASSIC) · 2022 | [Paper](<https://doi.org/10.1109/assic55218.2022.10088399>) |
| **Hybrid features** | Modeling Hybrid Feature-Based Phishing Websites Detection Using Machine Learning Techniques | Annals of Data Science · 2022 | [Paper](<https://doi.org/10.1007/s40745-022-00379-8>) |
| **MOE/RF** | MOE/RF: A Novel Phishing Detection Model Based on Revised Multiobjective Evolution Optimization Algorithm and Random Forest | IEEE TNSM · 2022 | [Paper](<https://doi.org/10.1109/tnsm.2022.3162885>) |
| **PDGAN** | PDGAN: Phishing Detection With Generative Adversarial Networks | IEEE Access · 2022 | [Paper](<https://doi.org/10.1109/access.2022.3168235>) |
| **Semantic features** | Phishing Website Detection With Semantic Features Based on Machine Learning Classifiers | International Journal on Semantic Web and Information Systems · 2022 | [Paper](<https://doi.org/10.4018/ijswis.297032>) |
| **CCBLA** | CCBLA: a Lightweight Phishing Detection Model Based on CNN, BiLSTM, and Attention Mechanism | Cognitive Computation · 2023 | [Paper](<https://doi.org/10.1007/s12559-022-10024-4>) |
| **Metaheuristic optimization** | Metaheuristics with deep learning driven phishing detection for sustainable and secure environment | Sustainable Energy Technologies and Assessments · 2023 | [Paper](<https://doi.org/10.1016/j.seta.2023.103114>) |
| **System provenance** | Detecting Malicious Websites From the Perspective of System Provenance Analysis | IEEE TDSC · 2024 | [Paper](<https://doi.org/10.1109/tdsc.2023.3277613>) |
| **PDHF** | PDHF: Effective phishing detection model combining optimal artificial and automatic deep features | Computers &amp; Security · 2024 | [Paper](<https://doi.org/10.1016/j.cose.2023.103561>) |
| **SHAP** | A Phishing Website Detection System Based on Hybrid Feature Engineering with SHAP Explainable Artificial Intelligence Technique | Web Information Systems Engineering – WISE 2024 PhD Symposium, Demos and Workshops · 2025 | [Paper](<https://doi.org/10.1007/978-981-96-1483-7_1>) |
| **Feature selection** | Feature Selection for Improved Phishing Detection | — | [Paper](<https://link.springer.com/chapter/10.1007/978-3-642-31087-4_27>) |
| **Page classification** | Large-Scale Automatic Classification of Phishing Pages | NDSS | [Paper](<https://www.ndss-symposium.org/ndss2010/large-scale-automatic-classification-phishing-pages/>) |
| **Phishing-Aware** | Phishing-Aware: A Neuro-Fuzzy Approach for Anti-Phishing on Fog Networks | — | [Paper](<https://ieeexplore.ieee.org/document/8352739>) |
| **PhishLang** | PhishLang: A Real-Time, Fully Client-Side Phishing Detection Framework Using MobileBERT | NDSS | [Paper](<https://www.ndss-symposium.org/ndss-paper/phishlang-a-real-time-fully-client-side-phishing-detection-framework-using-mobilebert/>) |

[↑ Topic index](#browse-the-bibliography)

<a id="visual-identity-and-reference-matching"></a>

### Visual identity and reference matching

Look at what is matched across pages, how the claimed brand is identified and how the domain is checked.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **Visual similarity** | Detection of phishing webpages based on visual similarity | 2005 | [Paper](<https://doi.org/10.1145/1062745.1062868>) |
| **Visual assessment** | An antiphishing strategy based on visual similarity assessment | IEEE Internet Computing · 2006 | [Paper](<https://doi.org/10.1109/mic.2006.23>) |
| **Earth mover’s distance** | Detecting Phishing Web Pages with Visual Similarity Assessment Based on Earth Mover's Distance (EMD) | IEEE TDSC · 2006 | [Paper](<https://doi.org/10.1109/tdsc.2006.50>) |
| **Page layout** | A layout-similarity-based approach for detecting phishing pages | 2007 Third International Conference on Security and Privacy in Communications Networks and the Workshops - SecureComm 2007 · 2007 | [Paper](<https://doi.org/10.1109/seccom.2007.4550367>) |
| **Visual similarity** | Visual-Similarity-Based Phishing Detection | 2008 | [Paper](<https://doi.org/10.1145/1460877.1460905>) |
| **Visual keypoints** | Fighting Phishing with Discriminative Keypoint Features | IEEE Internet Computing · 2009 | [Paper](<https://doi.org/10.1109/mic.2009.59>) |
| **GoldPhish** | GoldPhish: Using Images for Content-Based Phishing Analysis | 2010 Fifth International Conference on Internet Monitoring and Protection · 2010 | [Paper](<https://doi.org/10.1109/icimp.2010.24>) |
| **Site signatures** | Mitigate web phishing using site signatures | TENCON 2010 - 2010 IEEE Region 10 Conference · 2010 | [Paper](<https://doi.org/10.1109/tencon.2010.5686582>) |
| **PhishZoo** | PhishZoo: Detecting Phishing Websites by Looking at Them | 2011 IEEE Fifth International Conference on Semantic Computing · 2011 | [Paper](<https://doi.org/10.1109/icsc.2011.52>) |
| **Bayesian fusion** | Textual and Visual Content-Based Anti-Phishing: A Bayesian Approach | IEEE transactions on neural networks / a publication of the IEEE Neural Networks Council · 2011 | [Paper](<https://doi.org/10.1109/tnn.2011.2161999>) |
| **BaitAlarm** | BaitAlarm: Detecting Phishing Sites Using Similarity in Fundamental Visual Features | 2013 5th International Conference on Intelligent Networking and Collaborative Systems · 2013 | [Paper](<https://doi.org/10.1109/incos.2013.151>) |
| **Website identity** | Phishing Detection via Identification of Website Identity | 2013 International Conference on IT Convergence and Security (ICITCS) · 2013 | [Paper](<https://doi.org/10.1109/icitcs.2013.6717870>) |
| **Spatial layout** | Web phishing detection based on page spatial layout similarity | Informatica (Slovenia) · 2013 | [Title search](<https://scholar.google.com/scholar?q=Web%20phishing%20detection%20based%20on%20page%20spatial%20layout%20similarity>) |
| **Computer vision** | A Computer Vision Technique to Detect Phishing Attacks | 2015 Fifth International Conference on Communication Systems and Network Technologies · 2015 | [Paper](<https://doi.org/10.1109/csnt.2015.68>) |
| **Website logos** | Utilisation of website logo for phishing detection | Computers &amp; Security · 2015 | [Paper](<https://doi.org/10.1016/j.cose.2015.07.006>) |
| **Phishing-Alarm** | Phishing-Alarm: Robust and Efficient Phishing Detection via Page Component Similarity | IEEE Access · 2017 | [Paper](<https://doi.org/10.1109/access.2017.2743528>) |
| **Image and CSS** | Visual Similarity-Based Phishing Detection Scheme Using Image and CSS with Target Website Finder | GLOBECOM 2017 - 2017 IEEE Global Communications Conference · 2017 | [Paper](<https://doi.org/10.1109/glocom.2017.8254506>) |
| **Layout aggregation** | Detecting Phishing Websites via Aggregation Analysis of Page Layouts | Procedia Computer Science · 2018 | [Paper](<https://doi.org/10.1016/j.procs.2018.03.053>) |
| **Phish-IRIS** | Phish-IRIS: A New Approach for Vision Based Brand Prediction of Phishing Web Pages via Compact Visual Descriptors | 2018 2nd International Symposium on Multidisciplinary Studies and Innovative Technologies (ISMSIT) · 2018 | [Paper](<https://doi.org/10.1109/ismsit.2018.8567299>) |
| **Layout classification** | Phishing page detection via learning classifiers from page layout feature | EURASIP Journal on Wireless Communications and Networking · 2019 | [Paper](<https://doi.org/10.1186/s13638-019-1361-0>) |
| **Mobile OCR** | Cost-Effective OCR Implementation to Prevent Phishing on Mobile Platforms | 2020 International Conference on Cyber Security and Protection of Digital Services (Cyber Security) · 2020 | [Paper](<https://doi.org/10.1109/cybersecurity49315.2020.9138873>) |
| **LogoSENSE** | LogoSENSE: A companion HOG based logo detection scheme for phishing web page and E-mail brand recognition | Computers &amp; Security · 2020 | [Paper](<https://doi.org/10.1016/j.cose.2020.101855>) |
| **VisualPhishNet** | VisualPhishNet: Zero-Day Phishing Website Detection by Visual Similarity | ACM CCS · 2020 | [Paper](<https://doi.org/10.1145/3372297.3417233>) |
| **Clone detection** | Combining Text and Visual Features to Improve the Identification of Cloned Webpages for Early Phishing Detection | Proceedings of the 16th International Conference on Availability, Reliability and Security · 2021 | [Paper](<https://doi.org/10.1145/3465481.3470112>) |
| **Phishpedia** | Phishpedia: A Hybrid Deep Learning Based Approach to Visually Identify Phishing Webpages | USENIX Security · 2021 | [Paper](<https://www.usenix.org/conference/usenixsecurity21/presentation/lin>) · [Code](<https://github.com/lindsey98/Phishpedia>) |
| **Visual features** | Webpage visual feature extraction and similarity algorithm | Proceedings of the 2020 International Conference on Cyberspace Innovation of Advanced Technologies · 2021 | [Paper](<https://doi.org/10.1145/3444370.3444552>) |
| **PhishIntention** | Inferring Phishing Intention via Webpage Appearance and Dynamics: A Deep Vision Based Approach | USENIX Security · 2022 | [Paper](<https://www.usenix.org/conference/usenixsecurity22/presentation/liu-ruofan>) · [Code](<https://github.com/lindsey98/PhishIntention>) |
| **Logo recognition** | Phishing Attack Detection with ML-Based Siamese Empowered ORB Logo Recognition and IP Mapper | IEEE INFOCOM 2022 - IEEE Conference on Computer Communications Workshops (INFOCOM WKSHPS) · 2022 | [Paper](<https://doi.org/10.1109/infocomwkshps54753.2022.9798203>) |
| **Text and visual identity** | Hybrid phishing detection using joint visual and textual identity | Expert Systems with Applications · 2023 | [Paper](<https://doi.org/10.1016/j.eswa.2023.119723>) |
| **DynaPhish** | Knowledge Expansion and Counterfactual Interaction for Reference-Based Phishing Detection | USENIX Security · 2023 | [Paper](<https://www.usenix.org/conference/usenixsecurity23/presentation/liu-ruofan>) · [Code](<https://github.com/code-philia/Dynaphish>) |
| **PhishDecloaker** | PhishDecloaker: Detecting CAPTCHA-cloaked Phishing Websites via Hybrid Vision-based Interactive Models | 2024 | [Paper](<https://www.usenix.org/conference/usenixsecurity24/presentation/teoh>) |
| **Client-side resources** | Phishing Vs. Legit: Comparative Analysis of Client-Side Resources of Phishing and Target Brand Websites | The Web Conference · 2024 | [Paper](<https://doi.org/10.1145/3589334.3645535>) |
| **Local and global similarity** | Phishing webpage detection based on global and local visual similarity | Expert Systems with Applications · 2024 | [Paper](<https://doi.org/10.1016/j.eswa.2024.124120>) |
| **PhishIntel** | PhishIntel: Toward Practical Deployment of Reference-based Phishing Detection | 2024 | [Paper](<https://doi.org/10.48550/arxiv.2412.09057>) |

[↑ Topic index](#browse-the-bibliography)

<a id="email-sms-and-social-engineering"></a>

### Email, SMS and social engineering

Follow the message from delivery to the requested action. Look for evidence from wording, sender identity and links.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **Email classification** | Learning to detect phishing emails | WWW · 2007 | [Paper](<https://doi.org/10.1145/1242572.1242660>) |
| **Persuasion cues** | Phishing Email Detection Using Persuasion Cues | IEEE TDSC · 2022 | [Paper](<https://doi.org/10.1109/tdsc.2021.3118931>) |
| **SMS explanation** | Can You Walk Me Through It? Explainable SMS Phishing Detection using LLM-based Agents | 2025 | [Paper](<https://www.usenix.org/conference/soups2025/presentation/wang>) |
| **MultiPhishGuard** | MultiPhishGuard: An LLM-based Multi-Agent System for Phishing Email Detection | arXiv · 2025 | [Paper](<https://doi.org/10.48550/arxiv.2505.23803>) |
| **Paladin** | Paladin: Defending LLM-enabled Phishing Emails with a New Trigger-Tag Paradigm | NDSS · 2025 | [Paper](<https://doi.org/10.48550/arxiv.2509.07287>) |
| **Email language models** | LMs go Phishing: Adapting Pre-trained Language Models to Detect Phishing Emails | — | [Paper](<https://ieeexplore.ieee.org/abstract/document/10101955?casa_token=5_6Rm8LdVc0AAAAA:XXCwPcDBXQ5QGHoEgju7DydUlRx-cgBiQx4p8bhh6FPNIPejF9m1caLJBTbhu_CgT3r8I0U>) |

[↑ Topic index](#browse-the-bibliography)

<a id="llms-and-multimodal-reasoning"></a>

### LLMs and multimodal reasoning

Compare the inputs each model sees and the evidence it gives for a verdict.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **ChatGPT** | Detecting Phishing Sites Using ChatGPT | 2024 | [Paper](<https://doi.org/10.48550/arxiv.2306.05816>) |
| **KnowPhish** | KnowPhish: Large Language Models Meet Multimodal Knowledge Graphs for Enhancing Reference-Based Phishing Detection | USENIX Security · 2024 | [Paper](<https://www.usenix.org/conference/usenixsecurity24/presentation/li-yuexin>) · [Materials](<https://github.com/imethanlee/KnowPhish>) |
| **PhishLLM** | Less Defined Knowledge and More True Alarms: Reference-based Phishing Detection without a Pre-defined Reference List | USENIX Security · 2024 | [Paper](<https://www.usenix.org/conference/usenixsecurity24/presentation/liu-ruofan>) · [Code](<https://github.com/code-philia/PhishLLM>) |
| **PhishAgent** | PhishAgent: A Robust Multimodal Agent for Phishing Webpage Detection | AAAI · 2025 | [Paper](<https://doi.org/10.1609/aaai.v39i27.35003>) |
| **PhishIntentionLLM** | PhishIntentionLLM: Uncovering Phishing Website Intentions through Multi-Agent Retrieval-Augmented Generation | arXiv · 2025 | [Paper](<https://arxiv.org/abs/2507.15419>) |
| **MemoPhishAgent** | MemoPhishAgent: Memory-Augmented Multi-Modal LLM Agent for Phishing URL Detection | arXiv · 2026 | [Paper](<https://arxiv.org/abs/2602.21394>) |

[↑ Topic index](#browse-the-bibliography)

<a id="attacks-and-people"></a>

## 🛡️ Attacks and human factors

<a id="attack-measurement-and-robustness"></a>

### Attack measurement and robustness

Compare the assumed attacker capabilities, the evidence evaluated and whether a study measures effects on users or on detectors.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **Classifier evaluation** | Cracking Classifiers for Evasion: A Case Study on the Google's Phishing Pages Filter | Proceedings of the 25th International Conference on World Wide Web · 2016 | [Paper](<https://doi.org/10.1145/2872427.2883060>) |
| **PhishFarm** | PhishFarm: A Scalable Framework for Measuring the Effectiveness of Evasion Techniques against Browser Phishing Blacklists | 2019 IEEE Symposium on Security and Privacy (SP) · 2019 | [Paper](<https://doi.org/10.1109/sp.2019.00049>) |
| **Robustness evaluation** | Towards Adversarial Phishing Detection | 2020 | [Paper](<https://www.usenix.org/conference/cset20/presentation/panum>) |
| **PhishInPatterns** | PhishInPatterns: measuring elicited user interactions at scale on phishing websites | Proceedings of the 22nd ACM Internet Measurement Conference · 2022 | [Paper](<https://doi.org/10.1145/3517745.3561467>) |
| **URL detector robustness** | Reliability and Robustness analysis of Machine Learning based Phishing URL Detectors | IEEE TDSC · 2022 | [Paper](<https://doi.org/10.1109/tdsc.2022.3218043>) |
| **Conditional GAN** | Semi-supervised Conditional GAN for Simultaneous Generation and Detection of Phishing URLs: A Game theoretic Perspective | 2022 | [Paper](<https://doi.org/10.48550/arxiv.2108.01852>) |
| **SpacePhish** | SpacePhish: The Evasion-space of Adversarial Attacks against Phishing Website Detectors using Machine Learning | Proceedings of the 38th Annual Computer Security Applications Conference · 2022 | [Paper](<https://doi.org/10.1145/3564625.3567980>) |
| **LLM campaign study** | Targeted Phishing Campaigns using Large Scale Language Models | 2022 | [Paper](<http://arxiv.org/abs/2301.00665>) |
| **Classifier evaluation** | A Good Fishman Knows All the Angles: A Critical Evaluation of Google's Phishing Page Classifier | Proceedings of the 2023 ACM SIGSAC Conference on Computer and Communications Security · 2023 | [Paper](<https://doi.org/10.1145/3576915.3623199>) |
| **Human and LLM comparison** | Devising and Detecting Phishing: Large Language Models vs. Smaller Human Models | 2023 | [Paper](<http://arxiv.org/abs/2308.12287>) |
| **Competition field study** | Evading Anti-Phishing Models: A Field Note Documenting an Experience in the Machine Learning Security Evasion Competition 2022 | Digital Threats: Research and Practice · 2023 | [Paper](<https://doi.org/10.1145/3603507>) |
| **Awareness training** | Generating Personalized Phishing Emails for Social Engineering Training Based on Neural Language Models | Advances on Broad-Band Wireless Computing, Communication and Applications · 2023 | [Paper](<https://doi.org/10.1007/978-3-031-20029-8_26>) |
| **Detector robustness** | Mitigating Adversarial Gray-Box Attacks Against Phishing Detectors | IEEE TDSC · 2023 | [Paper](<https://doi.org/10.1109/tdsc.2022.3210029>) |
| **HTML robustness** | Raze to the Ground: Query-Efficient Adversarial HTML Attacks on Machine-Learning Phishing Webpage Detectors | Proceedings of the 16th ACM Workshop on Artificial Intelligence and Security · 2023 | [Paper](<https://doi.org/10.1145/3605764.3623920>) |
| **Spear phishing** | Spear Phishing With Large Language Models | 2023 | [Paper](<https://doi.org/10.48550/arxiv.2305.06972>) |
| **User perception** | "Are Adversarial Phishing Webpages a Threat in Reality?" Understanding the Users' Perception of Adversarial Webpages | Proceedings of the ACM Web Conference 2024 · 2024 | [Paper](<https://doi.org/10.1145/3589334.3645502>) |
| **Logo detector robustness** | Attacking Logo-Based Phishing Website Detectors with Adversarial Perturbations | Computer Security – ESORICS 2023 · 2024 | [Paper](<https://doi.org/10.1007/978-3-031-51479-1_9>) |
| **Phishing kit measurement** | Beneath the Phishing Scripts: A Script-Level Analysis of Phishing Kits and Their Impact on Real-World Phishing Websites | Proceedings of the 19th ACM Asia Conference on Computer and Communications Security · 2024 | [Paper](<https://doi.org/10.1145/3634737.3657013>) |
| **LLM email study** | Devising and Detecting Phishing Emails Using Large Language Models | IEEE Access · 2024 | [Paper](<https://doi.org/10.1109/access.2024.3375882>) |
| **Ethereum measurement** | Fishing for Fraudsters: Uncovering Ethereum Phishing Gangs With Blockchain Data | IEEE Transactions on Information Forensics and Security · 2024 | [Paper](<https://doi.org/10.1109/tifs.2024.3359000>) |
| **Visual detector robustness** | It Doesn’t Look Like Anything to Me: Using Diffusion Model to Subvert Visual Phishing Detectors | USENIX2024 · 2024 | [Title search](<https://scholar.google.com/scholar?q=It%20Doesn%E2%80%99t%20Look%20Like%20Anything%20to%20Me%3A%20Using%20Diffusion%20Model%20to%20Subvert%20Visual%20Phishing%20Detectors>) |
| **PhishinWebView** | PhishinWebView: Analysis of Anti-Phishing Entities in Mobile Apps with WebView Targeted Phishing | The Web Conference · 2024 | [Paper](<https://doi.org/10.1145/3589334.3645708>) |
| **Visual detector evaluation** | Evaluating the Effectiveness and Robustness of Visual Similarity-based Phishing Detection Models | 2025 | [Title search](<https://scholar.google.com/scholar?q=Evaluating%20the%20Effectiveness%20and%20Robustness%20of%20Visual%20Similarity-based%20Phishing%20Detection%20Models>) |
| **DNS measurement** | Exposing the Roots of DNS Abuse: A Data-Driven Analysis of Key Factors Behind Phishing Domain Registrations | Proceedings of the 2025 ACM SIGSAC Conference on Computer and Communications Security · 2025 | [Paper](<https://doi.org/10.1145/3719027.3744869>) |
| **Robustness comparison** | From ML to LLM: Evaluating the Robustness of Phishing Web Page Detection Models against Adversarial Attacks | Digital Threats: Research and Practice · 2025 | [Paper](<https://doi.org/10.1145/3737295>) |
| **CtPhishCapture** | CtPhishCapture: Uncovering Credential-Theft-Based Phishing Scams Targeting Cryptocurrency Wallets | NDSS | [Paper](<https://www.ndss-symposium.org/ndss-paper/ctphishcapture-uncovering-credential-theft-based-phishing-scams-targeting-cryptocurrency-wallets/>) |
| **Ethereum evaluation** | Phishing in Wonderland: Evaluating Learning-Based Ethereum Phishing Transaction Detection and Pitfalls | NDSS | [Paper](<https://www.ndss-symposium.org/ndss-paper/phishing-in-wonderland-evaluating-learning-based-ethereum-phishing-transaction-detection-and-pitfalls/>) |

[↑ Topic index](#browse-the-bibliography)

<a id="people-warnings-and-authentication"></a>

### People, warnings and authentication

Ask who makes the final decision and how the study measures comprehension, behaviour or susceptibility.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **Dynamic Security Skins** | The battle against phishing: Dynamic Security Skins | Proceedings of the 2005 symposium on Usable privacy and security · 2005 | [Paper](<https://doi.org/10.1145/1073001.1073009>) |
| **ViWiD** | ViWiD : Visible Watermarking Based Defense Against Phishing | Digital Watermarking · 2005 | [Paper](<https://doi.org/10.1007/11551492_36>) |
| **Security toolbars** | Do security toolbars actually prevent phishing attacks? | ACM CHI · 2006 | [Paper](<https://doi.org/10.1145/1124772.1124863>) |
| **User study** | Why phishing works | ACM CHI · 2006 | [Paper](<https://doi.org/10.1145/1124772.1124861>) |
| **Browser warnings** | You've been warned: an empirical study of the effectiveness of web browser phishing warnings | ACM CHI · 2008 | [Paper](<https://doi.org/10.1145/1357054.1357219>) |
| **Physiological signals** | A Multi-Modal Neuro-Physiological Study of Phishing Detection and Malware Warnings | Proceedings of the 22nd ACM SIGSAC Conference on Computer and Communications Security · 2015 | [Paper](<https://doi.org/10.1145/2810103.2813660>) |
| **Watermarking** | Preventing phishing attacks using text and image watermarking | Concurrency and Computation: Practice and Experience · 2019 | [Paper](<https://doi.org/10.1002/cpe.5083>) |
| **Phishing Funnel Model** | The Phishing Funnel Model: A Design Artifact to Predict User Susceptibility to Phishing Websites | Information Systems Research · 2021 | [Paper](<https://doi.org/10.1287/isre.2020.0973>) |
| **Evidence-based alerts** | Real-Time, Evidence-Based Alerts for Protection from Phishing Attacks | IEEE TDSC · 2024 | [Paper](<https://doi.org/10.1109/tdsc.2024.3425908>) |
| **URL inspection** | URL Inspection Tasks: Helping Users Detect Phishing Links in Emails | 2025 | [Paper](<https://www.usenix.org/conference/usenixsecurity25/presentation/lain>) |
| **PHAD** | PHAD- A Phishing Avoidance and Detection Tool Using Invisible Digital Watermarking | — | [Title search](<https://scholar.google.com/scholar?q=PHAD-%20A%20Phishing%20Avoidance%20and%20Detection%20Tool%20Using%20Invisible%20Digital%20Watermarking>) |
| **Toolbar evaluation** | Phinding Phish: An Evaluation of Anti-Phishing Toolbars | NDSS | [Paper](<https://www.ndss-symposium.org/ndss2007/phinding-phish-evaluation-anti-phishing-toolbars/>) |
| **Awareness training** | Supporting the Design of Phishing Education, Training and Awareness interventions: an LLM-based approach | — | [Title search](<https://scholar.google.com/scholar?q=Supporting%20the%20Design%20of%20Phishing%20Education%2C%20Training%20and%20Awareness%20interventions%3A%20an%20LLM-based%20approach>) |
| **Two-level authentication** | Two-level authentication approach to protect from phishing attacks in real time | — | [Paper](<https://link.springer.com/article/10.1007/s12652-017-0616-z>) |

[↑ Topic index](#browse-the-bibliography)

<a id="surveys-and-resources"></a>

## 📚 Surveys, datasets and benchmarks

<a id="surveys-and-field-guides"></a>

### Surveys and field guides

Start here for terminology, threat models and comparisons across detection methods.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **Detection survey** | Phishing Detection: A Literature Survey | IEEE Communications Surveys &amp; Tutorials · 2013 | [Paper](<https://doi.org/10.1109/surv.2013.032213.00009>) |
| **Malicious URL survey** | Malicious URL Detection using Machine Learning: A Survey | arXiv · 2017 | [Paper](<https://arxiv.org/abs/1701.07179>) |
| **Defense survey** | A recent review of conventional vs. automated cybersecurity anti-phishing techniques | Computer Science Review · 2018 | [Paper](<https://doi.org/10.1016/j.cosrev.2018.05.003>) |
| **Attack taxonomy** | A survey of phishing attacks: Their types, vectors and technical approaches | Expert Systems with Applications · 2018 | [Paper](<https://doi.org/10.1016/j.eswa.2018.03.050>) |
| **Detection survey** | Review: Phishing Detection Approaches | 2019 2nd International Conference on new Trends in Computing Sciences (ICTCS) · 2019 | [Paper](<https://doi.org/10.1109/ictcs.2019.8923069>) |
| **URL heuristics** | Heuristic-based strategy for Phishing prediction: A survey of URL-based approach | Computers &amp; Security · 2020 | [Paper](<https://doi.org/10.1016/j.cose.2019.101613>) |
| **Security research survey** | SoK: A Comprehensive Reexamination of Phishing Research From the Security Perspective | IEEE Communications Surveys &amp; Tutorials · 2020 | [Paper](<https://doi.org/10.1109/comst.2019.2957750>) |
| **Attacks and defenses** | A survey of phishing attack techniques, defence mechanisms and open research challenges | Enterprise Information Systems · 2022 | [Paper](<https://doi.org/10.1080/17517575.2021.1896786>) |
| **Deep learning survey** | Applications of deep learning for phishing detection: a systematic literature review | Knowledge and Information Systems · 2022 | [Paper](<https://doi.org/10.1007/s10115-022-01672-x>) |
| **Website detection survey** | A systematic literature review on phishing website detection techniques | Journal of King Saud University - Computer and Information Sciences · 2023 | [Paper](<https://doi.org/10.1016/j.jksuci.2023.01.004>) |
| **User study review** | Sixteen Years of Phishing User Studies: What Have We Learned? | IEEE TDSC · 2023 | [Paper](<https://doi.org/10.1109/tdsc.2022.3151103>) |
| **PHILTER** | SoK: PHILTER: Uncovering Security and Functional Gaps in AI-based Phishing Website Detection Literature via an LLM-based Reasoning Framework \| USENIX | — | [Paper](<https://www.usenix.org/conference/usenixsecurity26/presentation/alam>) |

[↑ Topic index](#browse-the-bibliography)

<a id="datasets-feeds-and-benchmarks"></a>

### Datasets, feeds and benchmarks

Check how examples were collected, labelled and split. A phishing feed records observed attacks, while an evaluation dataset also needs a sampling protocol.

| Method or focus | Paper or resource | Publication | Links |
| --- | --- | --- | --- |
| **Offline benchmark** | Building Standard Offline Anti-phishing Dataset for Benchmarking | International Journal of Engineering &amp; Technology · 2018 | [Paper](<https://doi.org/10.14419/ijet.v7i4.31.23333>) |
| **Feature dataset** | Phishing Dataset for Machine Learning: Feature Evaluation | 2018 | [Dataset](<https://doi.org/10.17632/h3cgnj8hft.1>) |
| **Feature comparison** | A Feature Selection Comparative Study for Web Phishing Datasets | 2020 IEEE International Conference on Electronics, Computing and Communication Technologies (CONECCT) · 2020 | [Paper](<https://doi.org/10.1109/conecct50063.2020.9198349>) |
| **PhishBench 2.0** | PhishBench 2.0: A Versatile and Extendable Benchmarking Framework for Phishing | ACM CCS · 2020 | [Paper](<https://doi.org/10.1145/3372297.3420017>) |
| **Dataset benchmarking** | Towards benchmark datasets for machine learning based website phishing detection: An experimental study | Engineering Applications of Artificial Intelligence · 2021 | [Paper](<https://doi.org/10.1016/j.engappai.2021.104347>) |
| **Annual threat report** | Kaspersky's 2022 spam and phishing report | 2023 | [Report](<https://securelist.com/spam-phishing-scam-report-2022/108692/>) |
| **Logo-2K+** | Wangjing1551/Logo-2k-plus-Dataset | 2024 | [Dataset](<https://github.com/Wangjing1551/Logo-2k-plus-Dataset>) |
| **IC3 annual report** | 2025 IC3 Annual Report | 2026 | [Report](<https://www.ic3.gov/AnnualReport/Reports/2025_IC3Report.pdf>) |
| **PhishingBaseline** | lindsey98/PhishingBaseline | 2026 | [Code](<https://github.com/lindsey98/PhishingBaseline>) |
| **APWG trends report** | Phishing Activity Trends Report: 1st Quarter 2026 | 2026 | [Report](<https://apwg.org/trendreports>) |
| **State of the Phish** | 2023 State of the Phish | — | [Title search](<https://scholar.google.com/scholar?q=2023%20State%20of%20the%20Phish>) |
| **APWG** | APWG | — | [Website](<https://apwg.org/trendreports?utm_source=chatgpt.com>) |
| **OpenPhish** | OpenPhish - Phishing Intelligence | — | [Website](<https://www.openphish.com/>) |
| **PhishStorm dataset** | PhishStorm - phishing / legitimate URL dataset | Aalto University's research portal | [Dataset](<https://research.aalto.fi/en/datasets/phishstorm-phishing-legitimate-url-dataset>) |
| **PhishTank** | PhishTank \| Join the fight against phishing | — | [Website](<https://phishtank.org/>) |
| **Quarterly threat report** | Q4 2022 Malware and Phishing Report: Phishing Volumes Increase 36% QoQ | — | [Report](<https://www.vadesecure.com/en/blog/q4-2022-phishing-and-malware-report>) |

[↑ Topic index](#browse-the-bibliography)

<a id="suggested-reading-paths"></a>

## 🧭 Suggested reading paths

### How do phishing sites persuade people?

Read the original user study, then compare its findings with the longer review of how phishing experiments are designed.

1. [Why phishing works](https://doi.org/10.1145/1124772.1124861)
2. [Sixteen Years of Phishing User Studies: What Have We Learned?](https://doi.org/10.1109/tdsc.2022.3151103)

### What can a detector see?

Compare page content, URL characters, visual similarity and page interaction. For each paper, write down the minimum input needed for one prediction.

1. [Cantina: a content-based approach to detecting phishing web sites](https://doi.org/10.1145/1242572.1242659)
2. [URLNet: Learning a URL Representation with Deep Learning for Malicious URL Detection](https://arxiv.org/abs/1802.03162)
3. [VisualPhishNet: Zero-Day Phishing Website Detection by Visual Similarity](https://doi.org/10.1145/3372297.3417233)
4. [Inferring Phishing Intention via Webpage Appearance and Dynamics: A Deep Vision Based Approach](https://www.usenix.org/conference/usenixsecurity22/presentation/liu-ruofan)

### How should I evaluate a detector?

Trace when labels become available, how test examples are selected and how performance changes under different conditions.

1. [An Analysis of Phishing Blacklists: Google Safe Browsing, OpenPhish, and PhishTank](https://doi.org/10.1145/3373017.3373020)
2. [Towards benchmark datasets for machine learning based website phishing detection: An experimental study](https://doi.org/10.1016/j.engappai.2021.104347)
3. [Evaluating the Effectiveness and Robustness of Visual Similarity-based Phishing Detection Models](https://scholar.google.com/scholar?q=Evaluating%20the%20Effectiveness%20and%20Robustness%20of%20Visual%20Similarity-based%20Phishing%20Detection%20Models)

### Where do LLMs enter the decision?

Compare a site-level verdict with brand knowledge and email analysis. Which evidence can a reader independently check?

1. [Detecting Phishing Sites Using ChatGPT](https://doi.org/10.48550/arxiv.2306.05816)
2. [KnowPhish: Large Language Models Meet Multimodal Knowledge Graphs for Enhancing Reference-Based Phishing Detection](https://www.usenix.org/conference/usenixsecurity24/presentation/li-yuexin)
3. [MultiPhishGuard: An LLM-based Multi-Agent System for Phishing Email Detection](https://doi.org/10.48550/arxiv.2505.23803)
