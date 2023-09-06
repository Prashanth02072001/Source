**Jenkins installation**
Docker/ by kubernetes
WAR files(web application archive)
Windows

**Apache Tomcat Installation**
1.Installjava8
2. Apache tomcat v9
3.Download and deploy war file
4.Installation of plugin

#Install home brew
1. brew install jenkins-lts
2.clear
3.brew list(finds jenkins)
4.brew services list
5.brew services start jenkins-lts
6. brew services list
7. goto window(chrome) and search for http://loclhost:8080
8. got to path mentioned on the screen of window for password setup
9. secrets ls
10.cat initialAdminPassword (copy the password)
11. paste password in window and then continue , install plugins.
12. start using jenkins, goto people and admin
13. docker pull jenkins/jenkins
14 cd ~/
15 open docker next, docker pull jenkins/jenkins( if not opens clear and run docker pull jenkins/jenkins)
16 ls
docker image ls
docker run jenkins/jenkins (we can have password)
clear
docker run jenkins/jenkins -p 8181:8080
docker run jenkins/jenkins
docker man
docker run -p 8181:8080 jenkins/jenkins
17  docken ps(int terminal)
18 then write in new tab like  localhost:8181

Project creation
1. new project
2. enter title

