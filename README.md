# Project-7-Container-App-project-6
## Container project

![Capture1](https://user-images.githubusercontent.com/74002629/185382955-28d67f00-8b19-4caa-8dd2-048cea6c0b74.PNG)

#### Project Description
-. Container project webapp like linkedin or facebook 
-. An application that used to share posts and make commant like facebook application connected with database to save info
-. and you can see your profile picture and cover.
Tools :-
1. Windows.
2. Terminal ubuntu.
3. Virtual Box.
4. Docker.
5. Linux.
6. DataBase MariaDB
7. Cashing DB like Memcashe to handel the query
8. Message Broker Rabbit MQ
9. Web server Tomcat
10. Nginx 

#### Step 1 - Setup and install Docker.
1. install Docker.
2. make 5 Containers with images.
    
#### Step 2 – Handeling the serveces.

1. Login with ssh port by linux.
2. username and password is vagrant.
3.Cheak Hostnames and IPS.


#### Step 3 - setup and install MYSQL.

1. Login to VM-DB and update OS Cheak Hostname and IP.
2. Install Mariadb package and starting enable Mariadb server.
3. Set Database username and password.

![eunmysql](https://github.com/Hatem-sudo/Project-7-Container-App-project-6/assets/113099054/d429c28c-b5cc-4652-a6ad-25dbeabc9895)



#### Step 4 – setup and install MEMCASHE.

1. Login to VM-MC and update OS Cheak Hostname and IP.
2. set repository and install the depdensies.
3. Install and enable memcahe on port 11211 and starting firewall  

![pix12](https://user-images.githubusercontent.com/74002629/185373600-c9815226-51e1-4e1a-ac92-b17b2e3713ea.PNG)

#### Step 5 - setup and install Rabbit-MQ.

1. Login to VM-RMQ and update OS Cheak Hostname and IP.
2. set EPEL repository and install the depdensies.
3. setup access to usertest and make it admin and starting firewall and open port 5672.

![pull rabit](https://github.com/Hatem-sudo/Project-7-Container-App-project-6/assets/113099054/bd1cef81-15f4-46bb-950b-8b65ae038002)

#### Step 6 - setup and install Tomcat.

1. Login to VM-App and update OS Cheak Hostname and IP.
2. Set repository and install the depdensies.
3. Download Tomcat package and change dir dir to /tmp and add user
4. Copy Tomcat home dir and creat Tomcat server file and enable firewall

![pix12](https://user-images.githubusercontent.com/74002629/185373600-c9815226-51e1-4e1a-ac92-b17b2e3713ea.PNG)

#### Step 7 - Code Build.

1. Download source code from gitHub or any version controll.
2. deploy the artifact.

![git and install maven](https://github.com/Hatem-sudo/Project-7-Container-App-project-6/assets/113099054/f69620c9-cd2c-4abc-b344-12e16d19d4b0)


#### Step 8 - setup and install Nginx

1. Login to VM-Web and update OS Cheak Hostname and IP.
2. Creat Nginx configration file and update contant
3. Delete old file and creat link to active website and resart Nginx.

![pull niginx and tomcat](https://github.com/Hatem-sudo/Project-7-Container-App-project-6/assets/113099054/567f6217-bce8-44c2-bd99-e2c7a0bcfc5e)

it's Done !!!

![dockercomposeup](https://github.com/Hatem-sudo/Project-7-Container-App-project-6/assets/113099054/b43cbba8-d003-4860-aa8a-74fa57001d20)

![1](https://github.com/Hatem-sudo/Project-7-Container-App-project-6/assets/113099054/0f7d702f-f460-43d7-80af-174d3c984758)


