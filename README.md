# Introduction of my Projects

## Contact Me!
![My figure](./figures/figure_me.jpg)
- Xinyao Tian ( Richard Tian )
- mobile number(AU): (+61) 0457 512 404
- mobile number(CH): (+86) 13311369059
- Email: richardtian1024@gmail.com || leontian1024@gmail.com
- CSDN technical Blog: https://blog.csdn.net/weixin_38070561
- Zhihu technical Blog: https://www.zhihu.com/people/winchester-26/activities
- Github: https://github.com/XinyaoTian


# List of My Projects


## "DataSciCamp" A website dedicated for Data Scientists - More than 1.5K stars in Github!
(Cooperate with a Doctor from Beijing Normal University)

### Keywords
>Project Keywords: Web Design & develop, Data Science, micro service architecture(Service Mesh)

>Technical Keywords: Flask, Docker, Kubernetes(K8S), Istio, IaaS

### A Brief Introduction of the Project

The landing product of this project is a web application for college teachers and students to obtain and share the latest competition information and share solutions.

The innovation of this project focuses on the improvement of traditional Web projects using a new software architecture called "micro service architecture".


### Mainly Description of the Project

The project was established on 29th, July, 2019.
As of 20th, September, 2019, my team and I have completed the design and implementation of most of the features of the website using the microservices architecture.
Using the microservices architecture, we not only greatly simplified the deployment and operation of the website, but also greatly reduced the cost of collaboration and greatly improved communication efficiency.
The final version of the project, "DataSciCamp 1.0", is expected to be officially launched on 1st, October, 2019. Teachers and students are welcome to enter the new version and have a new user experience.

### Project Outcomes

DataSciCamp Main Page - Older version
![DataSciCamp Main Page - Older version](./figures/datascicamp/frontPage.png)

DataSciCamp Main Page - the Newest version
![DataSciCamp Main Page - the Newest version](./figures/datascicamp/login.png)

DataSciCamp - Main Contributors List
![DataSciCamp - Main Contributors List](./figures/datascicamp/about-us.png)

### Project Achievements

This project is an open source project on Github. To date, we have received more than 1,500 Stars and enthusiastic feedback from countless teachers, students and software developers.

### Project References

