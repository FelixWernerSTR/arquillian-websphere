# very simple demo

* install websphere9 create a profile and start profile see steps below

* configure arquillian.xml
* build: mvn clean install
* or execute just junit-tests

* installing Websphere and creating profile:
* for example: unzip WebSphere_v900x.zip

* then you have to create initially a profile:

* execute %your_unzipped_directory%\AppServer\bin\ProfileManagement\pmt.bat
* just execute the wizard after clicking create new profile("disable administrative security")

* A hint:
* Please copy(and zip) new created profile for future usage. 
* Only this directory: %your_unzipped_directory%\AppServer\profiles\AppSrv01 
* After every stop you can override an initialy new created profile in future. 

* Starting a profile:
* call %WAS_HOME%/bin/startServer.bat server1 -profileName AppSrv01
* Stopping a profile:
* call %WAS_HOME%/bin/stopServer.bat server1 -profileName AppSrv01





