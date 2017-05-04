## CSRF HW Grading (25 points total)
Homework challenges can be found at: http://csrf-challenges.r7.io/

## Part 1 - Vulnerabilities 13 points
- Level 1 will be worth 3 points
- Level 2 will be worth 4 points 
- Level 3 will be worth 5 points
- Level 4 will be worth 5 points

To earn full points on each challenge you must craft a webpage (for levels 1, 2, and 3) and a link with an XSS payload (for level 4) that when the admin goes to that page/link, it stealthily makes a request to the corresponding level page. This request MUST contain your UW NetID.

Example: You create a webpage for Level 1 that I (as the admin) will open. This webpage needs to automatically submit a request in the background, invisible to the user. The request needs to be sent to the Level 1 page on http://csrf-challenges.r7.io. This request is made on behalf of the Admin without them knowing. Make sure to put your UW NetID in the contents of the request so I can easily verify you.

TL;DR - for 100% you must turn in 3 pages and a URL/link that when opened/clicked on by the admin a request will be sent to their respective level page (level 1 to level 1 post page, level 2 to level 2 post page, etc). Be sure to include your UW NetID in the the request.

## Part 2 - The Report 8 points
- Description (2 point)
	- What is CSRF and why is it bad
- Test Steps (3 points)
	- 1 sets of test steps, for the top one you solved, that includes how you found the vulnerability and how it works.
	- This should be detailed enough that someone in the class who didn't solve the challenges could walk through the steps, be able to reproduce the vulnerabilities, know how they worked, and why they happened.
- Mitigations (3 points)
	- Give mitigation recommendations for 2 languages/frameworks
		- ASP.NET
		- Django
	- This should include a few sentences about how to properly mitigate CSRF and a code example for each framework/language
	- Include a link or two to further reading/reference for the "developer"

## Deliverables
A .zip file containing the following:

1. An HTML file that opens in Firefox and triggers the CSRF attack against the lvl 1 page and make a post on the lvl 1 wall.
2. An HTML file that opens in Firefox and triggers the CSRF attack against the lvl 2 page and make a post on the lvl 2 wall.
3. An HTML file that opens in Firefox and triggers the CSRF attack against the lvl 3 page and make a post on the lvl 3 wall.
4. A .txt file containing a URL that I can copy and paste into Firefox that will trigger an attack against the lvl 4 page and make a post on the lvl 4 wall.

## Due Date
You can submit your malicious pages and link to me on Tuesday April 25th by 5:30pm (17:30) via email and I will run them. This will allow you to verify whether your CSRF attacks worked, and if they didn't work, give you a few days to tweak them.

The whole HW (vulnerabilities and report) are due at 11:59pm (23:59) Saturday April 29th 2017.

## Notes & Hints
Submit forms, even if you are not authenticated, and intercept the requests with Burp. This can give you a look at what is being sent to the server, so you can re-create that request in your malicious page.

For level 3 - pretend that the CSRF token is tied to the user (in a proper implementation it is). You all are anonymous users so you get tokens tied to no one, but the admin has a token tied to them. So requesting the form, grabbing the token attached to it, and dropping it in a payload will not work for level 3. See the next hint.

Don't assume just because there is a CSRF token that it is being checked properly on the server. Do some tests to verify that the token is being properly validated.

Please include links to any pages, guides, tutorials, people, or anything you used to help you figure out these challenges. Please do not cheat or trade answers! If you gently/fairly help one another out make sure to credit the people that helped you in your report. Give credit where credit is due.

No automated tools!

## Resources
http://www.troyhunt.com/2010/11/owasp-top-10-for-net-developers-part-5.html
https://www.owasp.org/index.php/Testing_for_CSRF_(OWASP-SM-005)
