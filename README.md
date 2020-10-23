# pragmatic-maven
Code for the talk "pragmatic maven"

## CLI commands used the talk

### package an artifact
    mvn verify
	
### check for plugin updates
    mvn versions:display-plugin-updates

### check for used / unused dependencies
	mvn org.apache.maven.plugins:maven-dependency-plugin:3.1.2:analyze
	
### check for dependecy updates
    mvn versions:display-dependency-updates
	
### security check
	mvn org.owasp:dependency-check-maven:check

### license report 
    mvn project-info-reports:dependencies
    mvn license:third-party-report
	
