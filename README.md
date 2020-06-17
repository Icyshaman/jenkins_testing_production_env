# jenkins_testing_production_env
>**Requirements**:
* docker

* git

* github account

* httpd docker image

* jenkins
<br><br>
>**How to use**:
* Clone github repository.
<br><br>
* Configure git hooks.

  * ![](Images/2.jpg)
<br><br>
* Configure jenkins job1

  * ![](Images/8.jpg)
  <br><br>
  * ![](Images/9.jpg)
<br><br>
* Configure jenkins job2

  * ![](Images/16.jpg)
  <br><br>
  * ![](Images/17.jpg)
<br><br>
* Add file to master branch of local git repository.

  * ![](Images/1.jpg)
<br><br>
* Add file to staging area and then move the files to commit area, as we configured git hook, when we commit, repo will directly pushed to the github master branch.

  * ![](Images/3.jpg)
  <br><br>
  * ![](Images/4.jpg)
<br><br>
* Since our jenkin job1 is configured, it will automatically copy the file to production environment and start docker container for production purpose.

  * ![](Images/5.jpg)
  <br><br>
  * ![](Images/6.jpg)
  <br><br>
  * ![](Images/7.jpg)
<br><br>  
* Add file to dev1 branch of local git repository.

  * ![](Images/10.jpg)
<br><br>  
* Add file to staging area and then move file to commit area, as we configured git hook, when we commit, repo will directly pushed to the github dev1 branch.

  * ![](Images/11.jpg)
  <br><br>
  * ![](Images/12.jpg)
<br><br>  
* Since our jenkin job2 is configured, it will automatically copy the file to testing environment and start docker container for testing purpose.

  * ![](Images/13.jpg)
  <br><br>
  * ![](Images/14.jpg)
  <br><br>
  * ![](Images/15.jpg)