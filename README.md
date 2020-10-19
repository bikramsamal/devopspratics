# Maven .

# What is Maven?
 - Maven is written in Java lanugage, its used to build the package. 
 
# Install the Maven

- Download the .zip file from Maven download site. 
- Unzip the package. 

# Configure the Maven.

- Add the maven path into System Environment variable. 

# Check the Maven Version.

C:\Users\admin>mvn --version
Apache Maven 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)
Maven home: C:\Users\bikramk\Desktop\devops_project\maven3\apache-maven-3.6.3\bin\..
Java version: 1.8.0_221, vendor: Oracle Corporation, runtime: C:\Program Files\Java\jdk1.8.0_221\jre
Default locale: en_US, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows

# Command for Maven Project

1. Open the CMD prompt. 
2. Execute the below command. 
mvn archetype:generate -DgroupId=in.samalgroup.app -DartifactId=devopspratics -DarchetypeArtifactId=maven-archetype-webapp -DarchetypeVersion=1.4  -DinteractiveMode=false

# Add the Maven folder to Git.
$ git init

# Add the files from working to staging Area.

$git add *

# Commit the files from Staging Area,

$git  commit -m "initial project setup"

# Create the new repository in Remote. 

# Add the git file from local to remote repository.

$ git remote add origin "https://github.com/bikramsamal/devopspratics"

$ git push origin master. 

# Build Maven package. 

cd devopspratics
cmd> mvn package

----- Logs

C:\Users\bikramk\Desktop\devops_project\Maven-project\devopspratics>mvn package
[INFO] Scanning for projects...
[INFO]
[INFO] ------------------< in.samalgroup.app:devopspratics >-------------------
[INFO] Building devopspratics Maven Webapp 1.0-SNAPSHOT
[INFO] --------------------------------[ war ]---------------------------------
[INFO]
[INFO] --- maven-resources-plugin:3.0.2:resources (default-resources) @ devopspratics ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\Users\bikramk\Desktop\devops_project\Maven-project\devopspratics\src\main\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.8.0:compile (default-compile) @ devopspratics ---
[INFO] No sources to compile
[INFO]
[INFO] --- maven-resources-plugin:3.0.2:testResources (default-testResources) @ devopspratics ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\Users\bikramk\Desktop\devops_project\Maven-project\devopspratics\src\test\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.8.0:testCompile (default-testCompile) @ devopspratics ---
[INFO] No sources to compile
[INFO]
[INFO] --- maven-surefire-plugin:2.22.1:test (default-test) @ devopspratics ---
[INFO] No tests to run.
[INFO]
[INFO] --- maven-war-plugin:3.2.2:war (default-war) @ devopspratics ---
[INFO] Packaging webapp
[INFO] Assembling webapp [devopspratics] in [C:\Users\bikramk\Desktop\devops_project\Maven-project\devopspratics\target\devopspratics]
[INFO] Processing war project
[INFO] Copying webapp resources [C:\Users\bikramk\Desktop\devops_project\Maven-project\devopspratics\src\main\webapp]
[INFO] Webapp assembled in [45 msecs]
[INFO] Building war: C:\Users\bikramk\Desktop\devops_project\Maven-project\devopspratics\target\devopspratics.war
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  2.100 s
[INFO] Finished at: 2020-10-19T11:55:07+05:30
[INFO] ------------------------------------------------------------------------

C:\Users\bikramk\Desktop\devops_project\Maven-project\devopspratics>
