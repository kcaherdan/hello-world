# maven-project

Simple Maven Project

Create a new github repository called "hello-world"

1. login to github
2. locate new repository and select
![create New repository](img/createnewrepo.jpg)

3. Input repository name as "hello-world"
4. Make repository "Public"
5. Add a README file and select "Create repository" 
![create repository](img/createrepo.jpg)


6. New repository created!
![hello-world repo created](img/newrepoCreated.jpg)

7. Upload files from the devolopers
![upload files](img/uploadfiles.jpg)
Drag additional files here.

![drag files here](img/dragfileshere.jpg)

8. setup Jenkins and login with your credentials

![jenkins login interface](img/jenkinslogin.jpg)

![jenkins with credentials](img/jenkinsloginwithcredential.jpg)

Since I am using a Jenkins container, I need to login as root and install java jdk 8 or 11,
also I need to install Maven, 
Java "apt install default-jdk"
java -version

Maven "apt install maven"
mvn -version

![install java and maven](installjava&mvn.jpg)

9. Install maven login; navitage to Manage jenkins :manage/pluginManager/available plugins
search for maven to install;

![maven plugin installation](img/installmavenplugin.jpg)

10. Create a Job on jemkins "A Maven Job"

![create a job](img/createajob.jpg)

11. Enter an item name "hello-world" and select ok

![Maven project "hello-world"](img/mavenproject.jpg)

12 Configure Jenkins

 Git - Source Code Management
![Repo URL and branches to build](img/git.jpg)

Build Root POM
![Alt text](img/build.jpg)

Build the Project by pressing Build Now 
![Build Now](img/Buildnow.jpg)

Building the project 
![running the build](img/building.jpg)

Finally, Build is successful
![Build is successful](img/done.jpg)


