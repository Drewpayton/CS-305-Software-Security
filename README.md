# CS-305-Software-Security

Artemis Financial is a consulting company that develops individualized financial plans for their customers. These financial plans included things like savings, retirement, investments, and insurance. Artemis Financial wanted to modernize their custom software, by using the most current and and effective software. Looking to security, Artemis wanted to add a file verification step to their web application for secure communications. 

I did an OWASP dependency check on Artemis Financial code base and found they were using an outdated system that was leading to various security vulnerabilities. It is important to code securely because there are people with malicious intent and you would not want sensitive information getting in their hands. Software security adds trust between a company and their users, allowing for growth and a more positive outlook on that company. 

The part that was most difficult was choosing the right hashing algorithm for the specific needs. I didn’t want to choose a hashing algorithm that wouldn’t work for them, or could be a vulnerability, or the hashing algorithm takes too long to hash the information.

I also checked after I implemented the hashing algorithm with another OWASP dependency check to make sure no other vulnerabilities were added to the code base.

Things like Integrated Development Environment, Owasp, StackOverflow and much more were all great resources and tools that I used in the current project. I think those would be helpful in future assignments when dealing with security.

There are plenty of ideas I can show employers that revolve around this assignment. I used an Owasp dependency check to search for vulnerabilities to find ways to decrease the amount of risks in the code base. Navigated eclipse ide to update the code base with a hashing algorithm. Used spring boot with maven to build and run as a java application. Researched hashing algorithms to incorporate SHA-256 for file encryption. Created certificates to make a secure and encrypted communication between my computer and the server.
