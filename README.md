# Prototype
# installation
This project contains (1) a zipped java implementation called proj2 of our prototype and 
(2) a set of zip files corresponding to the htdocs directory of an apache server in which we deploy
all resources used by the prototype (mainly ontologies, service specifications and requests descriptions).
The installation of the prototype requires a previous installation of xampp (https://www.apachefriends.org/) at c:\ (root directory in drive c).
Then, (1) Download the whole project in zip format (from the button called Code). The downloaded project is a directory called prototypes-main, 
      (2) Unzip the zipped directory called prototypes-main in a temporal directory.
      (3) As we said, the result of (2) is a zipped java implementation called proj2 of our prototype and 
      a set of 1015 zip files corresponding to the htdocs directory of an apache server.
      (4) In a temporal directory, unzip the htdocs directory by unzipping the file called htdocs.zip (using for instance winrar or 7-zip programs). 
      This step generates an unzipped htdocs directory containing all resources used by the prototype in directories such as specifications, requests,
      ontologies, modules, repositories, ... etc) 
      (5) All resources (directories+ files) generated in (4) must be copied to the htdocs directory of the apache server (c:\xampp) previously installed 
      in your machine.
      (6) Unzip the protoype (called proj2). Is is recommended to use an IDE such as IntelliJ IDEA or eclipse to execute it.
# execution
The execution of the prototype requires the initialisation of the apache server located at c:\xampp. This can be done by executing xampp-control application in c:\xampp. 
The execution of xampp-control shows a control panel for starting and ending the apache server which load all documents deployed at the c:\xampp\htdocs directory (installation, step 5).
Once the apache server has been started, the protoype can be executing by using some of the test programs included in its src\test directory (for instance, TestSearch, TestExperiment).
A set of java executable experiments is supplied in the directory src/experiments of the prototype. These experiments have been previously generated with the prototype. Their executions
have allowed to compile data in a excel file also supplied in the prototype called result.xlsx
