# SPRINGBOOT_WORKSHOP

EXPLAINATION : 

* it provide the embbed server
* reduce the boilstatehok
* Advantage	Description
✅ Fast Start	Ready-to-run projects
✅ Simple	Less setup and config
✅ Powerful	Enterprise-ready features
✅ Flexible	Works with most databases, tools, and APIs
✅ Scalable	Great for microservices and large systems

 Maven - project building tool, it updates the version of the each dependencies  and to manage jar and war file :
JAR ,WAR - java archive file , web archive file which have the all dependenices 
annotation : a way to add metadata ( @ sysmbol) to define the data .

WORKING PROCESS:


step 01 : to download Maven from appache maven website : https://maven.apache.org/download.cgi ,under that , download the file in binary zip file 

step 02 : to setup the environment system variable : 
* extract - copy path - create path in path variable and give name as M2_NAME 

step 03 : to verify , mvn --version 

![image](https://github.com/user-attachments/assets/563b4499-f652-4fed-ac6e-cb097d4b16b9)

step 04 : SETUP SPRING INITIALIZR 
 to communicate with the client and the server 
open chrome > start.spring.io
gradle gravy - for mobile application ,
maven for backend server .
dependencies : 
mongodb 
springboot
sprint web 
![image](https://github.com/user-attachments/assets/22aeb7e1-c18d-48d7-922c-80ce52197f2d)
click genrate 
give genrate >> download file >> extract it 
open eclipse >> under maven >> project >> browse >> crudusingmom=ngodb file >>  double click the folder >>  src/main/java >> only java file >> 

pom.xml - project object model 
step 05 : to install the maven jar file to the package maven 
Step 1: Open the Maven Tool Window
On the right side of IntelliJ, look for the "Maven" tab (a small m icon).

If you don't see it, open it from the top menu:
View → Tool Windows → Maven

Step 2: Run the package Goal
In the Maven panel:

Expand your project name

Then expand Lifecycle

(in intllij )
step 06 : MONGODB CONNECTION 

![image](https://github.com/user-attachments/assets/51381d83-332a-4dd4-bb20-10ec66529d7a)


step 07 : create the model file in the src/min/java-package 
step 08" create the database in mongodb as same name in package 
step 10 : open the java class and type ../////////  CREATE MODEL   ////////
@document(collection="student ")
public class student {
@id 
private String id ;
private String name ;
private String dept ;
// read get 
public String getId(){
return id;
}
public void setId(String id){
this.id=id; // for reference object 
}
method - correction of st : 2 types - user defined - access defined -
client -server -db
        controller  //collection of api and functionality of api
         service // product seriva
         model
         repository (JPA - manageing the relational data )
          db 

