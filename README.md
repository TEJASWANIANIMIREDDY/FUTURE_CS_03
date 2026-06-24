# API Security Risk Analysis

## Objective
To analyze a public API, identify common security risks, assess authentication and access control mechanisms, and provide remediation recommendations.

## API Tested
JSONPlaceholder

Base URL:
https://jsonplaceholder.typicode.com

Endpoints Tested:
- /users
- /posts
- /comments

## Tools Used
- Postman (Web Version)
- Microsoft Word
- JSONPlaceholder API

## Methodology
1. Reviewed API documentation.
2. Sent GET requests using Postman.
3. Inspected API responses and headers.
4. Identified security risks.
5. Classified risks based on severity.
6. Suggested remediation measures.

## Findings
- Open API Endpoint (Medium)
- Excessive Data Exposure (Medium)
- Missing Rate Limiting (Low)

## Conclusion
The JSONPlaceholder API was analyzed using Postman. Several common API security concerns were identified, including open endpoints, excessive data exposure, and lack of rate limiting. Although the API is intended for testing purposes, these observations demonstrate security risks commonly found in production APIs.
