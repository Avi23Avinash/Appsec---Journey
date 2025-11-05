# AppSec Engineer Roadmap Journey

## Day 1
This repository contains my projects, notes, and labs as I learn Web Application Security.
 #### Skills I will learn:
- Web Application Security
- Threat Modeling
- OWASP Top 10
- Secure Code Review
- API Security
- CI/CD Security

#### Projects Coming Soon:
- Vulnerability Labs
- Writeups
- API Security Testing
---
## Day 2 – Burp Suite Basics

###  What is HTTP?
HTTP (**HyperText Transfer Protocol**) is the communication method used between a client (like a browser) and a server.  
It helps in sending **requests** from the client and receiving **responses** from the server.  
It is the **foundation of data exchange** on the web.

### 📤 What is a Request?
When I used **httpbin** with the **GET** method, I saw that the request was sent from the browser to the server asking for data.  
It included the **request URL**, **method (GET)**, and some **headers** like *User-Agent*.  
No body was sent because **GET** only retrieves information.

### 📥 What is a Response?
The response is what the server sends back after receiving a request.  
I saw a **status code `200 OK`**, which means the request was successful.  
The response body contained **JSON data** showing details like my IP address, headers, and the URL I accessed.

### Burp Proxy

- **Intercept ON:**  
  When Intercept is ON, Burp stops the request before it goes to the server.  
  I can see and edit the request before forwarding it.

- **Intercept OFF:**  
  When Intercept is OFF, the request goes directly to the server without stopping.  
  Burp just lets the traffic flow normally.

  ---

##  Day 3 – Browser & Postman Basics

###  Browser Basics

####  Cookies
Cookies are small pieces of data stored by the browser on behalf of a website.  
They help websites remember user sessions, preferences, or login states.  
Every time you revisit the same site, your cookies are automatically sent with the request.  
For example, when you log in to a site, your **session ID** is often stored as a cookie.

#### localStorage
`localStorage` stores data permanently in the browser, even after closing it or restarting the system.  
It’s mainly used to save non-sensitive information like theme preference or username.

#### session storage
sessionStorage is similar to localStorage, but the data lasts only until the tab is closed.
It is useful for temporary data that’s needed only during a single session.

#### postman basics
Postman is a tool used to test and explore APIs.
It allows you to send requests (like GET, POST, PUT, DELETE) and analyze responses easily.
Each request includes:
-URL: The API endpoint
-Headers: Information like Content-Type
-Body: Data sent in POST/PUT requests
##### HTTP Status Codes (Summary)

- **1xx →** Information  
- **2xx →** Success  
- **3xx →** Redirection  
- **4xx →** Client Error  
- **5xx →** Server Error

**Postman helps understand how client–server communication works without needing a browser**.
---
## Day 4 – HTML Fundamentals

- Completed learning all essential HTML concepts including elements, attributes, forms, and input types.  
- Practiced creating static web pages using **VS Code**, focusing on structure and readability.  
- Understood the role of **HTML in web application security**, such as input fields being potential points for injection or XSS attacks.  
- Learned about **semantic tags** (header, section, article, footer) for better page organization.  
- Gained clarity on how front-end structure connects with backend requests — an important foundation for AppSec testing.  
- Confident in reading and analyzing HTML source code to identify web components and request flow.

