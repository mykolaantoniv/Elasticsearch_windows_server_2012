1. Download elasticsearch: https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch-1.2.1.zip;
2. Extract package
3. Download the JDK version of Java and install it.
	Go to the Java website: http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
	Accept the license and then download: “Windows x64 (jdk-8u5-windows-x64.exe)” package.
	Now install it!
4.  Add the JAVA_HOME variable to the server
	Now right click on “This PC” and choose “Properties” on the right bottom site next to your computer and full computer name click on Change settings.
	On the window that opens go to the Advanced tab and click on “Environment Variables”.
	at the bottom box called “System Variables” click on “new” and add the following:
	Variable Name: JAVA_HOME
	Variable value: C:\Program Files\Java\jdk1.8.0_05
5. Open a console and go to “c:\basefarm\elasticsearch\bin\”
	type the following command: "service install" and "service manager"
	