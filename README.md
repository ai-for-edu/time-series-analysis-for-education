# Time Series Analysis for Education
This repo is a collection of related papers and resources for the paper **Time Series Analysis for Education: Methods, Applications, and Future Directions**, which is the first to comprehensively review time series analysis in educational contexts, covering mainstream methods such as forecasting, classification, clustering, and anomaly detection to the best of our knowledge. We will regularly collect and update the latest resources in this repo.

<p align="center">
<img src="https://github.com/ai-for-edu/time-series-analysis-for-education/blob/main/img1.png" height = "350" alt="" align=center />
<p style="text-align: left;">
<b>Fig. 1</b> The hierarchical categorization of the key components of time series analysis in education.
</p>

## Survey paper
**Time Series Analysis for Education: Methods, Applications, and Future Directions** 
<br>
Authors: Shengzhong Mao, Chaoli Zhang, Yichi Song, Jindong Wang, Xiao-Jun Zeng, Zenglin Xu (IEEE Senior Member), and Qingsong Wen (IEEE Senior Member)

<p align="center">
<img src="https://github.com/ai-for-edu/time-series-analysis-for-education/blob/main/img2.png" height = "350" alt="" align=center />
<p style="text-align: left;">
<b>Fig. 2</b> Comparison of our survey with existing educational surveys (last 5 years).
</p>


<p align="center">
<img src="https://github.com/ai-for-edu/time-series-analysis-for-education/blob/main/img3.png" height = "350" alt="" align=center />
<p style="text-align: left;">
<b>Fig. 3</b> The overview of time series analysis in educational contexts. 
</p>

