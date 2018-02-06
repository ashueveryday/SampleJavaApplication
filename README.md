Getting Started with Java-MySQL-Sample Application:
----------------------------------------------------

This application is basically a simple User Input Form that takes input from user and saves it in database.




STS/Eclipse Configuration:
---------------------------

In order to configure this application following steps are to be done:

         1. Import the project in STS/Eclipse.

         2. Right click on the Project and go to properties.

         3. Under java build path, Configure your Tomcat and Java path.
		 
Note: For Eclipse, you have to enable Java Web applications (download the addon).


Maven Configuration:
---------------------------

In order to create pom.xml, following steps are to be done:

		1. Import the project in STS/Eclipse.
		
		2. Right click on the Project and under Configure click convert to maven project.
		
		3. Edit your pom.xml settings and you are ready to go.


Project Configuration:
--------------------------

         1. Open Config.properties (located in WebContent folder).

         2. Update the details of your MySql service in it.

                  app42.paas.db.username = <your_database_username>
                  app42.paas.db.port = <your_service_port>
                  app42.paas.db.password = <your_database_password>
                  app42.paas.db.ip = <your_service_ip>
                  app42.paas.db.name = <your_database_name>
				  
				  
Generating War File using STS/Eclipse:
---------------------------------------

         1. Right click on the project and click export.
         
         2. Under web, select WAR file.
         
         3. Enter the destination path and click on the finish button. Your war is ready.
		 
		 
Generating War File using Maven:
-----------------------------------

		1. First create pom.xml.
		
		2. Run the following command:
		
			mvn clean
			mvn install
			

				  
