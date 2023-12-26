# Recruiteq.io Website Improvement Plan

## Main Website

1. **Refactor Main Website**
   - Implement a complete refactor of the main website to match the design template [here](https://preview.themeforest.net/item/ogeko-human-resource-solutions-wordpress-theme/full_screen_preview/42298857?_ga=2.78094420.1386368033.1703437700-581143993.1694022298&_gac=1.86221546.1703437981.CjwKCAiAyp-sBhBSEiwAWWzTnqmx-YMRCIh-fFw7guzC5RoJLs9H5VVaKq4NW4jEo4VdTOYS5Pm_YhoCYyMQAvD_BwE).

2. **Use "rem" Units for Fonts and Dimensions**
   - Implement the use of "rem" units for fonts, padding, margin, width, and height to ensure a consistent and responsive design across different devices.

3. **Employer and Candidate Registration**
   - Employer registration restricted to Microsoft, Google, LinkedIn APIs, or company email.
   - Candidate registration with Facebook, Twitter (X), Google, GitHub APIs, or email.

4. **Combine Free Text and Category Search**
   - Integrate free text and category search into a unified search area for better user experience.

5. **Jobs Page Share Functionality**
   - Verify and enhance the share button on job pages to automatically include job introduction content, image generator, hashtags, and user referral link.

6. **Article Reading Time Estimation**
   - Implement a feature to estimate the reading time of articles, using the method described [here](https://dev.to/michaelburrows/calculate-the-estimated-reading-time-of-an-article-using-javascript-2k9l).

7. **Job Posting Enhancements**
   - Set the company name as a symbolic link to the company profile.
   - Create dedicated job pages for each job.

8. **Company Profile and Analytics**
   - Improve the visual appeal of the company profile.
   - Implement analytics for tracking views on company profiles during job searches and through referral links.

9. **HomePage Enhancements**
   - Verify the accuracy of category filters.
   - Integrate geolocation services on the home page and job pages.

## Common Dashboards Features

### Messenger (socket.io)

10. **Complete Messenger Features**
    - Finalize remaining work on messenger functionality, including file upload, read receipts, and overall completion.

11. **Enhance Chat Card**
    - Improve the chat card design, ensuring the "Type a message" area is within the card.

12. **User Activity Status**
    - Implement user activity status (Online, Offline) with user-settable options (Busy, On Vacation, Offline).

13. **Message Management**
    - Add options to mark messages as unread and mark read messages as unread.
    - Introduce a messenger popup similar to LinkedIn's messaging app.
    - Implement messenger group chats.

### Calendar Integration

14. **Calendly Logic Integration**
    - Confirm completion status of Calendly logic integration using the provided GitHub link.

15. **Interview Availability**
    - Allow users to set interview availability by specifying starting and ending days of the week and specific hours.

16. **UI/UX Enhancements for Notes**
    - Enhance UI/UX design and transform the notes section.

17. **Update Calendar Component**
    - Update the calendar component (design and code) to version 5.3.

18. **Employer and Candidate Offer**
    - Review and edit candidate contracts in the employer dashboard.
    - Implement a candidate's summary story.

19. **Close Account Functionality**
    - Investigate and discuss the non-functional close account option.

## Employer Dashboard

20. **Company Distribution Features**
    - Enable automated user creation via CSV upload.
    - Implement a Company Distribution list for automated email scheduling.

21. **Score Report**
    - Create a comprehensive score breakdown for candidates based on profile-job alignment.

22. **Kanban View**
    - Integrate a Kanban view for managing candidates.

23. **Image Generator**
    - Verify code functionality to generate images similar to [tuxpi.com](https://www.tuxpi.com/photo-effects/wanted-poster).

24. **Reports/Invoice Creator**
    - Check functionality of invoice generator, report downloads, transaction history, and budget tracking.

25. **Hiring Team Roles**
    - Highlight that the feature is inoperative and needs attention.

26. **Enhance Candidate Profile**
    - Include a missing checkbox field for Guest/Candidate parking.

27. **Employer Profile Enhancements**
    - Allow picture and video uploads and post sharing on social platforms.

28. **Profile Completion Progress Bar**
    - Review and enhance the profile completion progress bar.

29. **Activity Analytics Dashboard**
    - Implement an activity analytics dashboard.

30. **Devskiller Integration**
    - Integrate Devskiller into the system.

31. **Stripe and USDT API**
    - Verify the presence of Stripe and USDT API for employer profile transactions.

32. **Employer-Hiring Flow**
    - Verify the employer-hiring flow.

33. **Cross-Process Candidate Status Tracking**
    - Implement cross-process candidate status tracking.

34. **Enhance Employer Profile**
    - Address the issues outlined in the enhancement request.

## Candidate Dashboard

35. **Banking Withdrawal Display**
    - Dynamically show the current balance during withdrawals.

36. **Featured Jobs Card Limit**
    - Limit featured jobs card to 10 and display only active jobs.

37. **Recommended Jobs**
    - Improve the layout of recommended jobs, move bookmarks flag, and increase the size of the "Apply Now" button.

38. **Affiliation Program**
    - Implement the features specified in the affiliation program request.

39. **Auto-fill User Profile**
    - Use AI and machine learning to auto-fill user profiles from resumes.

## Admin Dashboards

40. **Admin Panel Reports**
    - Provide a link to the admin panel reports page.

41. **Withdraw Page Enhancements**
    - Add missing referral and hired withdrawal options on the admin dashboard.

42. **Remove Profile Completeness Bar**
    - Remove the profile completeness bar from the admin dashboard.

43. **Verify Dashboard Statistics**
    - Ensure user statistics, affiliation statistics, active users, and CV counter work with real data.

44. **Job-related Enhancements**
    - Verify the functionality of new added jobs and paid promotion jobs.

45. **Employer and Candidate Profiles**
    - Verify that profiles are fully functional and aligned with the schema.

46. **Messenger Integration**
    - Address the missing messenger in the admin panel.

47. **Admin Registration Tracking**
    - Implement registration tracking as outlined in the enhancement request.

## Infrastructure

48. **Microservices Containerization**
    - Containerize all components as microservices, including homepage, employer dashboard, candidate dashboard, admin dashboard, notification system, messenger, score report, payment transactions, employee activity analytics, incognito apply feature, template management service, and candidate cross-process status tracking.

49. **Website Flow**
    - Review and address issues outlined in the website flow document.

This improvement plan outlines the remaining work required for the Recruiteq.io recruiting platform. Each item is detailed with specific actions to be taken, ensuring a comprehensive

 enhancement of the website and its dashboards.
