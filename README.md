# Hotstar-pipeline-automation
This project demonstrates a robust, end-to-end CI/CD pipeline for a Java Maven web application (Hotstar clone). The pipeline is built using Jenkins Declarative Pipeline to automate the entire software delivery lifecycle—from code integration to final deployment on a production-ready server.
![p1](https://github.com/user-attachments/assets/c1bcc790-f4ba-4e5e-a937-3ed708a82464)
![P2](https://github.com/user-attachments/assets/cf1fb4d7-f426-480b-af11-aee77b8ea570)


💡 What Makes This Pipeline Special?

🤔

Feature
⚡ Fully Automated    -->  Zero manual steps from commit to deployment

🔍 Quality Enforced   -->  SonarQube gates block bad code from reaching production

📦 Artifact Versioned -->  Every build is stored and versioned in Nexus

☁️ Cloud Backed       -->  WAR files archived to AWS S3 for disaster recovery

🔁 Reproducible       -->  Any build can be re-deployed from Nexus at any time

🖥️ Live Application Preview --> The deployed Hotstar clone application, running on Apache Tomcat after a successful pipeline execution.
                                    ![WhatsApp Image 2026-04-09 at 1 13 26 PM](https://github.com/user-attachments/assets/347df9dd-5284-4cbb-adab-a10dfaaadb11)

# Tool & Technologies
                                    
![Tools and Tech](https://github.com/user-attachments/assets/03086cca-6f08-4492-bc5c-12e6ab239ccf)

# Plugin Used
Plugin-----------------------------------------------*----------------------------------- Purpose

Maven Integration Plugin-------------------------------------------------------------- Run Maven builds inside Jenkins

SonarQube Scanner for Jenkins--------------------------------------------------------Connect Jenkins to SonarQube

Sonar Quality Gates Plugin-----------------------------------------------------------Enforce Quality Gate in pipeline

Deploy to container Plugin-----------------------------------------------------------Deploy WAR to Tomcat

Nexus Artifact Uploader--------------------------------------------------------------Push artifacts to Nexus

S3 publisher plugin------------------------------------------------------------------Upload files to AWS S3

# Jenkins Credentials

1.Tomcat Credentials
2.Nexus  Credentials
3.Sonar  Credentials
4.AWS S3 Credentials

# 👤 Author
# A Creation by Nawazish 
        Build with ❤
