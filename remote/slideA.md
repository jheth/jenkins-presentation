!SLIDE

# Remote API

* http://hudson.sentryds.com:8080/api/?
	* XML, JSON, Python
* http://hudson.sentryds.com:8080/job/Database/api/?

!SLIDE bullets incremental transition=fade

# Build on Commit - SVN post-commit hook

@@@
REPOS="$1"
REV="$2"
UUID=`svnlook uuid $REPOS`
/usr/bin/wget \
  --header "Content-Type:text/plain;charset=UTF-8" \
  --post-data "`svnlook changed --revision $REV $REPOS`" \
  --output-document "-" \
  --timeout=2 \
  http://server/subversion/${UUID}/notifyCommit?rev=$REV
@@@

# Build on Commit using GitHub

* GitHub -> Repository -> Admin -> Deploy Keys
* Add Post-Receive URL
* http://jenkins:8080/job/Sniffle/build

If authentication is enabled:
* http://jenkins:8080/job/Sniffle/build?token=shared_secret

!SLIDE bullets incremental transition=fade

# CLI 

[java -jar jenkins-cli.jar -s http://jheth.sentryds.com:8080/ help]

* build
* clear-queue
* install-plugin
* list-changes
* login
* logout
* mail
* offline-node
* online-node
* version
* ....

!SLIDE bullets incremental transition=fade

# Jabber Bot

* !help
* !build [JobName]
* !status [JobName]
* !botsnack [food]
