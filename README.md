# Contract-book-Using-Vaadin
Java , HTML5 , JavaScript


Importing in NetBeans 8
--------------------
These instructions were tested on NetBeans 8.0.2. You can get it from https://www.netbeans.org

To checkout and run the project in NetBeans, do:
- Team -> Git -> Clone
- Set repository URL to https://github.com/vaadin/addressbook.git
- Finish
- Right click the imported project (Vaadin Addressbook Application) and select Run
- Select GlassFish Server 4.1 -> Remember in Current IDE Session -> OK

You should now have a GlassFish server running on localhost:8080 and a browser tab should also be automatically opened with this location

Importing in Eclipse
--------------------
These instructions were tested on Eclipse IDE for Java EE Developers Luna SR2. You can get it from http://eclipse.org/downloads/

To checkout and run the project in Eclipse, do:
- File -> Import...
- Check out Maven Projects from SCM
- Choose Git from SCM menu
  - If you do not see "Git" in the SCM menu, click "Find more SCM connectors in the m2e Marketplace" and install "m2e-egit". Restart Eclipse and start over.
- Set the repository URL to https://github.com/vaadin/addressbook.git
- 

You should now have a Jetty server running on localhost:8080. Navigate to [http://localhost:8080/](http://localhost:8080/) to play with the application

To use the built in server adapters of Eclipse,
- Run As -> Run on Server
- Select the server you want to run on, e.g. Apache Tomcat 8 and click ok
- *Do not use the suggested J2EE Preview server* as it is outdated, deprecated and does not support Servlet 3, which is required for this application
