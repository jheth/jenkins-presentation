!SLIDE bullets

# Continuous Integration with ![jenkins](../images/jenkins_logo.png) #

## An extendable open source continuous integration server ##

!SLIDE bullets incremental transition=fade

# Continuous Integration (CI) #

* [http://martinfowler.com/articles/continuousIntegration.html](http://martinfowler.com/articles/continuousIntegration.html)
* Integrate and test code changes early and often
* Make results visible to all
* Automate the Build and Deployment

!SLIDE bullets incremental transition=fade

# Workflow #

* Checkout code from SCM (SVN, GIT, etc)
* Make changes to code (bug fixes, new features)
* Write and Run automated tests
* Merge with latest changes from SCM
* Commit code
* Run a build on a clean machine (CI Server)

!SLIDE bullets incremental transition=fade

![Diagram](../images/ci.jpg)

!SLIDE bullets incremental transition=fade

# Introducing Jenkins #

* Open Source Continuous Integration Server
* [http://jenkins-ci.org](http://jenkins-ci.org)
* Formerly known as Hudson (Oracle owns the rights) 
* Collaborate on GitHub: [https://github.com/jenkinsci](https://github.com/jenkinsci)

!SLIDE bullets incremental transition=fade

# Installation #

* Native packages are available for many platforms.

* wget http://mirrors.jenkins-ci.org/war/latest/jenkins.war
* java -jar jenkins.war
* Visit http://server:8080
* /Users/jheth/.jenkins

!SLIDE bullets incremental transition=fade

# The Build #

### The entire set of ALL steps needed to obtain the software product.

* Checkout code from SCM
* Compile code (if necessary)
* Perform static analysis checks
* Run automated tests
* Generate code coverage reports
* Generate code documentation

!SLIDE bullets incremental transition=fade

# The Build #

### The entire set of ALL steps needed to obtain the software product.

* Display the results
* Publish/Deploy build artifacts
* Alert developers on failure
* ... 
*   
*   

!SLIDE bullets incremental transition=fade

# Demo #

