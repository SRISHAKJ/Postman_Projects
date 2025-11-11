# Postman API Testing Projects

This repository showcases a set of **Postman API Automation Projects** created to validate RESTful services for functionality, authentication, and performance.  
These projects demonstrate real-world testing scenarios.

---

## Projects Overview

| No. | Project Name | Description | Tools & Features |
|-----|---------------|--------------|------------------|
| 1 | **API Testing Automation Suite (JSONPlaceholder)** | Automated validation of sample REST API endpoints (GET, POST, PUT, DELETE) for functional and regression testing. | Postman, Newman, HTML Report, JSON Data Validation |
| 2 | **Auth & Security API Testing** | Focused on testing authentication and authorization methods like API Key, OAuth 2.0, and Token-based authentication. | Postman, Environment Variables, Chaining Requests, Negative Testing |
| 3 | **Performance Testing for API (JMeter + Postman)** | Combined test suite for validating both functional and performance aspects of API endpoints using Postman and JMeter. | Postman, JMeter, HTML Dashboard Reports |

---

##  Related Repository

| Project | Description | Repository Link |
|----------|--------------|-----------------|
| **RESTful Booker API Automation** | Comprehensive end-to-end API test suite for the RESTful Booker platform with CI/CD and detailed reporting. | [View Repository](https://github.com/SRISHAKJ/restful-booker-api-tests.git) |

---

##  Tech Stack

- **Primary Tool:** Postman  
- **Automation Runner:** Newman  
- **Performance Tool:** Apache JMeter  
- **Reporting:** Newman HTML / Dashboard Reports  
- **Languages Used:** JSON, JavaScript (for assertions)  
- **Version Control:** Git & GitHub  

---

##  Key Highlights

- Covers API functionality, security, and performance validation.  
- Utilizes data-driven testing and chained request flows.  
- Produces detailed HTML and PDF reports for result analysis.  
- Demonstrates integration between Postman and JMeter for advanced testing scenarios.  

---

##  How to Execute

1. Clone the repository  
   ```bash
   git clone https://github.com/SRISHAKJ/Postman_Projects.git
2. Install Newman globally
   ```bash
   npm install -g newman
3. Run any collection
   ```bash
   newman run "CollectionName.postman_collection.json" -e "EnvironmentName.postman_environment.json" -r html
4. Open the generated report.html in your browser to view results.

##  Author

**SRISHA K J**
- **Quality Analyst (3+ Years of IT Experience)**
- **srisharohith@gmail.com**
  
---

This repository demonstrates professional API automation and performance testing practices using Postman and JMeter.
