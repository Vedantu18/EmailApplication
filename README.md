# Project Title:

Java Email Application


## 1. Project Description:

Using JavaMail API to send emails using SMTP from Java applications:

1. without authentication, 
2. with TLS Authentication,
3. with SSL Authentication and Email attachment and image.


## 2. Tech Stack:

- Java 9
- JavaMail API
- Gmail SMTP server


## 3. Installing:

i. Clone the git repo

```
https://github.com/AAdewunmi/Java-Email-Application.git
```

ii. Open project folder

iii. Explore

😎


## 4. How To Use:

To send emails:

1. without authentication -> Run in IDE -> ```src/main/java/com/application/SimpleEmail.java```, 
2. with TLS Authentication -> Run in IDE -> ```src/main/java/com/application/TLSEmail.java```,
3. with SSL Authentication and Email attachment and image Run in IDE -> ```src/main/java/com/application/SSLEmail.java```.


## 5. JavaMail API Troubleshooting Tips: 

1. ```java.net.UnknownHostException``` comes when your system is not able to resolve the IP address for the SMTP server, it might be wrong or not accessible from your network. For example, GMail SMTP server is ```smtp.gmail.com``` and if I use ```smtp.google.com```, I will get this exception. If the hostname is correct, try to ping the server through command line to make sure it’s accessible from your system.


![Screenshot 2023-01-08 at 08-49-37 JavaMail Example - Send Mail in Java using SMTP DigitalOcean](https://user-images.githubusercontent.com/15172744/211188503-23c8cd16-a151-485a-a204-dc6daf65225b.png)

2. If your program is stuck in Transport send() method call, check that SMTP port is correct. If it’s correct then use telnet to verify that it’s accessible from you machine, you will get output like below.

![Screenshot 2023-01-08 at 08-49-10 JavaMail Example - Send Mail in Java using SMTP DigitalOcean](https://user-images.githubusercontent.com/15172744/211188520-0b7e3b80-5253-46fe-b8b8-923526d178d9.png)


## 6. Contributing:

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## 7. Original Creator:

Author:  Pankaj (Developer and author at DigitalOcean)
 
Tutorial Title:  JavaMail Example - Send Mail in Java using SMTP

Tutorial URL: https://www.digitalocean.com/community/tutorials/javamail-example-send-mail-in-java-smtp

Date: August 3, 2022
