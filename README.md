```
    _____   ____________     __ __ _________
   /  _/ | / / ____/ __ \   / // /<  / ____/
   / //  |/ / /_  / / / /  / // /_/ /___ \  
 _/ // /|  / __/ / /_/ /  /__  __/ /___/ /  
/___/_/ |_/_/    \____/     /_/ /_/_____/  
    --- Web Application Security ---       

``` 

# Description
This course will cover the ins and outs of web application security from the perspectives of the developer, administrator, and attacker. We will cover attacks from the all too common Cross-Site Scripting (XSS) attack through Cross-Site Request Forgery (CSRF), SQL Injection (SQLi), all the way to more advanced topics.
 
The goals of this course centers around familiarizing students with how to recognize a possible vulnerability, write a proof-of-concept, and provide helpful remediation so that a developer can properly mitigate the issue. The emphasis will be on hands-on learning and the students will be expected to think creatively as they face common defenses and work with unfamiliar frameworks and languages.

# Grading
Grade breakdown:
- hw: 60%
- midterm: 15%
- final: 25%

# Late penalty: 
- 10% daily, incremented in 10% steps (24hrs from time due)
- stops at 50% deduction
- final turn in no later than 2 weeks from due date
- all assignments due by start of last day of class

# Resources
- Suggested reading: Web Application Hacker's Handbook

# Correspondence:
- Please only use your UW email account for compliance reasons - I don't want a FERPA violation
- Write: "INFO 415 - (your subject header here)" in the subject line so I can filter it out

# Weekly Schedule

## Week 1 - Overview
- Tu - Introduction, overview, threat modeling
- La - Tools setup, traffic capture
- Th - Internet foundations, client-server communications, browser basics
- HW - Browsing by hand
- Reading
	- For HW
		- https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview
		- https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Evolution_of_HTTP
		- https://developer.mozilla.org/en-US/docs/Web/HTTP/Session
		- https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies
		- https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers
		- https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods
		- https://developer.mozilla.org/en-US/docs/Web/HTTP/Status
	- For next week
		- https://excess-xss.com/
		- WAHH Chapter 12
		- WAHH Chapter 3

## Week 2 - XSS
- Tu - XSS introduction
- La - Character encoding, unicode security, punycode domains
- Th - XSS filter bypass techniques
- HW - XSS challenges
- Reading
	- None

## Week 3 - XSS
- Tu - Regular expressions (regex)
- La - XSS practice
- Th - Advanced XSS payloads
- HW - Advanced XSS payloads
- Reading
	- WAHH Chapter 13 section on "Inducing User Action" (501-515)
	- http://www.troyhunt.com/2013/05/clickjack-attack-hidden-threat-right-in.html

## Week 4 - CSRF & Clickjacking
- Tu - CSRF
- La - Tor
- Th - Clickjacking
- HW - CSRF & Clickjacking challenges
- Reading
	- WAHH chapter 9

## Week 5 - SQLi
- Tu - SQLi introduction
- La - Social engineering
- Th - SQL and SQLi practice
- HW - SQLi challenges
- Reading
	- None

## Week 6 - SQLi
- Tu - Advanced SQLi techniques
- La - HW review
- Th - SQLi to full control
- HW - Midterm
- Reading
	- WAHH chapter 6
	- WAHH chapter 7

## Week 7 - Authentication
- Tu - Midterm review
- La - Canceled
- Th - Canceled
- HW - None, enjoy the breather
- Reading
	- None

## Week 8 - Crypto
- Tu - Canceled
- La - TBD
- Th - Common authentication flaws
- HW - Brute force, user enumeration, and timing attacks
- Reading
	- None

## Week 9 - Misc. Attacks
- Tu - Cryptography
- La - Authentication 2.0
- Th - OAuth 1.0 and business logic attacks
- HW - Golden bank pentest
- Reading

## Week 10 - Advanced Attacks
- Tu - Review
- La - Final
- Th - Final

## Final will be on the last day of class (lab + lecture [3 hrs])