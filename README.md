# taxi_service
# How to use it:
1. Create DB on SQL-script in src/main/resources/init_db.sql file.
2. Configure tomcat 
    2.1 Use taxi_service:war exploded
    2.2 leave @Application contex@ : "/"
3. Insert configuration data to src/main/java/mate/util/ConnectionUtil.java
4. Build project.
