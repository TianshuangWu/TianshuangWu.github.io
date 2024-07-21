---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<head>
    <style>
        .container {
            display: flex;
        }
        .text {
            flex: 80%;
        }
        .image {
            flex: 20%;
            display: flex;
            justify-content: flex-end;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="text">
              <p>I am a postgraduate in <a href='https://cies.hhu.edu.cn/'>College of Computer Science & Software Engineering</a> at <a href='https://www.hhu.edu.cn/'>Hohai University</a>. I am honored to be under the guidance of Professor Bao-Liu Ye and <a href='https://lyushenhuan.github.io/'>Shen-Huan Lyu</a>. Before that, I received my B.Sc. degree from <a href='https://scs.nuist.edu.cn/main.htm'>the School of Computer Science、Cyber Science and Engineering</a> in <a href='https://www.nuist.edu.cn/main.htm'>Nanjing University of Information Science & Technology</a> in Jun.2023.<br><br>
              My research interest includes <b>model compression</b> and <b>few-shot learning</b>.<br><br></p>
        </div>
        <div class="image">
            <img src="images/hhu.svg" alt='sym' width="60%">
        </div>
    </div>
</body>


# 🔥 News
- My graduate research focused on deep learning model compression, which aims to reduce the size of deep neural network models so that they can run on devices with limited computational resources, such as mobile devices or embedded systems. This process involves reducing the storage requirements of the model and improving its execution speed, while trying to maintain the performance of the model. Especially in the application scenarios of medical, finance and other fields, when dealing with sensitive data (such as disease diagnosis and treatment information in medical data or bank account information, investment and consumption records in commercial data), the number of accessible samples is limited due to the needs of privacy protection, which brings a challenge of how to compress the model in the case of few shot while ensuring the performance of the model.

#  👨‍💻 Projects
- <b>Deep Face Forgery DetectionSystem Based on Xception Model</b> Based on the Xception network model in deep learning, the face forgery video dataset is trained, and the best model is obtained by comparing and optimizing with the current model algorithms commonly used in deepfake face videos. Based on this, a face forgery detection system is designed. In the design process, the SeNet module is added to automatically obtain the importance of each channel to screen features by learning, and the WSDAN module is also introduced for data enhancement. Experiments show that the system can identify a variety of deepfake technologies (such as Deepfakes, Faceswap, etc.) with high accuracy. The future optimization direction is to accelerate the detection speed. [[code]](https://github.com/TianshuangWu/DeepFake)

- <b>Student Management System</b> The Student Management System is a system developed in C++ designed to efficiently manage and organize student data. The system mainly provides simplified administrative task processing and enhanced data access functions for educational institutions. The main functions include student record management (add, edit, delete, view student information), grade management (enter and update grades), and search and filter functions. The system adopts Object-oriented Programming (OOP) design, uses C++ standard library for basic operations and data processing, implements data persistence through file system or SQLite database, and provides secure user authentication and role-based access control. The system aims to provide a reliable and efficient student information management solution for educational institutions. [[code]](https://github.com/TianshuangWu/StudentScoreManage)

- <b>Shark Attack Prediction</b> The Shark Attack Prediction project utilizes Jupyter Notebook to predict shark attacks through data analysis and machine learning techniques. The project collects and processes historical data, performs exploratory data analysis and feature engineering, trains and evaluates models using a variety of machine learning algorithms, and ultimately makes predictions and visualizations on new data. The project aims to identify the key factors affecting shark attacks and help relevant departments and individuals to take preventive measures in advance to reduce safety risks in Marine activities. [[code]](https://github.com/TianshuangWu/SharkAttack)

# 📝 Publications 
- 

# 🎖 Honors and Awards
- *2021-2023* The school Scholarship in Nanjing University of Information Science & Technology.
- *2021-2022* Excellent student cadre of the school.
- *2021-2022* Merit student of the school.
- *2019* The first prize of the Challenge Cup China College Students Business Plan Competition.

# ✨ Academic Service
-

# 📖 Educations
- *2023.09 - now*, MA.Sc. in Electronic & Information Engineering, Hohai University (HHU) 
- *2019.09 - 2023.06*, B.Sc. in Information Security, Nanjing University of Information Science & Technology (NUIST)

# 💬 Invited Talks


# 💻 Internships
