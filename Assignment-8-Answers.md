# Answers to Assignment 8 Part 3

Add your answers to the questions in Assignment 8 Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
pillow (specifically version 9.4.0).
2. Which CVE is linked to this vulnerability?
CVE-2023-44271
3. What remediation steps do you suggest?
1. Upgrade to the up-to-date version, 2. Run applications that use pillow in isolated environments, such as containers. 3. Ensure that any image files processed by pillow are validated before processing
   
### Vulnerability 2:
1. Which vulnerability are you addressing?
sqlparse (specifically version 0.3.1)
2. Which CVE is linked to this vulnerability?
CVE-2024-4340
3. What remediation steps do you suggest?
1. update the sqlparse package 2. Implement strict input validation for SQL inputs processed by sqlparse to avoid complex or malformed inputs. 3. Monitor logs and performance
