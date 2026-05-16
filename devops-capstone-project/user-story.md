# User Story Template

## Template
**As a** [Role]  
**I want to** [Feature/Action]  
**So that** [Benefit/Value]  

---

## Example User Story: Create Account
**As a** Microservice Consumer  
**I want to** create a new customer account  
**So that** I can manage customer information in the system  

### Acceptance Criteria
- **Scenario: Successful Account Creation**
  - **Given** the service is running and database is connected
  - **When** a POST request is made to `/accounts` with valid JSON data
  - **Then** the service should return HTTP status `201 CREATED`
  - **And** the response body should contain the created account details with a unique ID
