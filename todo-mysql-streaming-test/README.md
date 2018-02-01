# Logging query counts per request in a simple Spring Boot Todo List Application

This is a minimal Spring Boot Todo List application. I've created this app as a testing ground for an idea on how
to log number of SQL queries Hibernate executes during rendering of a view (page).

Application has a request interceptor and Hibernate interceptor registered and they count of the queries executed
and log them. Count is also exposed in the model so stats can be displayed on the page itself.

## Running

To run the app download / clone the repository and then use gradle wrapper script to run it.

Linux / Mac:

`./gradlew run`

Windows:
  
`gradlew run`

Point the browser to [localhost:8080](http://localhost:8080), click through the app and watch the logs display timings and query counts
for each request.



