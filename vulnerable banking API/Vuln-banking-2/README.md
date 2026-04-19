#  Lab 07: API Penetration Testing

##  Overview
This lab focuses on performing practical API penetration testing on a target application. 
The assessment simulates real-world attack scenarios to identify vulnerabilities in authentication, authorization, and input handling.

## Objective
To understand how attackers identify and exploit common API vulnerabilities such as broken authentication, improper input validation, and insecure endpoint configurations.

##  Tools Used
- Postman
- Burp Suite
- Browser DevTools
- JWT.io

##  Approach
- Mapped available API endpoints
- Intercepted and modified API requests
- Tested authentication and authorization mechanisms
- Manipulated request payloads and headers
- Analyzed API responses for inconsistencies and leaks

##  Findings
- Weak authentication mechanisms allowed improper access control
- API endpoints lacked proper validation checks
- Sensitive data could be exposed through insecure configurations
- Improper handling of user input increased attack surface

##  Mitigation
- Implement strong authentication and session validation
- Enforce strict input validation and sanitization
- Apply proper authorization checks on all endpoints
- Avoid exposing sensitive data in API responses

