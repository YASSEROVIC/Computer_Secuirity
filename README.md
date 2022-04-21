# Computer_Secuirity
This repository is for computer security Project - CIS 3353

## Overall Testing
Overall testing was conducted utilizing the Open Web Application Security Project (OWASP)  Juice Shop, which is intended to show vulnerabilities and be exploited to learn best practices in real-world environments.
Areas tested in this project (that could potentially affect businesses significantly) were:
1.	Injection: user data is not validated, filtered, or sanitized by the application
2.	Broken Authentication (BA): Utilizing stolen or typical passwords for users and administrators
3.	Sensitive Data Exposure: 
4.	Broken Access Control: exploitation of access controls utilizing tools that need to be activly scanned for
5.	Cross-Site Scripting (XSS): Target for users browsers

## Using

Making this project by using following :

- [Linux Kali](https://www.kali.org/)

- [Juice Shop 13.0](https://github.com/juice-shop/juice-shop)

- [ Burp Suite Community Edition ](https://portswigger.net/burp/communitydownload)

## Installation
after download Juice Shop on your Linux : 
1. Install [ node.js ](https://github.com/juice-shop/juice-shop#nodejs-version-compatibility)
2. Run 
```bash
git clone https://github.com/juice-shop/juice-shop.git --depth 1 
```
(or clone your own fork of the repository)
3. Go into the cloned folder with cd juice-shop
4. Run 
```bash
npm install
```
(only has to be done before first start or when you change the source code)
5. Run
```bash
npm start
``` 
6. Browse to
```http
 http://localhost:3000
 ```
## Explaination

Here you can find the PDF file we test the vulnerabilities step by step.

[ Download PDF File ](https://github.com/YASSEROVIC/Computer_Secuirity/blob/main/Voul_on_J_S.pdf)