# 🔐 Lab 02: JWT Security Analysis

## Overview
This lab focuses on analyzing a JSON Web Token (JWT) to identify security weaknesses in authentication mechanisms.

##  Objective
To understand how misconfigured JWTs can lead to authentication bypass, privilege escalation, and data exposure.

## Tools Used
- jwt.io
- Postman
- Manual Base64 decoding

##  Approach
- Decoded JWT header and payload
- Analyzed signature configuration
- Tested token validation logic
- Reviewed expiration and payload data

##  Findings
- Use of `alg: none` allows signature bypass
- Sensitive data exposed in plaintext payload
- Expired tokens were still accepted
- Client-side trust of authorization fields

##  Mitigation
- Enforce strong signing algorithms (e.g., HS256, RS256)
- Validate token expiration strictly
- Avoid storing sensitive data in payload
- Never trust client-side token data

