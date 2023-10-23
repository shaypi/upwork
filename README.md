# **Recruiteq Main Website and Dashboard Open Issues Requiring Resolution**

## Needs to be fixed/improved:

### **_Main Website_**

1. - [ ] We need to use "rem" units for fonts. Maybe also for padding/margin/width/height. Currently, fonts are only handled by media queries, and everything looks very large on both mobile and desktop, not only the fonts but also buttons, boxes, and sections. So, using "rem" for width/height can fix this (you can use "vh" or "vw" units).

2. - [ ] HomePage: Book A Demo - Change the card content, and verify if the form has been sent to our Admin panel and our email company.
3. - [ ] HomePage: Candidate Registration - Need to verify that all social networking APIs and email registration are working, If a user registers with an email need to add Email Verification.
4. - [ ] HomePage: Employer Registration - Need to verify that all social networking APIs and email registration are working If a user registers with an email needs to add Email Verification.. Also, need to **fix** the Website field to allow adding the URL without "www" or "https://www". Need to update the industry as per this link: https://github.com/Recruiteq-io/Recruiteq-portal/issues/108.
5. - [ ] HomePage: Candidate and Employer Login - Verify that all social networking APIs and email login are working.
6. - [ ] HomePage: Search job by keyword is **not** working anymore - need to verify that it accurately provides results.
7. - [ ] HomePage: Filter by category - need to **verify that it accurately provides results.** Add geolocation service to the search area on the home page and job pages with the following links: https://docs.mapbox.com/playground/ and https://docs.mapbox.com/mapbox-gl-js/example/locate-user/. Also, need to fix a bug in the Role field.
8. - [ ] HomePage: After pressing the search button, the selected field should be presented in the Advanced Filter on the jobs page.
9. - [ ] HomePage: Counters - Compare the counters to the database to ensure accuracy.
10. - [ ] HomePage: Jobs cards - Verify that all content is aligned (aligned with the skills section ). The "Load more" button shows cards of different sizes, which needs to be fixed. Pressing "Share" should first open a login page. "Load more" should show four more cards instead of all job cards, and after pressing "show more," there should be an additional "show less" button to reduce the displayed cards. When pressing "show less," it should scroll back to the job cards.
11. - [ ] HomePage: Twitter - Convert it to "X" (the new social networking symbol).
12. - [ ] HomePage: Subscribe - Verify if the form has been sent to our Admin panel and our email company.

13. - [ ] HomePage: Homepage customization - Improve the entire homepage by changing the font, and website colors, and adding more content, similar to what's seen here: https://breezy.hr/ using https://iconscout.com/. Add a "Product" button to the toolbar and include the exact pages as found in the dropdown menu.

14. - [ ] JobsPage: Verify that all filters are working in the Advanced Filter and providing accurate results.
15. - [ ] JobsPage: Verify that the share button works as expected. When pressing the share button and selecting one of the social networking options, it should automatically add the job introduction content, image generator, job hashtags, and user referral link.
16. - [ ] JobsPage: Only display the first 6 jobs, and when scrolling down, automatically load more jobs on the page.
17. - [ ] JobsPage: Verify that all icon skills are displayed.
18. - [ ] Article: Require an **accurate estimation of the time required to read the article** found at https://dev.to/michaelburrows/calculate-the-estimated-reading-time-of-an-article-using-javascript-2k9l.
19. - [ ] Article: Address and enhance the loading time concerns on the article page and the admin panel article posting page.
20. - [ ] Article: Address the issue of the article URL - it should present a unique URL for each article.
21. - [ ] Article: Centralize the "Load More" button.
22. - [ ] HomePage: When trying to register with the same email address this should say, Email already registered.

### **_Common Dashboards Features_**

