# CS305

##Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a consulting company that develops individualized financial plans for their customers. The financial plans include savings, retirement, investments, and insurance.Specifically,they want to add a file verification step to their web application to ensure secure communications. 

##What did you do very well when you found your client’s software security vulnerabilities? 

When I found the vulnerabilites, I used a SHA 256 hashing to hash the string that was used to ensure that the communication is secure between Artemis and their client.  I also did a vulnerability check and addressed some of the security vulnerabilities. 

##Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

Security is perhaps the most important step to consider when building software. Consequences of security breaches are tremendous, they could mean loss of data, financial harm, loss of trust, or even a complete failure of a company. To prevent these disasters, security must be highly integrated when developing and maintaining a system.

##What part of the vulnerability assessment was challenging or helpful to you?

The challenging part of vulnerability assesment was configuriation as I had issues with the build, but through some trials and errors I was able to resolve the issues. The summary section in the dependency check  was very helpful in diagnosing and assesing the threat level.

##How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I’ve added multiple layers of security on different fronts. I made sure that the API connection is secure by creating a key store to generate a self-signed certificate using java keytool which allows the connection to operate on HTTPS as opposed to an HTTP browser. I ran a dependency check and update springboot to the latest version reducing the over all vulnerability by half.  I created a hash function to encrypt the strings for secure communication. 

##How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To make sure that my code was functional and secure, I made sure that everything was running smoothly without any bugs or errors. I ran dependency check after my changes to see if there was increase in numbers of vulnerabilties. . 

##What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I mostly used java as the programming language with Spring Boot Library for dependecy check and client/server management. I used key tool to generate certificate. 

##Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show the entire project to showcase my ability to  integrate SpringBoot, make api calls, and create certificates.
