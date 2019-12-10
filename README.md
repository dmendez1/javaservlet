# javaservlet


Run a 'git clone https://github.com/dmendez1/javaservlet.git'

Navigate to the '/src/resources/application.properties/' and edit azure.cosmosdb.uri, azure.cosmosdb.key, azure.cosmosdb.database values in order to work with your azure cosmosdb configuration.

From a command line at the root of your project run a 'mvn clean spring-boot:run' this should start your servlet and input yout hardcoded credentials. 

Alternatively you can create your own spring boot starter here: https://start.spring.io/.

**********INSTALLING MAVEN TO MAC OS *********


Extract the distribution archive, i.e.apache-maven-3.3.9-bin.tar.gz to the directory you wish to install Maven 3.3.9. The subdirectory apache-maven-3.3.9 will be created from the archive.
Optional: Add the MAVEN_OPTS environment variable to specify JVM properties, e.g. export MAVEN_OPTS="-Xms256m -Xmx512m". This environment variable can be used to supply extra options to Maven.
Make sure that JAVA_HOME is set to the location of your JDK, e.g. export JAVA_HOME=$(/usr/libexec/java_home -v 1.8) and that $JAVA_HOME/bin is in your PATH environment variable (although that might not be necessary with the latest Mac OS X versions and the Oracle JDK).
Add extracted apache-maven-3.3.9/bin to your $PATH
Run mvn --version to verify that it is correctly installed.
