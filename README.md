Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address? 

Artemis Financial is a global financial consulting company. Due to its nature of the business, they urged to develop a secure environment to protect sensitive information of their clients. They wanted to examine the web application, identify vulnerabilities, and mitigate them. 

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing? 

I explained why encryption algorithms and hashing algorithms are important to secure transmission. The explanation also includes reasons behind my choices. For Artemis Financial, it is crucial to secure an environment. They handle sensitive information such as savings and investment, and clients’ personal information. A secure environment is a key for clients to give away such information to the business. 

What part of the vulnerability assessment was challenging or helpful to you? 

When it comes to remediation, upon reviewing vulnerabilities, I immediately noticed that they are due to unsupported versions of software. Reading descriptions of each vulnerability helped me to figure out exactly what needs to be remediated. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use? 

I increased layers of security by implementing the right version of software. It is important to continue integrating the latest version, as it likely contains mitigation over existing vulnerabilities. Useful tools are NVD and CVE, which have the latest information about vulnerabilities. Maven OWASP dependency check is useful to find vulnerabilities in a code. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities? 

I made sure by checking certificates on a client node. As configured on Eclipse, the certificate showed SHA256 hash algorithms. Maven OWASP dependency check is a great tool to see any vulnerability in a code. I made sure to rerun the report after refactoring the code, and confirmed there is no vulnerability in it. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks? 

Maven OWASP dependency check is useful because it goes through the code and checks with the latest information about vulnerabilities. Vendors’ software version information is also useful in understanding each upgrade. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment? 

I want to showcase a successful API with HTTPS connection. It is crucial to understand encryption algorithms and the work in the course will show my understanding in RSA protocol. It also showcases my ability to generate self-signed certificate successfully. 

 
