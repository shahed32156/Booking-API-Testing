# Booking-API-Testing

**Booking API Testing Collection Link:** https://www.postman.com/abdullahshahed/workspace/booking-api-workspace/collection/29211991-849d2002-4528-477b-b360-6b035ba11116?action=share&creator=29211991&active-environment=29211991-e4828e0f-359d-44a9-ba0d-1e5bc8aec880  

**Booking Environment Link:** https://www.postman.com/abdullahshahed/workspace/booking-api-workspace/environment/29211991-e4828e0f-359d-44a9-ba0d-1e5bc8aec880?action=share&creator=29211991&active-environment=29211991-e4828e0f-359d-44a9-ba0d-1e5bc8aec880

API stands for** Application Programming Interface.** An API is a bridge that allows different software applications to talk to each other. I tested a Booking API with verious request(GET, POST, PUT, PATCH, DELETE, HEAD and OPTIONS).

I performed API Testing using the API link below:

**API URL:** [https://restful-booker.herokuapp.com](https://restful-booker.herokuapp.com/)

To get the users, 

**GET:** [https://restful-booker.herokuapp.com/booking](https://restful-booker.herokuapp.com/booking)

**GET:** The GET method is used to retrieve data from the server. (I retrieved data from the Booking API)

**POST:** The POST method is used to create new resources. (I created data in the Booking API using an authorization token)

**PUT:** The PUT method is used to replace an existing resource with an updated version. (I updated or modified the existing data for a particular bookingid in the Booking API using an authorization token)

**PATCH:** The PATCH method is used to update an existing resource partially. (I updated or modified a single key-value pair for a particular bookingid in the Booking API using an authorization token)

**DELETE:** The DELETE method is used to remove data from a database or API. (I deleted existing data for a particular bookingid from the Booking API using an authorization token)

**HEAD:** The HEAD method is like a GET request, but it only retrieves the headers, not the response body. (I used it to ensure that the API or URL is working correctly)

**OPTIONS:** The OPTIONS method is used to determine what HTTP methods are allowed for a particular resource. (I used it to check whether GET, POST, PUT, PATCH, and DELETE requests are allowed and working correctly)

I also created environments and used global variables in Postman to easily access data, avoiding the need to repeatedly search, create, modify, and validate data manually.
I have also worked with assertions to validate the Status Code, Response Time, Response Size, Request Size, Content-Type, and Content-Length, and identified the passed and failed test results.
