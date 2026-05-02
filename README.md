API Testing Project – Restful Booker
Project Overview: 
This project demonstrates comprehensive API testing performed on the Restful Booker API using Postman. The objective is to validate API functionality, ensure data integrity, and verify responses through automated test scripts.

API Tested:
Restful Booker API: https://restful-booker.herokuapp.com/

Tools & Technologies:
Postman
JavaScript (Postman Test Scripts)

Test Coverage: The following API endpoints and methods were tested:

POST – Create Booking (Valid)
POST – Token Generator
GET – Get Booking (Valid ID)
GET – Get Booking (Invalid ID)
GET – Get All Booking IDs
GET – Get Booking (Non-Numeric ID)
GET – Get Booking Details
PUT – Update Booking
DELETE – Delete Booking

Testing Approach:
✔ Functional Testing:
Verified all API endpoints functionality
Ensured correct request-response behavior
✔ Positive Testing:
Tested API with valid data inputs
Verified successful responses and expected outputs
✔ Negative Testing:
Tested API with invalid inputs (invalid ID, non-numeric values)
Verified proper error handling and failure responses

Validations Performed:
✅ Status Code Validation (200, 201, 400, 404)
✅ Response Body Validation
✅ JSON Schema / Structure Validation
✅ Response Time Validation

Environment Variables:
Created and used environment variables in Postman .Managed dynamic values such as:
Base URL
Booking ID
Authentication Token

Sample Test Scenarios:
Verify booking creation with valid data
Validate error response for invalid booking ID
Check update booking functionality
Verify deletion of booking
Validate authentication token generation
Ensure response time is within acceptable limits
