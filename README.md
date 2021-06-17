# taxi_service
    Web-application for organizing the work of a taxi service manager.
# How to use it:
1. Create DB on SQL-script in src/main/resources/init_db.sql file.
2. Configure tomcat 
    * Use taxi_service:war exploded
    * leave @Application contex@ : "/"
3. Insert configuration data to src/main/java/mate/util/ConnectionUtil.java
4. Build project.
