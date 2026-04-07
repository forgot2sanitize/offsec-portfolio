# 🌐 PortSwigger Web Security Academy

> 🔐 Focus: Web Exploitation • Auth Bypass • Input Injection

Collection of lab write-ups demonstrating practical exploitation of web vulnerabilities and real-world impact.

---

## 🚀 Highlights

- Focus on real-world attack patterns
- Short, impact-driven reports

## 🧠 Covered Skills

- SQL Injection (data extraction, auth bypass)
- Cross-Site Scripting (stored, reflected)
- Input validation bypass
- Understanding backend behavior

---

## SQL Injection

- [Retrieve hidden data](./sql-injection/retrieve-hidden-data.md)
- [Database version (Oracle)](./sql-injection/querying-database-version-oracle.md)

## XSS

- [Reflected XSS into a JavaScript string with angle brackets HTML encoded](./xss/javascript-string-angle-brackets-html-encoded.md)
- [Stored XSS into anchor href attribute with double quotes HTML-encoded](./xss/href-attribute-double-quotes-html-encoded.md)

## CSRF

- [CSRF where token validation depends on request method](./csrf/token-validation-depends-on-request-method.md)
- [CSRF where Referer validation depends on header being present](./csrf/referer-validation-depends-on-header-being-present.md)

---

## 📂 Structure

- `/sql-injection` - SQLi exploitation
- `/xss` - XSS exploitation
- `/csrf` - CSRF exploitation
- `/img` - Evidence (screenshots)

---

> ⚠️ All labs are performed in a controlled environment for educational purposes.