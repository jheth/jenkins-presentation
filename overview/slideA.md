!SLIDE

# Continuous Integration with Jenkins #

![jenkins](jenkins.png)

Ready to serve you day or night

!SLIDE incremental transition=fade

# Continuous Integration

* [CI by Martin Fowler]: http://martinfowler.com/articles/continuousIntegration.html
* Integrate and Test code changes ASAP

!SLIDE bullets incremental transition=fade

# Introducing Jenkins #

* Continuous Integration Server
* http://jenkins-ci.org
* Formerly known as Hudson (Oracle debocle) 
* Open Source / Free for All

!SLIDE bullets incremental transition=fade

# Installation

* wget http://mirrors.jenkins-ci.org/war/latest/jenkins.war
* java -jar jenkins.war
* Visit http://localhost:8080
* /home/<user>/.jenkins

!SLIDE bullets incremental transition=fade

# Developer Workflow 

* Checkout code from SCM (SVN, GIT, etc)
* Make changes to code (bug fixes, new features)
* Run automated tests
* Commit code
* Repeat steps 2-4

!SLIDE bullets incremental transition=fade

# The Build

## The entire set of ALL steps needed to obtain the software product.

* Checkout code from SCM
* Compile code (if necessary)
* Perform static anaylsis checks
* Run automated tests
* Generate code coverage reports
* Generate code documentation
* Report the results
* Publish/Deploy build artifacts
* Alert developers on failure

!SLIDE bullets incremental transition=fade

# Job vs Build

* Job is to Build as Class is to Instance of a Class.
* A Build is a single run of a Job definition.

# Demo


