# 🌐 Web Security Labs

> Part of [🎯 Offensive Security Portfolio](../README.md)

![Focus](https://img.shields.io/badge/Focus-Web%20Exploitation-red?style=for-the-badge&logo=owasp)
![Platform](https://img.shields.io/badge/Platform-PortSwigger-orange?style=for-the-badge&logo=burpsuite)
![Burp Suite](https://img.shields.io/badge/Tool%20Used-Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)

Hands-on exploitation of OWASP Top 10 vulnerabilities with real-world attack patterns and impact-driven write-ups.

---

## 🚀 Highlights

- Focus on real-world attack patterns
- Short, impact-driven reports

## 🧠 Covered Skills

- 💉 SQL Injection (data extraction, auth bypass)
- 🔓 Broken Access Control
- 🖥️ Cross-Site Scripting (stored, reflected)
- 🛡️ Input validation bypass
- 🔍 Understanding backend behavior

---

## 💉 SQL Injection

- [SQL injection vulnerability in WHERE clause allowing retrieval of hidden data](./sql-injection/retrieve-hidden-data.md)
- [SQL injection attack, querying the database type and version on Oracle](./sql-injection/querying-database-version-oracle.md)

## 🔓 Broken Access Control

- [Insecure direct object references](./broken-access-control/insecure-direct-object-references.md)
- [Multi-step process with no access control on one step](./broken-access-control/multi-step-process-with-no-access-control-on-one-step.md)

## 🖥️ XSS (Cross-Site Scripting)

- [Reflected XSS into a JavaScript string with angle brackets HTML encoded](./xss/javascript-string-angle-brackets-html-encoded.md)
- [Stored XSS into anchor href attribute with double quotes HTML-encoded](./xss/href-attribute-double-quotes-html-encoded.md)

## 🔄 CSRF (Cross-Site Request Forgery)

- [CSRF where token validation depends on request method](./csrf/token-validation-depends-on-request-method.md)
- [CSRF where Referer validation depends on header being present](./csrf/referer-validation-depends-on-header-being-present.md)

## 🌐 SSRF (Server-Side Request Forgery)

- [SSRF with filter bypass via open redirection vulnerability](./ssrf/ssrf-filter-bypass-via-open-redirection.md)

---

## 📂 Structure

| Folder | Content |
|---|---|
| `/sql-injection` | SQLi exploitation |
| `/xss` | XSS exploitation |
| `/csrf` | CSRF exploitation |
| `/broken-access-control` | Broken Access Control exploitation |
| `/ssrf` | SSRF exploitation |
| `/img` | Evidence (screenshots) |

---

> ⚠️ All labs are performed in a controlled environment for educational purposes.