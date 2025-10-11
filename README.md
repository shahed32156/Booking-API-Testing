### 💼 Project Title

Booking API Testing Using Postman

### 📝 Project Description

This project focuses on **API testing** of the Restful Booking API, a publicly available RESTful web service for practicing end-to-end testing of booking functionalities.    
Using **Postman**, various HTTP methods (GET, POST, PUT, PATCH, DELETE, HEAD and OPTIONS) and test scripts have been applied to validate different endpoints, ensure correct responses, assertions and verify data integrity in the booking system.

### 🎥 Project Video Link

```
https://drive.google.com/file/d/1Do-ruA_gBjrm4fSr0YxAOakiBh_jLYMC/view?usp=sharing
```

### 🚀 Features of API

- View booking Info
- Create bookings
- Generate the authorization/access token
- Update bookings info
- Update parial bookings info
- Delete bookings
- Check the API is working correctly
- Check the methods are allowed for a particular resource

### 🔗 Open your browser and navigate to

```
https://restful-booker.herokuapp.com
```

### 📜 Example Endpoints

```
- GET: /booking - Get or view the all booking info

- GET: /booking/{id} - Get or view the specific booking info

- POST: /booking - Create a new booking

- POST: /booking - Generate access token

- PUT: /booking/{id} - Update the booking info

- PATCH: /booking/{id} - Update the partial booking info

- DEL: /booking/{id} - Delete a booking

- HEAD: /booking/ -Check the API is working correctly

- OPT: /booking/ - Check the methods are allowed for a particular resource
```

### ⚙️ Steps to run the API using Postman

- Open the Postman
- Create a Collection
- Create 8 HTTP Request's method according to endpoints
- Create Environment for create Base URL and envirnment variables
- Create some necessary params on HTTP Request's methods like Content-Type, Accept and Cookies
- Some assertion performed on Post response script
- Finally Run the Collection and view the Response

### 🗂️ Project Structure

```
│  
└── Collections # Kind of directory where we create requests  
└──Environments # Environment variable where we create variables in perticuar environment    
└── Request # Send HTTP request to server  
└── Body # (Request Body) for Send Request  
└── Headers # Add Headers info  
└── Scripts # Write pre-request and post-response script    
└──  Response Body # Check the Response from server  
└── Headers # Check the Response Headers info  
└── Test Results # View test Results post-response scripts
```

### Tools & Technologies

- **Postman** → For sending requests and writing test scripts.  
- **JavaScript** (Postman Scripts) → For automating test validations.  
- **JSON** → For request body and response data handling.  
- **Environment Variables** → To store base URL, tokens, and booking IDs.

### 🔎 Observations

- Response status code of delete users info are not expected
    - Expected Status Code: 204 or 200
    - Actual Status Code: 201
    - Test Result: Failed
- Response massage of delete users info are not expected
    - Expected  Response Massage: Deleted
    - Actual Response Massage: Created
    - Test Result: Failed
- Otherwise all assertions, responses and test results are working fine.

### 🏁 Conclusion

This project successfully demonstrates how to perform end-to-end API testing using Postman — covering authentication, CRUD operations and response validation using asserion scripts.