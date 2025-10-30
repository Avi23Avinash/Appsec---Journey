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
