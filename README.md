# javaservlet


Run a 'git clone https://github.com/dmendez1/javaservlet.git'

Navigate to the '/src/resources/application.properties/' and edit azure.cosmosdb.uri, azure.cosmosdb.key, azure.cosmosdb.database values in order to work with your azure cosmosdb configuration.

From a command line at the root of your project run a 'mvn clean spring-boot:run' this should start your servlet and input yout hardcoded credentials. 

Alternatively you can create your own spring boot starter here: https://start.spring.io/.
