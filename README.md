# jenkins_testing_production_env
> **Requirements**:
* docker
* git
* github account
* httpd docker image
* jenkins

>**How to use**:
* clone the repository

* configure git hooks

  ![](Images/2.jpg)

* configure jenkins job1

  ![](Images/8.jpg)

  ![](Images/9.jpg)

* configure jenkins job2

  ![](Images/16.jpg)

  ![](Images/17.jpg)

* add a file to master branch of local git repository.

  ![](Images/1.jpg)

* add the file to staging area and then move the files to commit area as we configured git hook when we commit it directly pushed to the github master branch.

  ![](Images/3.jpg)

  ![](Images/4.jpg)

* since our jenkin job is configured it will automatically copy the file to production environment and start the docker container.

  ![](Images/5.jpg)

  ![](Images/6.jpg)

  ![](Images/7.jpg)
  
* add a file to dev1 branch of local git repository.

  ![](Images/10.jpg)
  
* add the file to staging area and then move the file to commit area as we configured git hook when we commit it directly pushed to the github dev1 branch.

  ![](Images/11.jpg)
  
  ![](Images/12.jpg)
  
* since our jenkin job is configured it will automatically copy the file to testing environment and start the docker container.

  ![](Images/13.jpg)

  ![](Images/14.jpg)

  ![](Images/15.jpg)
