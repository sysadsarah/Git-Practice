**Week of April 10th Notes**

Here of some terms I need to know for the Cloud Practitioner test.

ElastiCache
Amazon ElastiCache is a web service that makes it easy to deploy, operate, and scale an in-memory data store or cache in the cloud. The service improves the performance of web applications by allowing you to retrieve information from fast, managed, in-memory data stores, instead of relying entirely on slower disk-based databases.

AWS Elastic Beanstalk 
Elastic Beanstalk makes it easy for developers to quickly deploy and manage applications in the AWS Cloud. Developers simply upload their application code, and Elastic Beanstalk automatically handles the deployment details of capacity provisioning, load balancing, auto-scaling, and application health monitoring.

Amazon SQS
Amazon Simple Queue Service (Amazon SQS) offers a reliable, highly-scalable hosted queue for storing messages as they travel between applications or microservices. It moves data between distributed application components and helps you decouple these components.

SWF
Amazon Simple Workflow Service (SWF) is a web service that makes it easy to coordinate work across distributed application components. Amazon SWF enables applications for a range of use cases, including media processing, web application back-ends, business process workflows, and analytics pipelines, to be designed as a coordination of tasks.

AWS X-Ray 
AWS X-Ray helps developers analyze and debug distributed applications in production or under development, such as those built using micro service architecture. With X-Ray, you can understand how your application and its underlying services are performing.


*Week of April 3rd Notes**

**Wed**

