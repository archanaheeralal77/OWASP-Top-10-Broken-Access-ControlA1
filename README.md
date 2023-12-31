<img width="869" alt="Screenshot 2023-09-04 at 6 56 46 PM" src="https://github.com/archanaheeralal77/OWASP-Top-10-Broken-Access-ControlA1/assets/127080874/c6e5efd5-789c-4fba-8031-f621abb361df">
<img width="796" alt="Screenshot 2023-09-04 at 6 57 42 PM" src="https://github.com/archanaheeralal77/OWASP-Top-10-Broken-Access-ControlA1/assets/127080874/b17d5243-debb-49ac-aec2-1455df2b671c">
<img width="796" alt="Screenshot 2023-09-04 at 6 57 42 PM" src="https://github.com/archanaheeralal77/OWASP-Top-10-Broken-Access-ControlA1/assets/127080874/4c8d3b8f-d70e-4e35-82c3-976be91371b7">

**Attacker can perform if there is weakness in Access Control**

•	Unauthorized access to sensitive information

•	Inappropriate creation or deletion of resources

•	User impersonation

•	Force browsing

•	Privilege escalation

•	Path traversal

•	CSRF

•	Exposure of WSDL File Containing Sensitive Information


**How to Test?**

To identify if the weakness is present or not we can perform below:

1. DAST - Run Dynamic scanners.
2. SAST - Run Source code scanners.
4. Manual Testing - You can perform manual testing to find the weakness (example - www.abc.com/../../etc/passwd/)
5. Automation Testing - You can use automation tool like Burp Suite to perform the testing you can use Intruder and repeater both to test(Repeater can be used to test app by using multiple payload. Intruder can be used to modify the request and check the response.)
6. Fusser/Fussing

**How to Mitigate?**

1. Limiting CORS (Cross-Origin Resource Sharing) usage.

2. Use Least Privilege.
   
3. Deny Access By Default
   
4. Enable Role-based Access Control

5. Enable Permission-Based Access Control

7. Utilize Identity and access management (IAM) in AWS & Azure.


**CIA Consequences:**

**Confidentiality** – attacker can read/access the sensitive file/data

**Availability** – Attacker can delete/remove the sensitive file/data.

**Integrity** – Attacker can modify the sensitive file/data