[DataSciCamp Website (the Newest version)](https://www.datascicamp.com)

[DataSciCamp Website (Older version)](https://iphysresearch.github.io/DataSciComp?sub=PF,AC,DM,CV,NLP,RL,SP)

[DataSciCamp Github Repository (Older version)](https://github.com/iphysresearch/DataSciComp)


## The Assisted Diagnosis IT System of Periodontal Disease 
(Cooperate with a Doctor from Peking University)

### Keywords
>Project keywords: BigData, Machine Learning, Information System, Web application

>Technical keywords: Zeppelin, Spark, pySpark, Flask, Linux, DevOps

### A Brief Introduction of the Project

In recent years, cross-domain research on big data has been enthusiastically sought after. 
The project was initiated by a medical doctor who studied periodontal disease at Peking University and provided more than 1.7 million (desensitized, 27 dimensions as total) real periodontal disease cases collected by diagnosis in the clinical treatments during the past 20 years.
 
The team I led was responsible for the training modeling part of machine learning (including data cleaning, preprocessing, visualization, machine learning modeling, model tuning and validation, model export and persistence). Model building work and development of a Web system prototype with the ability to "enter new patient data and predict the severity of periodontal disease."

### Mainly Description of the Project

In terms of technical selection, I chose Zeppelin as the model training platform. With the underlying Spark and pyspark tool libraries, I could achieve excellent visualization and real-time communication and collaboration with the doctor. 
Almost every time I run a model, I could immediately use Zeppelin to report the results of grid search cross-validation to the doctor online. This frequent “report-improvement” mode could detect problems in time and make changes immediately.

In terms of Web services, since it is a demo version, it has low performance requirements and clear requirements. Therefore, I chose the Python-based Flask framework, which is easy to use and speeds up the development process. 
The Web service implements the "new-value prediction" function by calling the model trained on hdfs through pyspark.

### Project Outcomes

Design of the System Architecture
![Design of the System Architecture](./figures/pku_dentist/arch_design.png)

Project Show - the input web page of patients' info
![Project Show - the input web page of patients' info](./figures/pku_dentist/web_input.png)

Project Show - the web page of predicted results by the ML models
![Project Show - the web page of predicted results by the ML models](./figures/pku_dentist/web_result.png)

### Project Achievements

After the completion of the project, the doctoral and company leaders highly praised my work; the demo version of the Web service I developed was favored by the professors of the expert group during the defense. One professor even entered the values of the dental site many times. Comparing the predicted results with their actual clinical experience, the professor found that there is only a slight discrepancy, but the system's diagnosis time is only 5 seconds, which is only one percent of the time spent on the traditional diagnostic process, so it has a strong impact on the system and the machine learning model. The professor was really interested about my models and system.

As the person in charge of this project, I am also honored to be one of the authors of the doctoral thesis. The paper has been submitted to a top medical journal in China and is expected to be published next year.

### Project References
[Source Code of web application part](https://github.com/XinyaoTian/dentist_demo)

[Project Delivery PPT (in Chinese) ](https://github.com/XinyaoTian/project_introduction/blob/master/ppt/pku_dentist/%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%AE%9E%E8%B7%B5%E8%AF%BE%E7%A8%8B%E5%B1%95%E7%A4%BA%E7%89%99%E5%91%A8%E7%97%85%E6%B2%BB%E7%96%97%E6%96%B9%E6%A1%88%E7%96%97%E6%95%88%E9%A2%84%E6%B5%8B.pptx?raw=true)

[Internship Certification in English](./materials/internship_wedata.pdf)



## Research Report: A Road Map to a Top Data-driven enterprise of the Year 2018
(Cooperate with the Institute of Data Science, Tsinghua University)

### Keywords

>Project Keywords: Data Analysing, Web Crawler, Data Visualization

>Technical Keywords: Scrapy, Pandas, Matplotlib, Hdfs, MongoDB

### A Brief Introduction of the Project

The project and its conference were hosted by the Institute of Data Science, Tsinghua University and co-organized by Big Data Digest. The team consists of the following four teams: the “crawler team” responsible for obtaining data, the “analysis team” responsible for analyzing the data, the author of writing articles and interviewing the “media team” of the industry’s big cattle and responsible for layout design and printing. And the "design team" of the conference. The total members of teams is up to dozens.

### Mainly Description of the Project

In this project, I also served as the main person in charge of the “Crawler Team” and the main person in charge of the “Analysis Team”. In the “Crawler Team”, since the total number of the team was as many as 13 people, in order to unify the data format and avoided excessive data confusion, I mainly undertook the work of drafting the crawler data acquisition dimension and specification to standardize the data format. To make data structure meet the release requirements; at the same time, I was also solely responsible for obtaining job information about the data positions on the Zhilian Recruitment website. In the “Analysis Team”, combined with the acquired data, I was responsible for selecting the analysis tools (using the Pandas tool library and self-packaging jieba for the team members to use quickly), organizing and coordinating the members of the analysis team, and drafting Which dimensions need to be analyzed and the purpose of the analysis is clear; at the same time, I also meet with the members of the “Design Team” several times to discuss the feasibility of the design plan and to clarify the output format of the analysis results of the “Analysis Team”.

### Project Outcomes

Cover Page of the Report
![Cover Page of the Report](./figures/tsinghua_data/cover.png)

Data Analysing - in Public View: Who will be responsible for the moral problems with AI and Big Data?
![in Public View: Who will be responsible for the moral problems with AI and Big Data?](./figures/tsinghua_data/barchart_1.png)

Data Analysing - Comparison of the main demand of skills between Chinese universities and companies
![Comparison of the main demand of skills between Chinese universities and companies](./figures/tsinghua_data/wordPic.png)

### Project Achievements

With the efforts of all the members of the team for three consecutive weeks, the "A Road Map to a Top Data-driven enterprise of the Year 2018" was successfully released on 26th, Sep., 2018 in the lecture hall of the the Institute of Data Science, Tsinghua University. The atmosphere of the conference was warm. After the release of this report, A number of technological media immediately reprinted on the same day or the next day; it is rare for the public media of the technology circle to be so "stained" by the same report.

### Project References

[Our report on Big Data Digest](https://mp.weixin.qq.com/s/FSgPY1Q0qBtL8bJQ1GYb-A)

[The Research Report Downloading link](https://t.cj.sina.com.cn/articles/view/6105753431/16bee675701900bt98)

ps: If you're interested in content of the report, please google the keyword "2018 年度顶级数据团队建设全景报告"(in Chinese).
There are many Chinese medias reported our research.


## The Online Factory Management System 
(for small & medium factories to manage their employees info and devices data)

### Keywords
>Project keywords: Web Application, Information System, Enterprise Software, Service Mesh

>Technical keywords: Flask, Docker, Kubernetes(K8S), Istio, PostgreSQL, MongoDB

### A Brief Introduction of the Project

This management system is developed for some small-scaled factories.
The main purpose of this system is to help the factories manage their employees, store & share enterprise data and also analyse them.
Based on the micro service architecture (which we also called 'ServiceMesh' now), each module of the whole system is running in containers.
As a result, the architecture of the system is extremely clear and the whole system is easy to iteration, highly cohesion and totally decoupling.

### Mainly Description of the Project

When developing this management system, we had a five-members team and I was the leader of the team.
As a software engineer, I deeply knew the importance of understanding the real demands of our system users.
Hence, in the first fortnight of the iteration cycle, all of team members went to the factory and worked with the workers all the days
to totally realize the situation of the factory and tried to find out what was the real demands.

Then, we tried to paint the use case diagrams, class diagrams and other diagrams(like sequence diagrams etc.) to clarify the demands.

After that, we divided the whole system to several parts and unified the REST-API between modules. We also divided our team to two groups -- 
three members for coding and two members still stayed in the factory in order to keep communication between coding group and the manager of the factory.

### Project Outcomes

The FrontPage of the System (Auto-translated by Chrome)
![The FrontPage of the System](./figures/factory_app/FrontPage.png)

Project Show - the role "system administer" home page UI
![the system administer's home page UI](./figures/factory_app/system_admin_view.png)

Project Show - the role "employee" info-searching UI 
![Project Show - the role "employee" info-searching UI](./figures/factory_app/employee_view.png)

The Account table in PostgreSQL DB
![The Account table in PostgreSQL DB](./figures/factory_app/Account_DB.png)

### Project Achievements

The factory is now using our system in their daily working. The feedback from workers is pretty good.

"It's almost the most useful enterprise system I've used yet!" Said by a senior worker from that factory.


### Project References
[Source Code of web application part](https://github.com/chenjiaqi-factory-project)

[Website for demonstration (in Chinese)](http://182.92.119.168:80/)

## The Design and Implementation of a Micro-service Visualization, Operation and Monitoring System
(Internship in Institute of Software Chinese Academy of Science)

### Keywords
>Project Keywords: Basic Architecture, micro service architecture(Service Mesh), DevOps System

>Technical Keywords: IaaS, Docker, Kubernetes(K8S), Istio

### A Brief Introduction of the Project

The main work of this project team is based on Kubernetes research and development of a self-use cloud service platform for Internet companies (similar to "Alibaba Cloud", "Tencent Cloud", etc.) and delivered on time. As a member of the project team, I am mainly responsible for researching how micro service architectures are applied to Kubernetes clusters and designing and implementing Docker container monitoring cloudware and modules.

### Mainly Description of the Project

In the research of this project, I reviewed and translated several foreign language blogs and foreign language development documents, and contributed convenience and value to the Chinese development community while improving myself. (For translation articles, see: [Envoy, Nginx and HAProxy, micro How to choose a communication agent in the service? Translated from English blog](https://zhuanlan.zhihu.com/p/53470343), first published in the Nuggets translation plan).

In terms of technology selection, I used the "Service Mesh" architecture to replace the more popular "Spring Cloud Framework" for monitoring module design.
At present, the progress of the module can monitor the call relationship between each micro service (Istio-based Sidecar mode and L4, L7 agent), and visualize various common monitoring indicators (such as CPU utilization, network delay, etc., based on Prometheus and Grafana).

### Project Outcomes

Design of the System Architecture
![Design of the System Architecture](./figures/iscca-ms/arch_design.png)

Resource Monitoring Panel(Using Grafana) - Sample No.1
![Resource Monitoring Panel 1](./figures/iscca-ms/monitor_panel.png)

Resource Monitoring Panel(Using Grafana) - Sample No.2
![Resource Monitoring Panel 2](./figures/iscca-ms/monitor_panel2.png)

### Project Achievements

The project leader, Professor Zhang Wenbo, a doctoral tutor at the Chinese Academy of Sciences, and Professor Wang Wei, a master tutor, are very satisfied with my work.

### Project References

[Github Organization of Micro service Team in ISCAS](https://github.com/iscas-microservice-team)

[Internship Certification in English](./materials/internship_iscas.pdf)


## The End
Thanks for your reading.





