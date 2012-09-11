Liferay Portal
==============
Liferay Portal is a free and open source enterprise portal written in Java. It is an enterprise web platform for building business solutions that deliver immediate results and long-term value.

Running the Application
-----------------------

Liferay comes with a default database called HSQL or "hypersonic." This is not meant for production use however! As this example is just a demo, it does use the HSQL database.
If you want to use Liferay in production, you need to switch to another database.

Also, the JAVA JVM needs the -XX:MaxPermSize=256m" argument for this application. We configured that by adding the JAVA_OPTS environment variable.

To run the application, make sure you have the Stackato client installed and that you are logged in successfully for your desired target environment (e.g. http://api.stackato.local).

Then execute:

        stackato push -n 

This application takes a long time (about 4-5 minutes) to start. There might be a timeout with the Stackato client although the application is still starting.
Then go on your application url.

That's all. Have fun!
