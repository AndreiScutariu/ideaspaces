# ideaspace - Java project example
This project uses Spring Boot 1.3.5

# Database setup
  create database ideaspaces;
  mysql -u root -p < ideaspaces.sql

## Run the app
    gradle run

Navigate to [http://localhost:8080/ideas](http://localhost:8080/ideas), you should see the following in your browser:

    {"id":1,"content":"content"}
