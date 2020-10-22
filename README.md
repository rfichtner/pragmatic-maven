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
	
	