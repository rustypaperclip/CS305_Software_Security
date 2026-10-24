# CS305_Software_Security
SNHU CS305

## 1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

- Artemis Financial is a financial consulting company that is responsible for the financial planning of its customers and covers a variety of financial products. Artemis wanted to modernize its software and scale it while addressing any potential security concerns. I was tasked with reviewing their legacy code base and assess any current vulnerabilities within. Once identified, I relayed the information to Artemis and developed a plan to correct these vulnerabilities.

## 2. What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?

- I conducted a manual code review and identified many vulnerabilities. These were documented and included outdated libraries and insecure communications. Ensureing strong coding security protects the data and information in transit which reduces potential business liability if a breach were to occur.

## 3. Which part of the vulnerability assessment was challenging or helpful to you?

- The most helpful was the OWASP dependency check while the most challenging was creating the SSL certificates.

## 4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

- For Artemis Financial's software I implemented layered security including HTTPS communications and SSL encryption. In the future I will leverage the dependency check tools and conduct enhanced penetration testing.

## 5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

- I verified the application ran successfully. I then re-executed the dependency check to verify no new vulnerabilities were introduced.

## 6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

- The Java keytool was helpful in generating my own certificate. The OWASP dependency check will be extremely helpful in the future.

## 7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

- This assignment will demonstrate to employers that I am able to implement HTTPS communications in addition to generating my own certificates. I can also demonstrate that I am knowledgeable on proper encryption implementation.
