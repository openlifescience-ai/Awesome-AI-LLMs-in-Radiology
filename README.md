# Awesome-AI/LLMs-in-Radiology

<p align="center">

✨✨ A curated list of awesome resources, papers, datasets, and tools related to AI in radiology. This repository aims to provide a comprehensive collection of materials to facilitate research, learning, and development in the field of AI-powered radiology.

<h4 align="center">
  <a href="https://t.co/vkvJli6ZP7">
    <img src="https://img.shields.io/badge/Join-Community-blue" alt="Community" height="30"/>
  </a>
</h4>


[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/monk1337/Awesome-Medical-Multimodal-Large-Language-Models)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img width="800" src="https://raw.githubusercontent.com/openlifescience-ai/Awesome-AI-LLMs-in-Radiology/main/images/radio.jpg">
  <br>
  <em>Image Source: A Generalist Learner for Multifaceted Medical Image Interpretation </em>
</p>
</p>

##### Table of Contents

## Categories


- [Radiology Report Generation and Summarization](#radiology-report-generation-and-summarization)
- [Vision-Language Models for Medical Imaging](#vision-language-models-for-medical-imaging)
- [Large Language Models in Radiology](#large-language-models-in-radiology)
- [Multimodal Learning for Medical Image Analysis](#multimodal-learning-for-medical-image-analysis)
- [Evaluation Metrics and Benchmarking for AI in Radiology](#evaluation-metrics-and-benchmarking-for-ai-in-radiology)
- [Medical Image Synthesis and Augmentation](#medical-image-synthesis-and-augmentation)
- [AI for Specific Radiological Tasks](#ai-for-specific-radiological-tasks)
- [AI-Assisted Diagnosis and Decision Support](#ai-assisted-diagnosis-and-decision-support)
- [Natural Language Processing for Clinical Reports](#natural-language-processing-for-clinical-reports)


## Papers

### Radiology Report Generation and Summarization

#### 2024

- [Benchmarking and Boosting Radiology Report Generation for 3D High-Resolution Medical Images](https://arxiv.org/abs/2406.07146) - Che Liu, Zhongwei Wan, Yuqi Wang, Hui Shen, Haozhe Wang, Kangyu Zheng, Mi Zhang, Rossella Arcucci
- [Direct Preference Optimization for Suppressing Hallucinated Prior Exams in Radiology Report Generation](https://arxiv.org/abs/2406.06496) - Oishi Banerjee, Hong-Yu Zhou, Subathra Adithan, Stephen Kwak, Kay Wu, Pranav Rajpurkar
- [MAIRA-2: Grounded Radiology Report Generation](https://arxiv.org/abs/2406.04449) - Shruthi Bannur, et al.
- [RadBARTsum: Domain Specific Adaption of Denoising Sequence-to-Sequence Models for Abstractive Radiology Report Summarization](https://arxiv.org/abs/2406.03062) - Jinge Wu, Abul Hasan, Honghan Wu
- [Textual Inversion and Self-supervised Refinement for Radiology Report Generation](https://arxiv.org/abs/2405.20607) - Yuanjiang Luo, Hongxiang Li, Xuan Wu, Meng Cao, Xiaoshuang Huang, Zhihong Zhu, Peixi Liao, Hu Chen, Yi Zhang
- [Structural Entities Extraction and Patient Indications Incorporation for Chest X-ray Report Generation](https://arxiv.org/abs/2405.14905) - Kang Liu, Zhuoqi Ma, Xiaolu Kang, Zhusi Zhong, Zhicheng Jiao, Grayson Baird, Harrison Bai, Qiguang Miao
- [Multi-modality Regional Alignment Network for Covid X-Ray Survival Prediction and Report Generation](https://arxiv.org/abs/2405.14113) - Zhusi Zhong, Jie Li, John Sollee, Scott Collins, Harrison Bai, Paul Zhang, Terrence Healey, Michael Atalay, Xinbo Gao, Zhicheng Jiao
- [A Survey of Deep Learning-based Radiology Report Generation Using Multimodal Data](https://arxiv.org/abs/2405.12833) - Xinyi Wang, Grazziela Figueredo, Ruizhe Li, Wei Emma Zhang, Weitong Chen, Xin Chen
- [Automated Radiology Report Generation: A Review of Recent Advances](https://arxiv.org/abs/2405.10842) - Phillip Sloan, Philip Clatworthy, Edwin Simpson, Majid Mirmehdi
- [Topicwise Separable Sentence Retrieval for Medical Report Generation](https://arxiv.org/abs/2405.04175) - Junting Zhao, Yang Zhou, Zhihao Chen, Huazhu Fu, Liang Wan
- [FITA: Fine-grained Image-Text Aligner for Radiology Report Generation](https://arxiv.org/abs/2405.00962) - Honglong Yang, Hui Tang, Xiaomeng Li
- [Expert Insight-Enhanced Follow-up Chest X-Ray Summary Generation](https://arxiv.org/abs/2405.00344) - Zhichuan Wang, Kinhei Lee, Qiao Deng, Tiffany Y. So, Wan Hang Chiu, Yeung Yu Hui, Bingjing Zhou, Edward S. Hui
- [SERPENT-VLM : Self-Refining Radiology Report Generation Using Vision Language Models](https://arxiv.org/abs/2404.17912) - Manav Nitin Kapadnis, Sohan Patnaik, Abhilash Nandy, Sourjyadip Ray, Pawan Goyal, Debdoot Sheet
- [MRScore: Evaluating Radiology Report Generation with LLM-based Reward System](https://arxiv.org/abs/2404.17778) - Yunyi Liu, Zhanyu Wang, Yingshu Li, Xinyu Liang, Lingqiao Liu, Lei Wang, Luping Zhou
- [Memory-based Cross-modal Semantic Alignment Network for Radiology Report Generation](https://arxiv.org/abs/2404.00588) - Yitian Tao, Liyan Ma, Jing Yu, Han Zhang
- [CT2Rep: Automated Radiology Report Generation for 3D Medical Imaging](https://arxiv.org/abs/2403.06801) - Ibrahim Ethem Hamamci, Sezgin Er, Bjoern Menze
- [Large Model driven Radiology Report Generation with Clinical Quality Reinforcement Learning](https://arxiv.org/abs/2403.06728) - Zijian Zhou, Miaojing Shi, Meng Wei, Oluwatosin Alabi, Zijie Yue, Tom Vercauteren
- [Scene Graph Aided Radiology Report Generation](https://arxiv.org/abs/2403.05687) - Jun Wang, Lixing Zhu, Abhir Bhalerao, Yulan He
- [ICON: Improving Inter-Report Consistency of Radiology Report Generation via Lesion-aware Mix-up Augmentation](https://arxiv.org/abs/2402.12844) - Wenjun Hou, Yi Cheng, Kaishuai Xu, Yan Hu, Wenjie Li, Jiang Liu

#### 2023

- [Pragmatic Radiology Report Generation](https://arxiv.org/abs/2311.17154) - Dang Nguyen, Chacha Chen, He He, Chenhao Tan
- [A Systematic Review of Deep Learning-based Research on Radiology Report Generation](https://arxiv.org/abs/2311.14199) - Chang Liu, Yuanhe Tian, Yan Song
- [MAIRA-1: A specialised large multimodal model for radiology report generation](https://arxiv.org/abs/2311.13668) - Stephanie L. Hyland, Shruthi Bannur, Kenza Bouzid, Daniel C. Castro, Mercy Ranjit, Anton Schwaighofer, Fernando Pérez-García, Valentina Salvatelli, Shaury Srivastav, Anja Thieme, Noel Codella, Matthew P. Lungren, Maria Teodora Wetscherek, Ozan Oktay, Javier Alvarez-Valle
- [FaMeSumm: Investigating and Improving Faithfulness of Medical Summarization](https://arxiv.org/abs/2311.02271) - Nan Zhang, Yusen Zhang, Wu Guo, Prasenjit Mitra, Rui Zhang
- [Enhanced Knowledge Injection for Radiology Report Generation](https://arxiv.org/abs/2311.00399) - Qingqiu Li, Jilan Xu, Runtian Yuan, Mohan Chen, Yuejie Zhang, Rui Feng, Xiaobo Zhang, Shang Gao
- [Style-Aware Radiology Report Generation with RadGraph and Few-Shot Prompting](https://arxiv.org/abs/2310.17811) - Benjamin Yan, Ruochen Liu, David E. Kuo, Subathra Adithan, Eduardo Pontes Reis, Stephen Kwak, Vasantha Kumar Venugopal, Chloe P. O'Connell, Agustina Saenz, Pranav Rajpurkar, Michael Moor
- [Automated Chest X-Ray Report Generator Using Multi-Model Deep Learning Approach](https://arxiv.org/abs/2310.05969) - Arief Purnama Muharram, Hollyana Puteri Haryono, Abassi Haji Juma, Ira Puspasari, Nugraha Priya Utama
- [Dynamic Multi-Domain Knowledge Networks for Chest X-ray Report Generation](https://arxiv.org/abs/2310.05119) - Weihua Liu, Youyuan Xue, Chaochao Lin, Said Boumaraf
- [Can Prompt Learning Benefit Radiology Report Generation?](https://arxiv.org/abs/2308.16269) - Jun Wang, Lixing Zhu, Abhir Bhalerao, Yulan He
- [Fact-Checking of AI-Generated Reports](https://arxiv.org/abs/2307.14634) - Razi Mahmood, Ge Wang, Mannudeep Kalra, Pingkun Yan
- [Reading Radiology Imaging Like The Radiologist](https://arxiv.org/abs/2307.05921) - Yuhao Wang
- [Replace and Report: NLP Assisted Radiology Report Generation](https://arxiv.org/abs/2306.17180) - Kaveri Kale, pushpak Bhattacharyya, Kshitij Jadhav
- [Utilizing Longitudinal Chest X-Rays and Reports to Pre-Fill Radiology Reports](https://arxiv.org/abs/2306.08749) - Qingqing Zhu, Tejas Sudharshan Mathai, Pritam Mukherjee, Yifan Peng, Ronald M. Summers, Zhiyong Lu
- [Consensus, dissensus and synergy between clinicians and specialist foundation models in radiology report generation](https://arxiv.org/abs/2311.18260) - Ryutaro Tanno, et al.
- [An Iterative Optimizing Framework for Radiology Report Summarization with ChatGPT](https://arxiv.org/abs/2304.08448) - Chong Ma, Zihao Wu, Jiaqi Wang, Shaochen Xu, Yaonai Wei, Fang Zeng, Zhengliang Liu, Xi Jiang, Lei Guo, Xiaoyan Cai, Shu Zhang, Tuo Zhang, Dajiang Zhu, Dinggang Shen, Tianming Liu, Xiang Li

#### 2022

- [DeltaNet:Conditional Medical Report Generation for COVID-19 Diagnosis](https://arxiv.org/abs/2211.13229) - Xian Wu, Shuxin Yang, Zhaopeng Qiu, Shen Ge, Yangtian Yan, Xingwang Wu, Yefeng Zheng, S. Kevin Zhou, Li Xiao

#### 2020

- [When Radiology Report Generation Meets Knowledge Graph](https://arxiv.org/abs/2002.08277) - Yixiao Zhang, Xiaosong Wang, Ziyue Xu, Qihang Yu, Alan Yuille, Daguang Xu

### Vision-Language Models for Medical Imaging

#### 2024

- [UIT-DarkCow team at ImageCLEFmedical Caption 2024: Diagnostic Captioning for Radiology Images Efficiency with Transformer Models](https://arxiv.org/abs/2405.17002) - Quan Van Nguyen, Huy Quang Pham, Dan Quang Tran, Thang Kien-Bao Nguyen, Nhat-Hao Nguyen-Dang, Bao-Thien Nguyen-Tat
- [MedRG: Medical Report Grounding with Multi-modal Large Language Model](https://arxiv.org/abs/2404.06798) - Ke Zou, Yang Bai, Zhihao Chen, Yang Zhou, Yidi Chen, Kai Ren, Meng Wang, Xuedong Yuan, Xiaojing Shen, Huazhu Fu
- [DeViDe: Faceted medical knowledge for improved medical vision-language pre-training](https://arxiv.org/abs/2404.03618) - Haozhe Luo, Ziyu Zhou, Corentin Royer, Anjany Sekuboyina, Bjoern Menze
- [Multimodal Healthcare AI: Identifying and Designing Clinically Relevant Vision-Language Applications for Radiology](https://arxiv.org/abs/2402.14252) - Nur Yildirim, et al.
- [MedDr: Diagnosis-Guided Bootstrapping for Large-Scale Medical Vision-Language Learning](https://arxiv.org/abs/2404.15127) - Sunan He, Yuxiang Nie, Zhixuan Chen, Zhiyuan Cai, Hongmei Wang, Shu Yang, Hao Chen
- [CheXagent: Towards a Foundation Model for Chest X-Ray Interpretation](https://arxiv.org/abs/2401.12208) - Zhihong Chen, Maya Varma, Jean-Benoit Delbrouck, Magdalini Paschali, Louis Blankemeier, Dave Van Veen, Jeya Maria Jose Valanarasu, Alaa Youssef, Joseph Paul Cohen, Eduardo Pontes Reis, Emily B. Tsai, Andrew Johnston, Cameron Olsen, Tanishq Mathew Abraham, Sergios Gatidis, Akshay S. Chaudhari, Curtis Langlotz

#### 2023

- [RaDialog: A Large Vision-Language Model for Radiology Report Generation and Conversational Assistance](https://arxiv.org/abs/2311.18681) - Chantal Pellegrini, Ege Özsoy, Benjamin Busam, Nassir Navab, Matthias Keicher
- [IQAGPT: Image Quality Assessment with Vision-language and ChatGPT Models](https://arxiv.org/abs/2312.15663) - Zhihao Chen, Bin Hu, Chuang Niu, Tao Chen, Yuxin Li, Hongming Shan, Ge Wang
- [T3D: Towards 3D Medical Image Understanding through Vision-Language Pre-training](https://arxiv.org/abs/2312.01529) - Che Liu, Cheng Ouyang, Yinda Chen, Cesar César Quilodrán-Casas, Lei Ma, Jie Fu, Yike Guo, Anand Shah, Wenjia Bai, Rossella Arcucci
- [CXR-CLIP: Toward Large Scale Chest X-ray Language-Image Pre-training](https://arxiv.org/abs/2310.13292) - Kihyun You, Jawook Gu, Jiyeon Ham, Beomhee Park, Jiho Kim, Eun Kyoung Hong, Woonhyunk Baek, Byungseok Roh
- [Utilizing Synthetic Data for Medical Vision-Language Pre-training: Bypassing the Need for Real Images](https://arxiv.org/abs/2310.07027) - Che Liu, Anand Shah, Wenjia Bai, Rossella Arcucci
- [XrayGPT: Chest Radiographs Summarization using Medical Vision-Language Models](https://arxiv.org/abs/2306.07971) - Omkar Thawkar, Abdelrahman Shaker, Sahal Shaji Mullappilly, Hisham Cholakkal, Rao Muhammad Anwer, Salman Khan, Jorma Laaksonen, Fahad Shahbaz Khan
- [ConTEXTual Net: A Multimodal Vision-Language Model for Segmentation of Pneumothorax](https://arxiv.org/abs/2303.01615) - Zachary Huemann, Xin Tie, Junjie Hu, Tyler J. Bradshaw

#### 2022

- [RoentGen: Vision-Language Foundation Model for Chest X-ray Generation](https://arxiv.org/abs/2211.12737) - Pierre Chambon, Christian Bluethgen, Jean-Benoit Delbrouck, Rogier Van der Sluijs, Małgorzata Połacin, Juan Manuel Zambrano Chaves, Tanishq Mathew Abraham, Shivanshu Purohit, Curtis P. Langlotz, Akshay Chaudhari
- [Making the Most of Text Semantics to Improve Biomedical Vision--Language Processing](https://arxiv.org/abs/2204.09817) - Benedikt Boecking, Naoto Usuyama, Shruthi Bannur, Daniel C. Castro, Anton Schwaighofer, Stephanie Hyland, Maria Wetscherek, Tristan Naumann, Aditya Nori, Javier Alvarez-Valle, Hoifung Poon, Ozan Oktay

#### 2021

- [Multi-modal Understanding and Generation for Medical Images and Text via Vision-Language Pre-Training](https://arxiv.org/abs/2105.11333) - Jong Hak Moon, Hyungyung Lee, Woncheol Shin, Young-Hak Kim, Edward Choi

### Large Language Models in Radiology

#### 2024

- [Exploring Multilingual Large Language Models for Enhanced TNM classification of Radiology Report in lung cancer staging](https://arxiv.org/abs/2406.06591) - Hidetoshi Matsuo, Mizuho Nishio, Takaaki Matsunaga, Koji Fujimoto, Takamichi Murakami
- [The current status of large language models in summarizing radiology report impressions](https://arxiv.org/abs/2406.02134) - Danqing Hu, Shanyuan Zhang, Qing Liu, Xiaofeng Zhu, Bing Liu
- [Opportunities and challenges in the application of large artificial intelligence models in radiology](https://arxiv.org/abs/2403.16112) - Liangrui Pan, Zhenyu Zhao, Ying Lu, Kewei Tang, Liyong Fu, Qingchun Liang, Shaoliang Peng
- [Is Open-Source There Yet? A Comparative Study on Commercial and Open-Source LLMs in Their Ability to Label Chest X-Ray Reports](https://arxiv.org/abs/2402.12298) - Felix J. Dorfner, Liv Jürgensen, Leonhard Donle, Fares Al Mohamad, Tobias R. Bodenmann, Mason C. Cleveland, Felix Busch, Lisa C. Adams, James Sato, Thomas Schultz, Albert E. Kim, Jameson Merkow, Keno K. Bressem, Christopher P. Bridge

#### 2023

- [Holistic Evaluation of GPT-4V for Biomedical Imaging](https://arxiv.org/abs/2312.05256) - Zhengliang Liu, et al.
- [Exploring the Boundaries of GPT-4 in Radiology](https://arxiv.org/abs/2310.14573) - Qianchu Liu, Stephanie Hyland, Shruthi Bannur, Kenza Bouzid, Daniel C. Castro, Maria Teodora Wetscherek, Robert Tinn, Harshita Sharma, Fernando Pérez-García, Anton Schwaighofer, Pranav Rajpurkar, Sameer Tajdin Khanna, Hoifung Poon, Naoto Usuyama, Anja Thieme, Aditya V. Nori, Matthew P. Lungren, Ozan Oktay, Javier Alvarez-Valle
- [R2GenGPT: Radiology Report Generation with Frozen LLMs](https://arxiv.org/abs/2309.09812) - Zhanyu Wang, Lingqiao Liu, Lei Wang, Luping Zhou
- [Radiology-Llama2: Best-in-Class Large Language Model for Radiology](https://arxiv.org/abs/2309.06419) - Zhengliang Liu, Yiwei Li, Peng Shu, Aoxiao Zhong, Longtao Yang, Chao Ju, Zihao Wu, Chong Ma, Jie Luo, Cheng Chen, Sekeun Kim, Jiang Hu, Haixing Dai, Lin Zhao, Dajiang Zhu, Jun Liu, Wei Liu, Dinggang Shen, Tianming Liu, Quanzheng Li, Xiang Li
- [General-Purpose vs. Domain-Adapted Large Language Models for Extraction of Structured Data from Chest Radiology Reports](https://arxiv.org/abs/2311.17213) - Ali H. Dhanaliwala, Rikhiya Ghosh, Sanjeev Kumar Karn, Poikavila Ullaskrishnan, Oladimeji Farri, Dorin Comaniciu, Charles E. Kahn
- [Evaluation of GPT-4 for chest X-ray impression generation: A reader study on performance and perception](https://arxiv.org/abs/2311.06815) - Sebastian Ziegelmayer, Alexander W. Marka, Nicolas Lenhart, Nadja Nehls, Stefan Reischl, Felix Harder, Andreas Sauter, Marcus Makowski, Markus Graf, Joshua Gawlitza
- [ChatRadio-Valuer: A Chat Large Language Model for Generalizable Radiology Report Generation Based on Multi-institution and Multi-system Data](https://arxiv.org/abs/2310.05242) - Tianyang Zhong, et al.
- [CohortGPT: An Enhanced GPT for Participant Recruitment in Clinical Study](https://arxiv.org/abs/2307.11346) - Zihan Guan, Zihao Wu, Zhengliang Liu, Dufan Wu, Hui Ren, Quanzheng Li, Xiang Li, Ninghao Liu

### Multimodal Learning for Medical Image Analysis

#### 2024

- [Language Augmentation in CLIP for Improved Anatomy Detection on Multi-modal Medical Images](https://arxiv.org/abs/2405.20735) - Mansi Kakkar, Dattesh Shanbhag, Chandan Aladahalli, Gurunath Reddy M
- [Advancing Multimodal Medical Capabilities of Gemini](https://arxiv.org/abs/2405.03162) - Lin Yang, et al.
- [Improving Medical Multi-modal Contrastive Learning with Expert Annotations](https://arxiv.org/abs/2403.10153) - Yogesh Kumar, Pekka Marttinen
- [Towards a clinically accessible radiology foundation model: open-access and lightweight, with automated evaluation](https://arxiv.org/abs/2403.08002) - Juan Manuel, et al.

#### 2023

- [Effectively Fine-tune to Improve Large Multimodal Models for Radiology Report Generation](https://arxiv.org/abs/2312.01504) - Yuzhe Lu, Sungmin Hong, Yash Shah, Panpan Xu
- [Beyond Images: An Integrative Multi-modal Approach to Chest X-Ray Report Generation](https://arxiv.org/abs/2311.11090) - Nurbanu Aksoy, Serge Sharoff, Selcuk Baser, Nishant Ravikumar, Alejandro F Frangi
- [A Systematic Evaluation of GPT-4V's Multimodal Capability for Medical Image Analysis](https://arxiv.org/abs/2310.20381) - Yingshu Li, Yunyi Liu, Zhanyu Wang, Xinyu Liang, Lei Wang, Lingqiao Liu, Leyang Cui, Zhaopeng Tu, Longyue Wang, Luping Zhou
- [Cross-Modal Conceptualization in Bottleneck Models](https://arxiv.org/abs/2310.14805) - Danis Alukaev, Semen Kiselev, Ilya Pershin, Bulat Ibragimov, Vladimir Ivanov, Alexey Kornaev, Ivan Titov
- [Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data](https://arxiv.org/abs/2308.02463) - Chaoyi Wu, Xiaoman Zhang, Ya Zhang, Yanfeng Wang, Weidi Xie

#### 2022

- [Using Multi-modal Data for Improving Generalizability and Explainability of Disease Classification in Radiology](https://arxiv.org/abs/2207.14781) - Pranav Agnihotri, Sara Ketabi, Khashayar (Ernest)Namdar, Farzad Khalvati

#### 2020

- [Creation and Validation of a Chest X-Ray Dataset with Eye-tracking and Report Dictation for AI Development](https://arxiv.org/abs/2009.07386) - Alexandros Karargyris, Satyananda Kashyap, Ismini Lourentzou, Joy Wu, Arjun Sharma, Matthew Tong, Shafiq Abedin, David Beymer, Vandana Mukherjee, Elizabeth A Krupinski, Mehdi Moradi

### Evaluation Metrics and Benchmarking for AI in Radiology

#### 2024

- [FineRadScore: A Radiology Report Line-by-Line Evaluation Technique Generating Corrections with Severity Scores](https://arxiv.org/abs/2405.20613) - Alyssa Huang, Oishi Banerjee, Kay Wu, Eduardo Pontes Reis, Pranav Rajpurkar
- [GREEN: Generative Radiology Report Evaluation and Error Notation](https://arxiv.org/abs/2405.03595) - Sophie Ostmeier, Justin Xu, Zhihong Chen, Maya Varma, Louis Blankemeier, Christian Bluethgen, Arne Edward Michalson, Michael Moseley, Curtis Langlotz, Akshay S Chaudhari, Jean-Benoit Delbrouck
- [LLM-RadJudge: Achieving Radiologist-Level Evaluation for X-Ray Report Generation](https://arxiv.org/abs/2404.00998) - Zilong Wang, Xufang Luo, Xinyang Jiang, Dongsheng Li, Lili Qiu

#### 2023

- [Radiology-Aware Model-Based Evaluation Metric for Report Generation](https://arxiv.org/abs/2311.16764) - Amos Calamida, Farhad Nooralahzadeh, Morteza Rohanian, Koji Fujimoto, Mizuho Nishio, Michael Krauthammer

### Medical Image Synthesis and Augmentation

#### 2024

- [Shadow and Light: Digitally Reconstructed Radiographs for Disease Classification](https://arxiv.org/abs/2406.03688) - Benjamin Hou, Qingqing Zhu, Tejas Sudarshan Mathai, Qiao Jin, Zhiyong Lu, Ronald M. Summers
- [PairAug: What Can Augmented Image-Text Pairs Do for Radiology?](https://arxiv.org/abs/2404.04960) - Yutong Xie, Qi Chen, Sinuo Wang, Minh-Son To, Iris Lee, Ee Win Khoo, Kerolos Hendy, Daniel Koh, Yong Xia, Qi Wu

#### 2023

- [Cascaded Latent Diffusion Models for High-Resolution Chest X-ray Synthesis](https://arxiv.org/abs/2303.11224) - Tobias Weber, Michael Ingrisch, Bernd Bischl, David Rügamer

#### 2022

- [medigan: a Python library of pretrained generative models for medical image synthesis](https://arxiv.org/abs/2209.14472) - Richard Osuala, Grzegorz Skorupko, Noussair Lazrak, Lidia Garrucho, Eloy García, Smriti Joshi, Socayna Jouide, Michael Rutherford, Fred Prior, Kaisar Kushibar, Oliver Diaz, Karim Lekadir


### AI for Specific Radiological Tasks

#### 2024

- [Towards a Comprehensive, Efficient and Promptable Anatomic Structure Segmentation Model using 3D Whole-body CT Scans](https://arxiv.org/abs/2403.15063) - Heng Guo, Jianfeng Zhang, Jiaxing Huang, Tony C. W. Mok, Dazhou Guo, Ke Yan, Le Lu, Dakai Jin, Minfeng Xu

#### 2019

- [MULAN: Multitask Universal Lesion Analysis Network for Joint Lesion Detection, Tagging, and Segmentation](https://arxiv.org/abs/1908.04373) - Ke Yan, Youbao Tang, Yifan Peng, Veit Sandfort, Mohammadhadi Bagheri, Zhiyong Lu, Ronald M. Summers

#### 2018

- [Attention-Guided Curriculum Learning for Weakly Supervised Classification and Localization of Thoracic Diseases on Chest Radiographs](https://arxiv.org/abs/1807.07532) - Yuxing Tang, Xiaosong Wang, Adam P. Harrison, Le Lu, Jing Xiao, Ronald M. Summers

### AI-Assisted Diagnosis and Decision Support

#### 2022

- [Weakly Supervised Learning with Automated Labels from Radiology Reports for Glioma Change Detection](https://arxiv.org/abs/2210.09698) - Tommaso Di Noto, Meritxell Bach Cuadra, Chirine Atat, Eduardo Gamito Teiga, Monika Hegi, Andreas Hottinger, Patric Hagmann, Jonas Richiardi
- [Learning to diagnose common thorax diseases on chest radiographs from radiology reports in Vietnamese](https://arxiv.org/abs/2209.04794) - Thao T.B. Nguyen, Tam M. Vo, Thang V. Nguyen, Hieu H. Pham, Ha Q. Nguyen
- [Anatomy-Guided Weakly-Supervised Abnormality Localization in Chest X-rays](https://arxiv.org/abs/2206.12704) - Ke Yu, Shantanu Ghosh, Zhexiong Liu, Christopher Deible, Kayhan Batmanghelich
- [Breaking with Fixed Set Pathology Recognition through Report-Guided Contrastive Training](https://arxiv.org/abs/2205.07139) - Constantin Seibold, Simon Reiß, M. Saquib Sarfraz, Rainer Stiefelhagen, Jens Kleesiek

#### 2020

- [Deep-LIBRA: Artificial intelligence method for robust quantification of breast density with independent validation in breast cancer risk assessment](https://arxiv.org/abs/2011.08001) - Omid Haji Maghsoudi, Aimilia Gastounioti, Christopher Scott, Lauren Pantalone, Fang-Fang Wu, Eric A. Cohen, Stacey Winham, Emily F. Conant, Celine Vachon, Despina Kontos

#### 2018

- [Accurate Weakly Supervised Deep Lesion Segmentation on CT Scans: Self-Paced 3D Mask Generation from RECIST](https://arxiv.org/abs/1801.08614) - Jinzheng Cai, Youbao Tang, Le Lu, Adam P. Harrison, Ke Yan, Jing Xiao, Lin Yang, Ronald M. Summers

#### 2017

- [Spatial Aggregation of Holistically-Nested Convolutional Neural Networks for Automated Pancreas Localization and Segmentation](https://arxiv.org/abs/1702.00045) - Holger R. Roth, Le Lu, Nathan Lay, Adam P. Harrison, Amal Farag, Andrew Sohn, Ronald M. Summers


### Natural Language Processing for Clinical Reports

#### 2024

- [Leveraging Prompt-Learning for Structured Information Extraction from Crohn's Disease Radiology Reports in a Low-Resource Language](https://arxiv.org/abs/2405.01682) - Liam Hazan, Gili Focht, Naama Gavrielov, Roi Reichart, Talar Hagopian, Mary-Louise C. Greer, Ruth Cytter Kuint, Dan Turner, Moti Freiman

#### 2023

- [Parameter-Efficient Methods for Metastases Detection from Clinical Notes](https://arxiv.org/abs/2310.18472) - Maede Ashofteh Barabadi, Xiaodan Zhu, Wai Yip Chan, Amber L. Simpson, Richard K.G. Do
- ["Nothing Abnormal": Disambiguating Medical Reports via Contrastive Knowledge Infusion](https://arxiv.org/abs/2305.08300) - Zexue He, An Yan, Amilcare Gentili, Julian McAuley, Chun-Nan Hsu

#### 2021

- [RadGraph: Extracting Clinical Entities and Relations from Radiology Reports](https://arxiv.org/abs/2106.14463) - Saahil Jain, Ashwin Agrawal, Adriel Saporta, Steven QH Truong, Du Nguyen Duong, Tan Bui, Pierre Chambon, Yuhao Zhang, Matthew P. Lungren, Andrew Y. Ng, Curtis P. Langlotz, Pranav Rajpurkar

#### 2017

- [NegBio: a high-performance tool for negation and uncertainty detection in radiology reports](https://arxiv.org/abs/1712.05898) - Yifan Peng, Xiaosong Wang, Le Lu, Mohammadhadi Bagheri, Ronald Summers, Zhiyong Lu
