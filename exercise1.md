# CI:CD pipeline

I assumed that i am using JAVA language to build the web application. We are a team of 6 and we will discuss what are the technologies we want to use to build our application in most efficient way. Well, we will be obviously using git and github to maintain our code. Besides, we will discuss what are the other technologies we will be using for our application specially for linting, testing, building, CI setups and more.


## Linting
Besides that we want to look up for the most efficient linting tool in our use case. Researching (Googling) for about 10 to 15 minutes, we came across various linting tools for JAVA. CheckStyles, SonarCube, LightRun were among the best and common linting tools we all came accross. CheckStyles is a linting tool that works on most IDE and also supports CLI. After some discussions we came to a conclusion to use CheckStyles for our application.

## Testing
There are lots and lots of testing frameworks for JAVA ecosystem. JUnit is one of the most famous framework for unit testing. JUnit offers test runners to execute tests. It is  less complicated and takes minimum time to execute. Another poweful testing framework is Selenium. It is end to end testing framework which is an automated open-source (free) application testing framework that is used for cross browser testing. It is functional for almost every browser, works on most popular operating systems, and its scripts can be written in popular programming languages like C#, Java, Python, PHP, and more. So we concluded to use Selenium for testing our application.

## Building
For building JAVA application Apache Maven is most popular which was originally developed in 2001 and has since been adopted as the de facto standard for building Java projects. Maven’s scalability and extensibility make it an attractive choice for small development teams who need automated builds but don’t have a lot of resources allocated toward software engineering overhead. Other alternatives maybe Gradle, SBT and Apache Ant with ivy.

## CI setup
For setting up my CI pipeline, Jenkings and Github Actions are the best possible options but besides them we do have few other tools such as Circle CI, Travis CI, Buddy, GitLab CI, Code ship etc. Some of these tools are self hosted and some of them are cloud-based. For our application, We chose Github Actions because our application is mediumly sophisticated application and we dont wanna spend too much on setting up our own servers.




