* A Web Application of Apache Spark using Spring Boot MVC to read Wuzzuf dataset downloaded form Kaggle.com

## Mixing Spring & Spark - Steps:
1. Create a Maven-Based Spring Boot Project
2. Add the required dependencies in pom.xml
3. Configure Spark Properties in application.properties
4. Adding the Spark ApplicationConfig: declaring the JavaSparkContext and SparkConf as beans (using @Bean annotation) this tell the spring container to manage them for us
5. Creating a service/controller for Read Csv & Register a REST Controller with an endpoint
6. Run the application, Test your application from a REST client or on Browser
   Url: http://localhost:8081/read-csv


   *just run the program, and use request mapping to test each function
   *The charts are stored in /public folder 
   *You can visualize the charts using request mapping :
	*localhost:8081/pie
	*localhost:8081/bar1
	*localhost:8081/bar2

   *to see YearsExp column after factorization:	localhost:8081/factorizeYrsOfExp
 
   