Today I learned the difference between vertical scaling and horizontal scaling. Vertica scaling (“scaling up”), you're adding more compute power to your existing instances/nodes. So if I go from T2 to T3 I scaled up. In horizontal scaling (“scaling out”), you get the additional capacity in a system by adding more instances to your environment, sharing the processing and memory workload across multiple devices. If I add EC2 instances, Im scaled out.
What do I find interesting? Alot of the AWS terms and policies are 
![Load Balancing](https://social.dnsmadeeasy.com/wp-content/uploads/2021/04/Screen-Shot-2021-04-19-at-4.18.23-PM.png)

Today I learned that AWS has added some categories to their support plan. Enterprise On-Ramp is not a service that we have seen in our coursework. 
Enterprise On-Ramp is for those who have production/business critical workloads in AWS and want 24x7 access to technical support and need expert guidance to grow and optimize in the Cloud. With Enterprise On-Ramp, you get 24x7 technical support from high-quality engineers, tools and technology to automatically manage health of your environment, consultative architectural guidance delivered in the context of your applications and use-cases, and a pool of Technical Account Managers (TAMs) to coordinate access to proactive / preventative programs and AWS subject matter experts. 

**Tues**

Notes of some terms I needed to learn for the Cloud Practitioner test. 
ElastiCache?
Amazon ElastiCache is a web service that makes it easy to deploy, operate, and scale an in-memory data store or cache in the cloud. The service improves the performance of web applications by allowing you to retrieve information from fast, managed, in-memory data stores, instead of relying entirely on slower disk-based databases.

AWS Elastic Beanstalk makes it easy for developers to quickly deploy and manage applications in the AWS Cloud. Developers simply upload their application code, and Elastic Beanstalk automatically handles the deployment details of capacity provisioning, load balancing, auto-scaling, and application health monitoring.

Amazon SQS
Amazon Simple Queue Service (Amazon SQS) offers a reliable, highly-scalable hosted queue for storing messages as they travel between applications or microservices. It moves data between distributed application components and helps you decouple these components.

SWF
 Amazon Simple Workflow Service (SWF) is a web service that makes it easy to coordinate work across distributed application components. Amazon SWF enables applications for a range of use cases, including media processing, web application back-ends, business process workflows, and analytics pipelines, to be designed as a coordination of tasks.

AWS X-Ray helps developers analyze and debug distributed applications in production or under development, such as those built using micro service architecture. With X-Ray, you can understand how your application and its underlying services are performing.


** Week of March 27th Notes**
 (notes)

Wednesday we started our day taking a practice test for the practitioner exam.
Though the class passed, individually, were are at varying levels. I will
Continue to study until I get all the questions correct. 

After lunch, we had a graduate from a past cohort come to speak to our class.
Her name was Muriah and she explained her job search and interview experiences.
Some pointers from today’s guest Muriah:
* Indeed is a good resource. It provided her with the most interviews.
* Use key terms that match your the job you’re applying for on your resume.
* Thank the interviewer for their time before introduing yourself. 
* Body language and a great attitude goes a long way.
I for one appreciate the the visits from former students as it gives me a sense of encouragement.

Later the gathered into groups and did labs from the Jaws module. 
One lab prompted us to install python from the command line. Then we needed to get a Json policy by only using the AWS CLI. This was difficult. With some assistance, we used arn=$(aws iam list-policies --scope Local --query "Policies[*].Arn" --output text); aws iam get-policy-version --policy-arn $arn --version-id v1.  This allowed the team to complete the lab. 

On Tuesday I told the class that I listened a the darknet diaries podcast called Jason’s, Pen test. Jason 
talked about doing pen tests back in the days when he had to physically 
break into companies server room and limited access spaces. He mentioned 
using a blow up doll on one of his missions. He lied on the ground to blow up the doll 
until sensor activated. I added a commit to Gitlab. I created a branch on one 
of my repositories on Github and made some additions there.
I started the Python Module

**Python Module**

I learned that GoLang is a language that google created. 
Primitive date type is data that are built into a coding language with no modification.
Composite data type combines multiple data types into a single unit.
Programming is a way to automate processes. Programming languages specify a way to communicate 
directions to a computer. Software is written into a text file by using a programming language, 
which is either interpreted or compiled when it is run. Data is typed so that the interpreter or 
compiler knows whether it is a string, integer, Boolean, or other data type.
A composite data type stores different types of data in a single variable.
Functions are collections of instructions that can be called repeatedly in a program.
Version control manages changes to computer programs, documents, or other collections of information.


---------------------------------------------------------------------------------------------------------------

**Week of March 20th**


Ticket A function is a piece of reusable code with a name. You use a function by:
* Calling by its name
* Including a list of one or more inputs called arguments, which are enclosed in parentheses
Python has several built-in functions that you can use to help you write more useful programs.
A collection of functions is called a library. Python’s collection of built-in functions is called the Python Standard Library.


**Week of March 20th**

Durning the presentation today we learned about how to secure the cloud. 
The discussion on the use symmetric keys vs asymmetric keys.
Symmetric encryption uses a private key to encrypt and decrypt an 
encrypted email. Asymmetric encryption uses the public key of the 
recipient to encrypt the message. Then, if the recipient wants to decrypt 
the message, the recipient will have to use their private key to decrypt.

The next presentation discussed API (Application Programming Interface). API provides a programmatic access to data
Or services. Venmo and Linkedin had API security breeches.  Nmap is a tool used by admins and hackers to scan networks
for open ports and search for active hosts on a network. 
Wireshark is used to scan for vulnerabilities. When scanning IP addresses, a decoy IP address should be used. 
Myles did a demonstration with ESXi. 
Shafan Sugarman included this photo for the class to see :
![Document Shared by Sugarman](images/Screenshot_2023-03-28_at_12.20.53_PM.png)

**Friday**


Today my group presented on the topic of Malware and AWS services 
to keep the cloud safe. We watched presentations by our classmates 
and learned a  bit. A topic that stood out to me during the presentations 
was pen testing. A penetration tester is responsible for finding security 
vulnerabilities, including determining which penetration testing method 
(Gupta, 2021) is best suited to the situation. This is a challenging task 
that requires advanced skills and knowledge. A penetration tester needs 
to be familiar with different hacking techniques and have in-depth network 
security knowledge. They must also know how to use various tools to assess 
the target system’s security posture.

![Pen-testing](https://www.eccouncil.org/cybersecurity-exchange/wp-content/uploads/2022/03/Penetration-Testing-Phases-1024x512.jpg) 

There are five penetration testing phases: reconnaissance, scanning, vulnerability assessment, exploitation, and reporting.Pen testers use tools to examine the target website or system for weaknesses, 
including open services, application security issues, and open source vulnerabilities.
![Pen-testing](https://www.satalytics.com.au/wp-content/uploads/2020/02/5-key-steps-in-Pen-testing-process.png)


What I learned: 
I  was looking at the last part of the security module and wanted to 
revisit the information about the AWS Trusted Advisor. Questions about this 
service keeps popping up on the Cloud Practitioner practice tests so I want to 
make sure I know what it is.
Trusted Advisor is an online resource to help you reduce cost, increase 
performance, and improve security by optimizing your AWS environment. 
It provides best practices (or checks) in five categories:
1. Cost Optimization – Save money on AWS by reducing unused and 
idle resources or making commitments to reserved capacity.
2. Performance – Improve the performance of your service by checking 
your service limits, ensuring that you take advantage of provisioned throughput, 
and monitoring for over-utilized instances.
3. Security – Improve the security of your application by closing gaps, 
activating various AWS security features, and examining your permissions.
4. Fault Tolerance – Increase the availability and redundancy of your AWS 
application by taking advantage of automatic scaling, health checks, multiple 
Availability Zones, and backup capabilities.
5. Service Limits – Check for service usage that is more than 80 percent of the service limit.
The status of the check is shown 
 
March 21st Notes Continued.
From the Test prep 
Amazon Aurora is a relational database management system (RDBMS) built for the cloud with full MySQL and PostgreSQL compatibility. Aurora gives you the performance and availability of commercial-grade databases at one-tenth the cost.
Amazon Aurora: enterprise class - works with mysql - 5x faster -automatic. 
Its best to have multiple AWS account.  Its part of the AWS best practice to do so. 
Spot instances get 90 percent discount! 
Your DNS is the service that translates your domain name into an IP address. AWS Route 53 is a smart DNS system that can dynamically change your origin address based on load, and even perform load balancing before traffic even reaches your servers.


Today we decided to choose Malware as our topic for the presentation on Friday. At the moment, the class is watching an AWS Cloud Practitioner test prep, in the Zoom lobby, thanks to Afnan. Simultaneously, I am doing some research for the  presentation and editing some slides. 

![alt text](https://www.bleepstatic.com/content/hl-images/2023/02/13/mortal-kombat.jpg)
## H2 Mortal Kombat Malware


From the security module, I learned about malware and Intrusion detection system. 
Malicious software (malware) is designed to cause harm to a computer system 
by interrupting one of the CIA triad elements: – Confidentiality – Integrity – Availability
Malware include: – Worms – Bots – Ransomware – Viruses

They get you by getting your information on a fake or insecure website, emails or 
removable devices, web links and more. 
Some antivirus programs include:• AVG • McAfee • Norton • Kaspersky. Use these to 
keep your computer safe. 

An intrusion detection system (IDS) is a hardware or software solution that monitors a 
network or a computer system to detect intrusions or malicious activity. When this kind 
of activity happens, the IDS generates alerts to notify security personnel.
An IDS can detect an attack by using different mechanisms, including the following:
• Anomaly-based detection – The IDS compares the current traffic pattern or system 
activity against established baselines for any deviation. • Signature-based detection – The IDS monitors and analyzes the traffic for known patterns 
of attack.

Today I learned about three types of encryption, and what and ACL is. The three typed of encryption include symmetric, asymmetric, and hybrid.  Symmetric encryption is less complex and less secure. It used when speed is the priority. Asymmetric encryption is more secure than symmetric encryption because different keys are used for the encryption and decryption processes. Its a slower process than symmetric encryption.  

An ACL is made of a list of permissions: it tells which users have access to which resources and which operations they are allowed. For example, a company might decide to define permissions based on job role. When someone new is hired, they automatically receive all the permissions that come with the role by being placed into the appropriate role group.

Victor reintroduced us to the Boolean method for job searching. He showed us how to search for jobs  and told us to use  LinkedIn, Indeed, Monster, Dice as well as a recruiter. The more job searching resources we use, the better chances we have in obtaining a job. For example, a company might decide to define permissions based on job role. When someone new is hired, they automatically receive all the permissions that come with the role by being placed into the appropriate role group.

![alt text](https://www.thesslstore.com/blog/wp-content/uploads/2020/11/how-encryption-works-symmetric-encryption.png)
