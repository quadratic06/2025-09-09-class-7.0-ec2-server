---
tags:
  - IT/DevSecOps
  - IT/Cloud/AWS
aliases:
created: 2025-09-20
last-modified:
---
Note Create: [[2025-09-20]]
⬅ [[AWS Class 7.0 - Week 1 - Creating Security Group & EC2 Instance]]
➡ [[AWS Class 7.0 - Week 3 - Command Line, File Management, and GitHub]]
[[Class 7 Lesson Summaries]]

---
# [[2025-09-16|Week 2 - Class 7 ZION: AWS and The Borg TUE 16 SEP]] ![](https://youtu.be/W_0rAcmh_D8?list=PLzfyR91ut1X3Dtxbub2F2kUuRrPK7_-Gs)

## Class Lesson: 2025-09-16
 
 AWS Regions Map [https://awsgeek.com/AWS-Regions/](https://www.awsgeek.com/AWS-Regions/) ![[Pasted image 20260501154734.png]]
 There is no Region in [[Russia]] because it states that any data residing in the cloud has to be accessible by the Russian Gov't.
### Lesson Summary: 2025-09-16
- Created a spending budget in AWS to limit monthly spending fees incurred by the usage AWS resources.
- Enabled additional Regions in AWS for usage.
- Created a security group to enable HTTP and SSH access to EC2 instance with a  create key pair, which also host a webpage on Apache server that was installed via user data script.
- Accessed an EC2 instance using SSH via the EC2 Instance Connect, then use ping command to ping IP address 8.8.8.8 (google site) to ensure internet connection.
- Created a template from an EC2 instance, then modifications to the template to generate different version of the template.

---
# [[2025-09-20|Week 2 - Class 7 ZION AWS - SAT SEP 20]] ![](https://youtu.be/rUEspUoOZdo?list=PLzfyR91ut1X3Dtxbub2F2kUuRrPK7_-Gs)
## Class Discussion: 2025-09-20

- Talked about how [[Donald Trump|Trump]] gave us a leg up because of his $100k tax on [[H-1B1 Visa]]
	- makes them like 100x times more expensive
- going to make less competition in the market
- we should be able to get jobs in 2026 May-July timeframe

DEI was suppose to be for black people, but it benefitted white women mostly, so getting rid of it really didn't affect black community. I know our community is upset but DEI didn't help us overall.

We'll be doing beginner to intermediate [[Artificial Intelligence|Ai]] in class 7
## Class Lesson: 2025-09-20

#Linux/Commands 
`ping -c 20 8.8.8.8`
- `-c <#>` tells the command to terminate after 8 executions

To enable/disable "*Auto Assign IP address*" it will be done in the subnet settings
### Troubleshooting
Issue: Every time try to use Instance Connect it receives an error that *"Failed to connect to your instance. Error establishing SSH connection to your instance."*
- The EC2 instance is running and the webserver/webpage is working.

Problem: The system clock and the AWS time was out of sync.

Solution: The system on the student's computer was not synced to the correct time. So he just went into clock settings then did automatic sync and the SSH connection worked.
### Lesson Summary
*Same as last class*

---
# [[2025-09-21|Week 2 - Class 7 ZION AWS: Student-led Sundays SEP 21]] ![](https://www.youtube.com/watch?v=Cdkr2AVTryk&list=PLzfyR91ut1X3Dtxbub2F2kUuRrPK7_-Gs&index=81&pp=iAQB)
## Class Discussion: 2025-09-21
## Class Lesson: 2025-09-21
Didn't have to take any notes
Same content as previous notes above

~~Completed all steps in EC2 exercise after class [[2026-05-03]]~~
~~Need finish reading chapter 2 of Bahga~~
~~completed~~
### Lesson Summary
