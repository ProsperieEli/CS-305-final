# CS-305-final

# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial services company that helps individuals create planning tools for their retirement, 401k, and other forms of financial needs. As well as being our client for this project. Artemis recruited me to help ensure that their company's application was properly secure and protected. The company main issue stemmming from the presence of software vulnerabilities. Weak hashing implementations and insecure communiction protocols being some of the vulnerabilities detected. 

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

My main focus was to indentify vulnerabilities in the companies code base. Once those those vulnerbilities were found. My focus shifted to either suppressing those that were not of high priority and the false-positives. As well as ensure the coding database was up-to-date to reduce the risk of running into an exposed system software. 

The main reason it's important to create secure coding is to protect against sensitive information being exposed due to easily accessible databases. In Artemis Financial's case, that could be PPI such as social security numbers, bank accounts & routing numbers, and tax information. This information is critical both to the company and the customers that trust them with this information. Having proper security in place snrues that this information is locked tight. Giving both the company and users a trust in company reputation. This also protects the company from legal issues should any issues arise so long as they follow the correct laws in place. 

# Which part of the vulnerability assessment was challenging or helpful to you?

For me personally, I believe my hardest struggle was the supression file and the Maven-dependency check. For the suppression file, I felt it was difficult to know how to properly suppress a vulnerability that was giving a false-positive. However, after enough time with it, I believe I have a strong understanding of the concept. As for the Maven-dependency check. it gave me the most challenge only for the first two assignments as I didn't realize I needed an API key to properly access the dependency. Which meant I also needed to change the environment to run the files. 

Overall, both were overcome. However, I believe these two stands as my most challenging segments.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

The main ways I increased the layers in security were through things such as the use of HTTPS with SSL/TLS certificates, using the principle of least privilege, and improving the cryptoraphic hashing algorithms to SHA-256. Going forward into the future. I believe I would use industry standards of OWASP guidelines for selecting my mitigation techniques and the static code analysis tools alongside the Maven-dependency check to assess vulnerabilities. 

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

The main way I checked to see if I had correctly refactored the code I was working on was through reviewing logs to see if there was any different behavior, re-running vulnerability scans, and testing my endpoints. After each refactoring cycle, I specifically checked that the code was working and no new vulnerabilities were showing. 

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Some of my tools are as follow:
<ul>
  <li>Maven Dependency Checks</li>
  <li>OWASP industry security frameworks</li>
  <li>SSL/TLS certificates</li>
</ul>

All of these can be helpful going forward in my ever growing journey of secure coding. 

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I feel somethings from this course I can take away is my knowledge of vulnerbilities and how to access and understand their meaning. Knowing how to complete a dependency check and view all the known vulnerabilities within a software is a major component in handling security and maintaing secure coding practices. I believe Project 2 shows this excellently and I would happily share it with future employers. 
