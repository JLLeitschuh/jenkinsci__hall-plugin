#Hall Jenkins Plugin

##Using the Plugin

TODO

##Development Setup

###Prerequisites:
1. Maven, OSX comes with it, for others [download it here](http://maven.apache.org/download.cgi)
1. [Eclipse](http://www.eclipse.org/downloads/)
1. [Maven Eclipse Plugin](http://eclipse.org/m2e/download/)

###Eclipse Setup
1. Open Eclipse
1. File > Import > Existing Maven Projects
1. Choose root directory of the repo
1. Follow instructions

###Running
	$ cd YOUR_REPO_ROOT
	$ mvn clean
	$ mvn hpi:run
	
Navigate to [localhost:8080/jenkins](http://localhost:8080/jenkins) 