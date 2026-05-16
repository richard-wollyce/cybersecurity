---
title: "Secure Coding Practices"
description: "Principles for building secure software from the ground up."
---

# Secure Coding Practices

Security cannot be bolted onto an application after it is built; it must be designed into the architecture and written into the code. 

## 1. Input Validation
Never trust data from the user or the client side. 
- **Validate Everything:** Validate length, format, type, and range of all input.
- **Allow-listing over Block-listing:** It is always safer to define what is strictly *allowed* (allow-listing) rather than trying to define all the things that are *bad* (block-listing), because attackers constantly invent new bad inputs.

## 2. Output Encoding
Output encoding is the primary defense against Cross-Site Scripting (XSS).
- Before rendering user-supplied data in the browser, encode it appropriately for the context (HTML body, JavaScript variable, CSS, or URL).
- Most modern web frameworks (like React or Angular) handle basic context-aware encoding automatically, but developers must be careful when bypassing these protections (e.g., using `dangerouslySetInnerHTML`).

## 3. Parameterized Queries
The only foolproof way to prevent SQL Injection is to separate the SQL code from the user-provided data.
- **Use Prepared Statements / Parameterized Queries.** The database driver treats the user input strictly as data, not as executable code.
- Avoid building queries by concatenating strings.

## 4. Least Privilege
Applications, processes, and users should only have the minimum permissions necessary to perform their function.
- A web application's database user should not have administrative privileges over the database server.
- If an application only needs to read data, it should not have write permissions.

## 5. Fail Securely
When an application encounters an error, it should fail in a way that does not grant additional access or leak sensitive information.
- Never display raw stack traces or database errors to the end-user. Catch errors gracefully and log the details securely on the server.
