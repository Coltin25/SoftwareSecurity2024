# SoftwareSecurity2024

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
- Artemis Financial is a financial consulting company that specializes in creating individualized financial plans for its customers. They requested that we better protect the company and its clients personal data by adding layers of security to their web application.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
- I was able to identify false positiives against the true security vulnerabilities in a timely manner. Its important to code securely to protect the code against attacks meant to leak information about their clients. The company's overall well-being is given a peace of mind for the compoany and reliablity to the customers.

Which part of the vulnerability assessment was challenging or helpful to you?
- Determining the false positives was the most challenging part of the vulnerability assessment however I learned how to address them correctly because of it.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
- I integrated certificate authorities as well as strengthened the large vulnerablilites, in the future I would include AES encryption or whatever the stronges encryption at the time is as well as force 2 factor verification for all associates that have access to change system.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
- I performed rigorous static and dynamic testing on the code to ensure that none of the dependencies could be exploited. Once the code was refactored i ran the code to validate that the code was still safe and operational.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
- I liked the maven dependency tool as well as the keytool for eclipse to create a certificate authority.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
- I would show the dependency checker and viewing false positives and showing how I could suppress the false positives and strengthen the other dependencies. 
