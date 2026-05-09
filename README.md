#Test Plan for demoblaze.com
________________________________________


1. Objective
Verify that the core shopping features on demoblaze.com function correctly for a standard user  -- including login, product browsing, add to cart, and checkout. The goal is to ensure users can complete a purchase without errors.

2. Scope - what will be tested
User login & logout Product browsing Add to cart Remove from cart Checkout form Navigation links Responsive layout Form validation
 
3. Out of scope - will NOT be tested
Payment processing Admin panel Email notifications Performance testing Security / penetration 
________________________________________

4. Test types
Functional    UI / visual 
Negative testing  ·  Usability
Cross-browser (Chrome, Firefox)
 
5. Test environment
URL: demoblaze.com
Browser: Chrome 124, Firefox 125
Device: Desktop + Mobile (375px) 

6. Tools
Test cases: Google Sheets
Bug tracking: Jira (free tier)
Screenshots: Snagit / Lightshot
 
7. Timeline
Test case writing: Day 1
Test execution: Day 2
Bug reporting + summary: Day 3 

________________________________________

8. Entry & exit criteria
Start testing when...
Site is accessible · Test cases are written · Test account is created on demoblaze

Stop testing when...
All 20 test cases executed · All bugs logged · Summary report written

9. Risks & assumptions
Demo site may be unstable or reset periodically  ·  No real payment data will be used  ·  Testing is manual only (no automation)  ·  Site data may not persist between sessions 
