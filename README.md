# very simple demo

* install websphere9, create a profile and start profile see steps below

* configure arquillian.xml
* build: mvn clean install
* or execute just junit-tests

* installing Websphere and creating profile:
* for example: unzip WebSphere_v900x.zip

* create a profile:

* execute %your_unzipped_directory%\AppServer\bin\ProfileManagement\pmt.bat
* create new profile, just folow the wizard("disable administrative security")

* A hint:
* backup(and zip) new created profile for future usage. 
* Only directory: %your_unzipped_directory%\AppServer\profiles\AppSrv01 
* After every stop you can restore an initialy created profile in future. 

* Starting a profile:
* call %WAS_HOME%/bin/startServer.bat server1 -profileName AppSrv01
* Stopping a profile:
* call %WAS_HOME%/bin/stopServer.bat server1 -profileName AppSrv01





