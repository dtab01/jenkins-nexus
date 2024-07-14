# sonarqube
This project seeks to integrate Nexus first & then Sonarqube, Maven, Tomcat & Git with Jenkins on an EC2 instance on the AWS platform.

How to Integrate Nexus Repository with Jenkins Using Declarative Pipeline

1.  Create Hosted repository in Nexus
2.  Create Local User in nexus
3.  Install Nexus Plugin to integrate with Jenkins
4.  Add Nexus Credentials in Jenkins
5.  Write Jenkinsfile by adding one stage which will be used to publish the artifact to Nexus Repository Manager

6.      Prerequisites
7.        OpenJDK
8.        Minimum CPUs: 4
9.        Ports: 8080 (Jenkins), 8081 (Nexus
10.       Jenkins installed on an EC2 instance / User Account
11.       Nexus installed on an EC2 instance
12.       Web Browser

13.        In   Nexus
14.  Create Repo in Nexus ( Type- maven2(hosted); Name -maven-central-repository; Version policy- Release/Snapshot/Mixed; Layout Policy- Strict; Blob store- default; Deployment Policy- Allow Redeploy; Cleanup policy)
15.  Create New User (1st & last Name- Jenkins User; Email- juser@example.com; Passwd- jenkins123; status - active; roles - nx-admin)
16.  
