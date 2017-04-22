## Clickjacking HW Grading (15 points total)
Homework challenges can be found at http://clickjacking-challenges.r7.io/

## Part 1 - Vulnerabilities (13 points)
Level 1: 3 points

Level 2: 3 points

Level 3: 5 points

Style: 2 points

The webpages you will be creating clickjacking attacks for are http://clickjacking-challenges.r7.io/level/1 /level/2 /level/3. Level 2 and 3 pages take 1 URL parameter: name. The name parameter specifies your UW NetID. This URL is the one you will be embedding in your iFrame on the clickjacking page. The goal is to trick a victim admin (me) into browsing to your page and clicking on something that secretly submits the form of the page in the iFrame. When you test your clickjacking attack your name and the phrase "unavailable" will appear, but when I click on it a the request will properly resolve and I can verify your attack.

TL;DR - To earn full points on the challenges you must craft a webpage that convinces a victim (me) to click somewhere on the page and in doing so submit the form with your information.

## Part 3 - The Report (2 points)
- Description (1 point)
	- What is clickjacking and why is it bad?
- Mitigations (1 point)
	- Give a mitigation recommendations for stopping clickjacking. A couple sentences - what to do, how it works, and why you would choose that mitigation over others.

This must be submitted as a txt file. Please no PDFs or Word docs!

## Deliverables
A .zip file containing:

1. An HTML page I can open in Firefox that entices me to click somewhere on the page and triggers a clickjacking attack against the level 1 button.
2. An HTML page I can open in FIrefox that entices me to click somewhere on the page and triggers a clickjacking attack against the level 2 form with your UW NetID in it.
1. An HTML page I can open in Firefox that entices me to click somewhere on the page and triggers a clickjacking attack against the level 3 form with your UW NetID in it.


## Due Date
The whole HW (vulnerabilities and report) are due at 11:59pm (23:59) Friday April 29th 2017

## Notes
Please include links to any pages, guides, tutorials, people, or anything you used to help you figure out these challenges. Please do not cheat or trade answers! If you gently/fairly help one another out make sure to credit the people that helped you in your report. Give credit where credit is due.

No automated tools!