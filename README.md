# Postman QA Task

Imagine you are testing a room booking application. Using this room booking [API Documentation](https://restful-booker.herokuapp.com/apidoc/index.html)

## Task 1
Based on the API above and your previous experience of working with API's, how would you go about testing it. Create a TEST-APPROACH.md and explain your test approach in as much detail as you can, taking everything into consideration (it's like a one page test plan containing a brain dump of your thought process).

## Task 2
To ensure the application is healthy, the DevOps team call the `/ping` endpoint every minute.
1. Fix the failing healthcheck test
1. Suggest any improvements

## Task 3
In order to present the name of the person who has made the booking. The API must return booking information based on the booking id e.g. `/booking/1`.    
1. Get a booking by id and check booking details

### Testing tips
When writing the tests remember the test should be able to run without any manual data setup and also cleanup any data after the test