## Table of Contents
- [Educational data mining](#Educational data mining)
  * [Educational data mining surveys](#Educational data mining surveys)
  * [Data mining vs. Learning analytics](#Data mining vs. Learning analytics)
  * [Multimodal learning | Data fusion](#Multimodal learning | Data fusion)
 
- [Educational Tasks and Applications](#Educational Tasks and Applications)
	* [Acedemic performance prediction](#Academic performance)
	* [Learner behaviour analysis](#Learner behaviour analysis)
	* [Anomaly/outlier detection](#Anomaly/outlier detection)

- [Public educational datasets](#Public educational datasets)
	* [UCI ML Repository](#UCI ML Repository)
	* [Mendeley Data Repository](#Mendeley Data Repository)
	* [Harvard Dataverse Repository](#Harvard Dataverse Repository)
	* [Educational Competitions](#Educational Competitions)
	* [Miscellaneous Sources](#Miscellaneous Sources)

- [Educational venues](#Educational venues)
  * [Conferences & Workshops](#Conferences & Workshops)
  * [Journals](#Journals)

## Educational data mining
### Educational data mining surveys
* 2024: A Comprehensive Survey on Deep Learning Techniques in Educational Data Mining. [[Paper]](https://arxiv.org/abs/2309.04761)
* 2023: Classification technique and its combination with clustering and association rule mining in educational data mining—A survey. [[Paper]](https://doi.org/10.1016/j.engappai.2023.106071)
* 2023: Handling Big Data in Education: A Review of Educational Data Mining Techniques for Specific Educational Problems. [[Paper]](https://doi.org/10.5772/acrt.17)
* 2022: Educational data mining: A bibliometric analysis of an emerging field. [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9737480)
* 2022: Educational Data Mining: A Comprehensive Review and Future Challenges. [[Paper]](https://iopscience.iop.org/article/10.1149/10701.16129ecst)
* 2021: Educational Data Mining: A Review. [[Paper]](https://iopscience.iop.org/article/10.1088/1742-6596/1950/1/012022)
* 2020: Big Educational Data & Analytics: Survey, Architecture and Challenges. [[Paper]](https://ieeexplore.ieee.org/document/9093868)
* 2020: Educational data mining: a systematic review of research and emerging trends. [[Paper]](https://www.emerald.com/insight/content/doi/10.1108/IDD-09-2019-0070/full/html)
* 2020: Educational data mining and learning analytics: An updated survey. [[Paper]](https://doi.org/10.1002/widm.1355)
* 2019: A systematic review of deep learning approaches to educational data mining. [[Paper]](https://doi.org/10.1155/2019/1306039)
* 2019: A systematic review of deep learning approaches to educational data mining. [[Paper]](https://go.gale.com/ps/i.do?id=GALE%7CA613619209&sid=googleScholar&v=2.1&it=r&linkaccess=abs&issn=10762787&p=AONE&sw=w)
* 2018: Educational data mining applications and tasks: A survey of the last 10 years. [[Paper]](https://link.springer.com/article/10.1007/s10639-017-9616-z)

### Data mining vs. Learning analytics
* 2024: Educational data mining and learning analytics: A review of educational management in e-learning. [[Paper]](https://www.emerald.com/insight/content/doi/10.1108/IDD-10-2022-0099/full/html)
* 2024: Reviewing the differences between learning analytics and educational data mining: Towards educational data science. [[Paper]](https://doi.org/10.1016/j.chb.2024.108155)
* 2023: Educational data mining versus learning analytics: A review of publications from 2015 to 2019. [[Paper]](https://doi.org/10.1080/10494820.2021.1943689)
* 2021: Educational Data Mining versus Learning Analytics: A Review of Publications From 2015 to 2019. [[Paper]](https://www.tandfonline.com/doi/full/10.1080/10494820.2021.1943689)
* 2021: Comparison of learning analytics and educational data mining: A topic modeling approach. [[Paper]](https://doi.org/10.1016/j.caeai.2021.100016)
* 2020: Educational data mining and learning analytics: An updated survey. [[Paper]](https://doi.org/10.1002/widm.1355)
* 2019: Educational data mining and learning analytics for 21st century higher education: A review and synthesis. [[Paper]](https://doi.org/10.1016/j.tele.2019.01.007)

### Multimodal learning | Data fusion
* 2022: A review on data fusion in multimodal learning analytics
and educational data mining. [[Paper]](https://wires.onlinelibrary.wiley.com/doi/full/10.1002/widm.1458)
* 2022: Multimodal educational data fusion for students' mental health detection. [[Paper]](https://ieeexplore.ieee.org/iel7/6287639/6514899/09810926.pdf)
* 2021: Review on publicly available datasets for educational data mining. [[Paper]](https://wires.onlinelibrary.wiley.com/doi/epdf/10.1002/widm.1403)
* 2020: Multimodal data fusion in learning analytics: A systematic review. [[Paper]](https://www.mdpi.com/1424-8220/20/23/6856)
* 2019: Building pipelines for educational data using AI and multimodal analytics: A “grey‐box” approach. [[Paper]](https://bera-journals.onlinelibrary.wiley.com/doi/pdf/10.1111/bjet.12854)

## Educational Tasks and Applications
### Academic performance prediction
* 2023: Prediction of student academic performance based on their emotional wellbeing and interaction on various e-learning platforms. [[Paper]](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/article/10.1007/s10639-022-11573-9&casa_token=RUjbp45jct8AAAAA:2AHyO956tiPqzMjDaG5Pb0zx2nKBuhVY0wCgVAA-LITHWBIUmIxZdcYioWiQ09aNukfSUH6g08-bacrklg)
* 2022: Educational data mining: prediction of students' academic performance using machine learning algorithms. [[Paper]](https://link.springer.com/article/10.1186/s40561-022-00192-z)
* 2022: Educational Data Mining for Student Performance Prediction: A Systematic Literature Review (2015-2021).[[Paper]](https://online-journals.org/index.php/i-jet/article/view/27685)
* 2022: Educational data mining to predict students' academic performance: A survey study. [[Paper]](https://link.springer.com/article/10.1007/s10639-022-11152-y)
* 2021: Contributions of machine learning models towards student academic performance prediction: a systematic review. [[Paper]](https://www.mdpi.com/2076-3417/11/21/10007)
* 2021: A systematic literature review of student'performance prediction using machine learning techniques. [[Paper]](https://www.mdpi.com/2227-7102/11/9/552)
* 2021: Educational Data Mining Techniques for Student Performance Prediction: Method Review and Comparison Analysis. [[Paper]](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2021.698490/full)
* 2020: Predicting student performance using data mining and learning analytics techniques: A systematic literature review. [[Paper]](https://www.mdpi.com/2076-3417/11/1/237)
* 2019: Students' academic performance and dropout predictions: A review. [[Paper]](https://www.academia.edu/download/90788716/3-Ameen-et-al-CReady-Vol42-3.pdf)

### Learner behaviour analysis
* 2024: Research on learning behavior patterns from the perspective of educational data mining: Evaluation, prediction and visualization. [[Paper]](https://doi.org/10.1016/j.eswa.2023.121555)
* 2023: Learning analytics on student engagement to enhance students' learning performance: A systematic review. [[Paper]](https://www.mdpi.com/2071-1050/15/10/7849)
* 2023: Dynamic interaction between student learning behaviour and learning environment: Meta-analysis of student engagement and its influencing factors. [[Paper]](https://www.mdpi.com/2076-328X/13/1/59)
* 2022: Predicting students' performance in e-learning using learning process and behaviour data. [[Paper]](https://www.nature.com/articles/s41598-021-03867-8)
* 2022: Learning analytics in online learning environment: A systematic review on the focuses and the types of student-related analytics data. [[Paper]](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/article/10.1007/s10758-021-09541-2&casa_token=YXmqo3b773AAAAAA:GaZl1cMTCH8tkoIxDPktvTl-BqGVBKlacxkR9Rybs8LgImlBplo9LvHJa6orjNXZLxC_SqeZWlIUqlS1YQ)
* 2021: Impact of learner's characteristics and learning behaviour on learning performance during a fully online course. [[Paper]](https://link.springer.com/chapter/10.1007/978-981-16-6104-4_2)
* 2021: Fostering student engagement with motivating teaching: An observation study of teacher and student behaviours. [[Paper]](https://www.tandfonline.com/doi/abs/10.1080/02671522.2020.1767184)
* 2021: [HTML] Synthesis of student engagement with digital technologies: a systematic review of the literature. [[Paper]](https://link.springer.com/article/10.1186/s41239-021-00270-1)
* 2020: Utilizing Student Time Series Behaviour in Learning Management Systems for Early Prediction of Course Performance. [[Paper]](https://eric.ed.gov/?id=EJ1273765)

### Anomaly/outlier detection
* 2024: Anomaly detection in the course evaluation process: a learning analytics–based approach. [[Paper]](https://www.emerald.com/insight/content/doi/10.1108/ITSE-09-2022-0124/full/html)
* 2023: Anomaly Detection in the Course Evaluation Process. [[Paper]](https://link.springer.com/chapter/10.1007/978-981-19-7892-0_8)
* 2023: Context-aware analysis of group submissions for group anomaly detection and performance prediction. [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26892)
* 2022: Educational Anomaly Analytics: Features, Methods, and Challenges. [[Paper]](https://www.frontiersin.org/journals/big-data/articles/10.3389/fdata.2021.811840/full)
* 2022: Data Processing Model of Students' Evaluation of Teaching Based on Outlier Detection. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9829518/)
* 2022: An introduction to statistical techniques used for detecting anomaly in test results. [[Paper]](https://www.tandfonline.com/doi/abs/10.1080/02671522.2020.1812108)
* 2021: Early Detecting the At-risk Students in Online Courses Based on Their Behavior Sequences. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-72802-1_2)
* 2021: Anomaly detection for early warning in object-oriented programming course. [[Paper]](https://ieeexplore.ieee.org/iel7/9678505/9678390/09678677.pdf)
* 2021: Unsupervised anomaly detection with distillated teacher-student network ensemble. [[Paper]](https://www.mdpi.com/1099-4300/23/2/201)
* 2020: Improving affect detection in game-based learning with multimodal data fusion. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-52237-7_19)

## Public educational datasets
### UCI ML Repository
* **Student Performance Dataset**: 649 samples, 30 features, focusing on estimating student end-of-term scores. [[Link]](https://archive.ics.uci.edu/dataset/320/student+performance)
* **User Knowledge Modeling Dataset**: 403 samples, 5 features, suitable for classification and clustering of learners' knowledge levels. [[Link]](https://archive.ics.uci.edu/dataset/257/user+knowledge+modeling)
* **Educational Process Mining Dataset**: 230,318 instances, 13 features, supports forecasting, classification, and clustering. [[Link]](https://archive.ics.uci.edu/dataset/346/educational+process+mining+epm+a+learning+analytics+data+set)
* **Open University Learning Analytics Dataset (OULAD)**: Data for seven modules, used for identifying at-risk students and predicting engagement. [[Link]](https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset)
* **Student Academics Performance**: 300 records, 24 features, primarily used for predicting student performance. [[Link]](https://archive.ics.uci.edu/dataset/467/student+academics+performance)

### Mendeley Data Repository
* **KEEL Data**: Datasets for knowledge discovery compatible with KEEL software. [[Link]](https://data.mendeley.com/datasets/py4hhv3rb8/1)
* **MOOC Lectures Dataset**: Word embeddings and topic vectors from 12,032 Coursera video lectures. [[Link]](https://data.mendeley.com/datasets/xknjp8pxbj/1)
* **Flip Teaching in Physics Lab Data**: Performance data of 1,233 engineering students in Physics and Electricity courses. [[Link]](https://data.mendeley.com/datasets/68mt8gms4j/3)
* **Outcome-Based Education (OBE) Dataset**: 34.65 million entries assessing outcome-based education. [[Link]](https://data.mendeley.com/datasets/9zkfwdm8xf/1)
* **Influencing Factors of Teacher Burnout**: Survey responses from 876 teachers on self-concept, efficacy, and burnout. [[Link]](https://data.mendeley.com/datasets/6jmv43nffk/2)
* **Academic Performance Evolution Data**: Performance data of 12,411 engineering students across 44 features. [[Link]](https://data.mendeley.com/datasets/83tcx8psxv/1)


### Harvard Dataverse Repository
* **HarvardX Person-Course**: 338,223 entries with 20 features for analyzing user progress and predicting course outcomes. [[Link]](https://doi.org/10.7910/DVN/26147)
* **MOOC-Ed Network Dataset**: Designed to examine dropout rates and self-regulated learning behaviors in MOOCs. [[Link]](https://doi.org/10.7910/DVN/ZZH3UB)
* **CAMEO Dataset**: Information on student activities in MITx and HarvardX courses, used to study cheating through multiple accounts. [[Link]](https://doi.org/10.7910/DVN/3UKVOR)
* **Canvas Network Open Courses**: 325,000 records with 25 features detailing activities in 238 courses, often used for clustering tasks. [[Link]](https://doi.org/10.7910/DVN/1XORAL)
* **Video Game Learning Analytics**: Data from 331 students in preschool settings, focusing on phonological awareness and literacy. [[Link]](https://doi.org/10.7910/DVN/V7E9XD)
* **Interdisciplinary Student Dataset**: 807 observations with 29 variables, covering demographic data of 543 undergraduates and 246 graduates. [[Link]](https://doi.org/10.7910/DVN/M07HQ7)


### Educational Competitions
* **The KDD Cup**: Launched in 2010, this competition focuses on predicting student performance using tutoring system logs. The 2015 edition centered on forecasting dropouts in XuetangX MOOCs. [[Link]](https://pslcdatashop.web.cmu.edu/KDDCup/)
* **The NAEP Competition**: The 2017 edition used deidentified click-stream data from middle school students using ASSISTments, while the 2019 edition focused on predicting student activities based on early test data. [[Link]](https://sites.google.com/view/assistmentsdatamining/home)
* **EdNet Dataset**: Collected by Santa, an AI tutoring service in Korea, this hierarchical dataset includes four sub-datasets focused on logged actions from 780,000 users. [[Link]](https://github.com/riiid/ednet)
* **Riiid AIEd Challenge 2020**: A Kaggle competition dataset with 418 lectures, 170 questions, and actions from 393,656 users, aimed at developing knowledge tracing models. [[Link]](https://www.kaggle.com/c/riiid-test-answer-prediction/)

### Miscellaneous Sources
* **DataShop@CMU**: Repository with 40 datasets offering secure storage and analytical tools for learning science research. [[Link]](https://pslcdatashop.web.cmu.edu/)
* **NUS Multisensor Presentation**: Time series, video, and audio data from 51 individuals, used for feedback on oral presentation skills. [[Link]](https://scholarbank.nus.edu.sg/handle/10635/137261)
* **Learn Moodle August 2016**: An anonymized dataset capturing user activities from the Learn Moodle MOOC, including badges, course completions, and event logs. [[Link]](http://research.moodle.net/158/)
* **MUTLA Dataset**: Multimodal data for analyzing teacher-student interactions, including brainwave data and webcam footage. [[Link]](https://github.com/RyanH98/SAILData)
* **Junyi Academy Dataset**: Student interaction data with the Junyi Academy platform, detailing study durations and response accuracy. [[Link]](https://www.kaggle.com/datasets/junyiacademy/learning-activity-public-dataset-by-junyi-academy)

## Educational venues
### Conferences & Workshops
### Journals