1. - [ ] Notification using WebSocket and socket.io: Refer to issue [link](https://github.com/Recruiteq-io/Dashboard/issues/13).
2. - [ ] Messenger Functionality: Refer to issue [link](https://github.com/Recruiteq-io/Recruiteq-portal/issues/39).
3. - [ ] Messenger - Missing Candidate/Employer (user) metadata. Refer to issue #25.
4. - [ ] Messenger - Missing features such as file upload and read receipts to track when messages have been read by the recipient.
5. - [ ] Messenger - Improve the chat card (the "Type a message" area should be within the card).
6. - [ ] Messenger - User activity: Add a user status activity (Online, Offline). Include an option allowing users to set their status, such as Busy, On Vacation, or Offline. Reference: [link1](https://stackoverflow.com/questions/32134623/socket-io-determine-if-a-user-is-online-or-offline) and [link2](https://medium.com/@ruveydayilmaz/handle-users-online-offline-status-with-socket-io-e92113c07eac).
7. - [ ] Messenger - Add an option to mark unread messages (should be in bold) and provide an option to mark read messages as unread.
8. - [ ] Messenger - Missing messenger popup like LinkedIn, please check the following - LinkedIn-like Messaging App.
9. - [ ] Messenger - Missing messenger group chats.
10. - [ ] Calendar Integration - Confirm the completion status of the Calendly logic integration using the provided GitHub link: [link](https://github.com/Recruiteq-io/Recruiteq-portal/issues/65).
11. - [ ] Interview Availability - Provide users with the flexibility to set their interview availability by choosing:
    1. - [ ] The starting day of the week when they are available.
    2. - [ ] The ending day of the week when their availability ends.
    3. - [ ] The specific hours within those days when they can conduct interviews.
12. - [ ] Require enhancement of UI/UX design and transformation of the note's appearance to align with the following exemplar [link](https://github.com/Recruiteq-io/Dashboard/issues/15).
13. - [ ] Two-Factor Authentication:
    - - [ ] Only email authentication is currently operational. Need to verify WhatsApp, SMS, and FingerPrint authentication.
14. - [ ] Replace instances of "Twitter" with "X".
15. - [ ] Add an option to edit the background on employer and candidate profiles.
16. - [ ] After the login, you need to rename the Profile on the toolbar to Dashboard.
17. - [ ] On the candidate and employer dashboard, add a homepage logo to redirect you to the homepage.
18. - [ ] On the candidate and employer, change the envelope logo to messenger (need to act like LinkedIn).
19. - [ ] Replace "Welcome back to Recruiteq Harman Porter" with "It's great to have you back at Recruiteq {Placeholder} of the user's full name.
20. - [ ] Logout Issues:
    - - [ ] Occasionally, it might prevent you from logging out and instead redirect you to the dashboard page.
    - - [ ] When a user logs out, they should also log out from any other open tabs in their browser.
21. - [ ] Gear Icon:
    - - [ ] Align the location of the icon with the rest of the icons.
    - - [ ] Ensure the gear will be like the following [link](https://zone-ui.vercel.app/).
22. - [ ] Calendar: Update this component (design and code) to the latest version 5.3.
23. - [ ] Main Menu: Increase the icon and the string (button name) size.

24. - [ ] Employer and Candidate offer - Candidate Contract Review and Edit [link](https://github.com/Recruiteq-io/Dashboard/issues/29).

25. - [ ] Employer / Candidate - candidate's summary story https://github.com/Recruiteq-io/Dashboard/issues/34
26. - [ ]  Replace the "Email me" with Notify me on the Notifications settings
27. - [ ] Close Account does not work - We need to discuss this option 
28. - [ ] It takes a long time until Company Logo or Profile Picture

### **_Employer Dashboards_**

1. - [ ] Notification - Refer to issue [link](https://github.com/Recruiteq-io/Dashboard/issues/13).
2. - [ ] Automation - Refer to issue [link](https://github.com/Recruiteq-io/Recruiteq-portal/issues/43).
3. - [ ] Verify the provided code for the Image Generator and ensure it functions similarly to [link](https://www.tuxpi.com/photo-effects/wanted-poster).
4. - [ ] Within "Company Distribution," incorporate three features.
    - - [ ] Automatically create new users by uploading a company CSV containing First name, Last name, Email address, Phone number, Title, etc. User information will be updated accordingly.
    - - [ ] Implement a Company Distribution list for sending automated emails based on the company's chosen schedule.
    - - [ ] Move the CSV card to the Scheduler area and improve the UI by:
        - - [ ] Decreasing the card size: Remove space around the cards to make them more compact.
        - - [ ] Adding a title to each card: This will help users understand the functionality of each card at a glance.
        - - [ ] Adding a tooltip.
5. - [ ] Score Report: The candidates' management page showcases a comprehensive score breakdown for each candidate based on the alignment between the candidate's profile and the job description. Further details can be found at [link](https://github.com/Recruiteq-io/Recruiteq-portal/issues/44).
    - - [ ] The score is divided into five categories: skills, years of experience, salary expectations, work experience, and education.
    - - [ ] The maximum achievable score is 100, distributed across these five categories.
    -   [ ] Report examples https://github.com/Recruiteq-io/Dashboard/issues/41
6. - [ ] Campaign - [link](https://github.com/Recruiteq-io/Recruiteq-portal/issues/48).
    1. - [ ] Provide the estimation of people reached per day only when the user selects the budget, start and end dates, and required skills.
    1. - [ ] Campaign Page - Managing the current Campaigns.
    1. - [ ] This needs to be discussed with Yagel.
7. - [ ] Reports / Invoice Creator:
    - - [ ] Employer invoice generator [link](https://github.com/Recruiteq-io/Dashboard/issues/17).
    - - [ ] Need to check Download reports as CSV and Download Invoice buttons are working.
    - - [ ] Need to check Transaction History and Budget are working as well.
8. - [ ] Hiring Team Roles:
    - - [ ] Highlight that the feature is still inoperative and requires attention. Refer to: [link](https://github.com/Recruiteq-io/Dashboard/issues/12).

> 9. - [ ] Kanban view in the Manage Candidate page: [link](https://github.com/Recruiteq-io/Dashboard/issues/19). Resource for the Kanban - [link](https://minimals.cc/dashboard/kanban).

10. - [ ] Employer Dashboard Analytics: The growth should start from 0 to 1 (with at least 10 rows) and need to be dynamically updated.
11. - [ ] Address and improve load time issues on the Manage Jobs.
12. - [ ] Address and improve load time issues on the Manage Candidates.
13. - [ ] Address and improve load time issues on the Manage Interviews.
14. - [ ] Align the card size for the entire dashboard.
15. - [ ] When Updating a new job (Edit job) and pressing on the Update job, this should redirect you to the Manage Jobs page.
16. - [ ] Missing field with a checkbox. Guest/Candidate parking [link](https://github.com/Recruiteq-io/Dashboard/issues/30).

18. - [ ] Need to improve the offer card [link](https://github.com/Recruiteq-io/Dashboard/issues/31).

19. - [ ] Employer Profile:
    - - [ ] Improve it by adding options to add pictures, and videos, or make posts (similar to [link](https://minimals.cc/dashboard/user)) and share them on social networking platforms.
    - - [ ] Missing the entire country phone number excitation and missing a way to type the letter in the box.
    - - [ ] Missing a complete TimeZone list and missing a way to type the letter in the box.
    - - [ ] In Why work with us missing box extend (increase decrease option).
    - - [ ] Social Links - Not saving the changes.
    - - [ ] Two Factor Authentication 2 - Not working anymore.
20. - [ ] Manage Jobs:
    - - [ ] Fix the job titles - this should contain the Leader field and role feild. if in the leader filed is non this will present only the role name.
    - - [ ] Edit job looks broken, can not update Leader and Skills fields. When trying its show white page.
    - - [ ] View Job post looks very much broken.
    - - [ ] In the Review Candidates section, pressing on a candidate should open their candidate profile.
    - - [ ] Need to verify "Add Co-Worker" flow is working.
    - - [ ] Once you make the job as a Boost ad feature, need to verify it moves to the Advertising page.
21. - [ ] Profile Completion Progress Bar: [link](https://github.com/Recruiteq-io/Dashboard/issues/21).

22. - [ ] Activity Analytics Dashboard: [link](https://github.com/Recruiteq-io/Dashboard/issues/26).

23. - [ ] Devskiller digital skills assessment integration - We need to be able to integrate Devskiller into our system.

24. - [ ] Post A New Job - [link](https://github.com/Recruiteq-io/Dashboard/issues/33).
25. - [ ] Fix the Affiliates by Sites in the Dashboard page
25. - [ ] Fix the sharing option in the articles page
26. - [ ] Automation - Align the design to look like the Job Introduction. In the options, the default will be "---Select Option---".
28. - [ ] Automation - In the Distribution feature need to add a placeholder as well
27. - [ ] Automation - Need to fix the UI UX of the Company Distribution page. Need to bring down the Upload CSV and add a title for each card.
29. - [ ] Manage Candidate - Need to verify that filters are working and that verify Interview is working as expected.
30. - [ ] Employer Profile:
    - - [ ] Missing Stripe in the credit card option, missing USDT api gateway.
    - - [ ] Need to verify that the reports (Weekly Summary, Transaction history, and Balance are working)
31. - [ ] Verify Employer - Hiring flow https://github.com/Recruiteq-io/Dashboard/issues/36

32. - [ ] Cross-Process Candidate Status Tracking https://github.com/Recruiteq-io/Dashboard/issues/28


### **_Candidate Dashboards_**

1. - [ ] On banking - the withdrawal should show the current balance (should be dynamic).
2. - [ ] In the candidate dashboard need to limit the featured jobs card to max 10 jobs and show only the active jobs.
3. - [ ] Need to improve the Recommended Jobs on the candidate dashboard. You should move the bookmarks flag to the upper right corner and increase the size of the "Apply Now" button.
4. - [ ] Recommended Jobs search field needs to be with round edges.
5. - [ ] Need to verify all counters.
6. - [ ] Bookmarks jobs look very much broken.
7. - [ ] Dashboard page the Featured Jobs area should only present the Active jobs.
8. - [ ] Recommended Jobs popup card only shows part of the job description.
    - - [ ] Profile Completion Progress Bar: [link](https://github.com/Recruiteq-io/Dashboard/issues/22).
    - - [ ] Affiliation Program: Refer to the following link [link](https://github.com/Recruiteq-io/Dashboard/issues/27).
9. - [ ] Auto-fill a user profile using a candidate's resume using AI and machine learning: [link](https://github.com/Recruiteq-io/Dashboard/issues/20).
10. - [ ] Candidate / Affiliation Analytics: [link](https://github.com/Recruiteq-io/Recruiteq-portal/issues/34).
    - - [ ] Need to fix the profile visits, including missing weekly and daily data.
    - - [ ] The cake chart should dynamically change by region.
11. - [ ] Include "Skills" in the candidate settings
12. - [ ] Missing Calender Icon on the right corner of the toolbar. Update this component (design and code) to the latest version 5.3.
13. - [ ] The Profile Picture on the setting page looks very much odd, please fix it.
14. - [ ] Availability - https://github.com/Recruiteq-io/Dashboard/issues/40

15.  - [ ]  Candidate - Incognito application https://github.com/Recruiteq-io/Dashboard/issues/32


### **_Admin Dashboards_**

1. - [ ] Admin Panel reports page [link](https://github.com/Recruiteq-io/Dashboard/issues/18).
2. - [ ] Missing Referral withdraw and Hired withdraw (signing bonus) in the withdraw page on the Admin dashboard.
3. - [ ] Remove the Profile Completeness bar
4. - [ ] Verify User Statistics is working with real data
5. - [ ] Verify Affiliation Statistics is working with real data
6. - [ ] Verify Active Users is working with real data
7. - [ ] Verify CV's Counter is working with real data

8. - [ ] Admin - Employer - Job Description Templates - https://github.com/Recruiteq-io/Dashboard/issues/35

9. - [ ] Paypal fund holder - https://github.com/Recruiteq-io/Dashboard/issues/38
11. - [ ] New Added Jobs and Paid Promotion Jobs are missing the "Position" column in the table.
13. - [ ] Need to verify Employer and Candidate and Jobs profiles are fully functional and are aligned to the profiles schema. 
14. - [ ] There are missing Messanger in the Admin panel.
15. - [ ] In the posting page remove the post button from the top left corner, when clicking on it its redirects you to an empty page.
16. - [ ] The Search in the post is not working.
17. - [ ] There is no option to edit a post.
18. - [ ] Missing Referral withdraw and Hired withdraw (signing bonus) in the withdraw page on the Admin dashboard.
19. - [ ] Remove the Profile Completeness bar

### **Infrastructure**

1. - [ ]  Containerize everything as microservices.
   - - [ ] Homepage Micro Frontend 
   - - [ ] Employer Dashboard Micro Frontend
   - - [ ] Candidate Dashboard Micro Frontend
   - - [ ] Admin Dashboard Micro Frontend:
   - - [ ] Notification using socket.io
   - - [ ] Messanger using socket.io
   - - [ ] Score report using AI machine learning
   - - [ ] Payment transactions using PayPal, strip and USDT
   - - [ ] Employee Activity Analytics Dashboard
   - - [ ] Incognito Apply Feature
   - - [ ] Template Management Service
   - - [ ] Candidate Cross-Process Status Tracking




