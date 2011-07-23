!SLIDE bullets

# Continuous Integration with ![jenkins](../images/jenkins_logo.png) #

## An extendable open source continuous integration server ##

!SLIDE bullets incremental transition=fade

# Continuous Integration (CI) #

* [Martin Fowler Article](http://martinfowler.com/articles/continuousIntegration.html)
* Integrate and test code changes early and often
* Make results visible to all
* Automate it

!SLIDE bullets incremental transition=fade

# Introducing Jenkins #

* Open Source Continuous Integration Server
* [http://jenkins-ci.org](http://jenkins-ci.org)
* Formerly known as Hudson (Oracle debocle) 
* Collaborate on GitHub: [https://github.com/jenkinsci](https://github.com/jenkinsci)

!SLIDE bullets incremental transition=fade

# Installation #

* Native packages are available for many platforms.

* wget http://mirrors.jenkins-ci.org/war/latest/jenkins.war
* java -jar jenkins.war
* Visit http://server:8080
* /Users/jheth/.jenkins

!SLIDE bullets incremental transition=fade

# Developer Workflow #

* Checkout code from SCM (SVN, GIT, etc)
* Make changes to code (bug fixes, new features)
* Run automated tests
* Commit code
* Repeat steps 2-4

!SLIDE bullets incremental transition=fade

# The Build #

### The entire set of ALL steps needed to obtain the software product.

* Checkout code from SCM
* Compile code (if necessary)
* Perform static analysis checks
* Run automated tests
* Generate code coverage reports
* Generate code documentation
* Report the results
* Publish/Deploy build artifacts
* Alert developers on failure

!SLIDE bullets incremental transition=fade

# Job vs Build #

* Job is to Build as Class is to Instance.
* A Build is a single run of a Job definition.

!SLIDE bullets incremental transition=fade

# Demo #


