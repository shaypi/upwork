# Recruiteq.io Website Improvement Plan

## Main Website

1. **Refactor Website Design**
   - Refactor the entire main website and pages to mirror the design of [this template](https://preview.themeforest.net/item/ogeko-human-resource-solutions-wordpress-theme/full_screen_preview/42298857?_ga=2.78094420.1386368033.1703437700-581143993.1694022298&_gac=1.86221546.1703437981.CjwKCAiAyp-sBhBSEiwAWWzTnqmx-YMRCIh-fFw7guzC5RoJLs9H5VVaKq4NW4jEo4VdTOYS5Pm_YhoCYyMQAvD_BwE).

2. **Use "rem" Units for Fonts**
   - Switch to "rem" units for fonts, padding, margin, width, and height to ensure consistency across different devices.

3. **Employer Registration Restriction**
   - Allow employers to register only via Microsoft, Google, and LinkedIn APIs or using a company email address.

4. **Candidate Registration Improvements**
   - Enable registration using Facebook, Twitter (X), Google, and GitHub APIs or an email address.

5. **Streamline Search Functionality**
   - Combine free text and category search in one area for a more user-friendly experience.

6. **Share Button Enhancement**
   - Verify and enhance the share button on the JobsPage to include job introduction content, image generator, job hashtags, and user referral link.

7. **Article Reading Time Estimation**
   - Implement an accurate estimation of the time required to read articles, like the one found [here](https://dev.to/michaelburrows/calculate-the-estimated-reading-time-of-an-article-using-javascript-2k9l).

8. **JobsPage Enhancements**
   - Set the company name as a symbolic link to the company profile.
   - Improve the visual appeal of the company profile.
   - Implement analytics for tracking views on the company profile and job positions from referral links.

9. **Dedicated Job Page**
   - Create a dedicated job page for each job based on the provided Figma screen.

10. **Homepage Improvements**
    - Verify the accuracy of the category filter on the homepage.
    - Add geolocation service to the search area on the homepage and job pages.

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

1. **Messenger Integration**
   - Complete remaining work on the Messenger feature using socket.io.

2. **User Metadata**
   - Address missing candidate/employer metadata as per the provided issue.

3. **Messenger Functionality**
   - Implement missing features like file upload and read receipts in the Messenger.
   - Improve the chat card design.

4. **User Activity Status**
   - Add user status activity (Online, Offline) with status options (Busy, On Vacation, Offline).

5. **Message Management**
   - Add options to mark messages as unread and bold.
   - Provide an option to mark read messages as unread.

6. **Messenger Group Chats**
   - Implement group chat functionality.

7. **Calendar Integration**
   - Confirm completion status of Calendly logic integration.

8. **Interview Availability**
   - Allow users to set interview availability, specifying start and end days and specific hours.

9. **UI/UX Enhancement for Notes**
   - Enhance the UI/UX design for notes.

10. **Calendar Component Update**
    - Update the calendar component to the latest version (5.3).

11. **Employer and Candidate Offer**
    - Review and edit candidate contracts in the Employer/Candidate dashboards.

12. **Profile Closing**
    - Investigate and resolve issues with the Close Account feature.

## Employer Dashboard

1. **Company Distribution Features**
   - Automatically create new users via CSV upload.
   - Implement a Company Distribution list for automated emails.

2. **Score Report**
   - Provide a comprehensive score breakdown for candidates based on alignment with job descriptions.

3. **Kanban View**
   - Implement Kanban view in the Manage Candidate page.

4. **Image Generator**
   - Verify and ensure functionality similar to the provided image generator.

5. **Score Report Details**
   - Divide the score into skills, experience, salary expectations, work experience, and education.
   - Set a maximum achievable score of 100.

6. **Report Examples**
   - Provide examples for reports.

7. **Campaign Management**
   - Implement features related to campaigns.

8. **Reports/Invoice Creator**
   - Verify functionality of the Employer invoice generator.
   - Check Download reports, Transaction History, and Budget buttons.

9. **Hiring Team Roles**
   - Address the inoperative feature related to hiring team roles.

10. **Missing Checkbox**
    - Address the missing checkbox issue related to Guest/Candidate parking.

11. **Enhanced Employer Profile**
    - Improve Employer Profile with options for pictures, videos, and posts.

12. **Profile Completion Progress Bar**
    - Implement and enhance the Profile Completion Progress Bar.

13. **Activity Analytics Dashboard**
    - Implement the Activity Analytics Dashboard.

14. **Devskiller Integration**
    - Integrate Devskiller into the system.

15. **Stripe and USDT API**
    - Verify the presence of Stripe and USDT API in the Employer Profile.

16. **Employer-Hiring Flow**
    - Verify the Employer-Hiring flow.

17. **Cross-Process Candidate Status Tracking**
    - Implement cross-process tracking for candidate status.

18. **Employer-Profile Enhancement**
    - Address the issues related to Employer-Profile enhancement.

## Candidate Dashboard

1. **Dynamic Balance Display**
   - Make withdrawal displays dynamic, showing the current balance.

2. **Featured Jobs Limit**
   - Limit featured jobs card to 10 and show only active jobs.

3. **Recommended Jobs Improvements**
   - Improve the layout of Recommended Jobs, moving bookmarks and increasing the size of "Apply Now" button.

4. **Affiliation Program**
   - Implement features related to the Affiliation Program.

5. **Auto-fill User Profile**
   - Integrate AI and machine learning to auto-fill user profiles using resumes.

## Admin Dashboards

1. **Admin Panel Reports**
   - Provide a link to the reports page in the Admin Panel.

2. **Withdraw Page Enhancements**
   - Add Referral withdraw and Hired withdraw features to the withdraw page.

3. **Profile Completeness Bar Removal**
   - Remove the Profile Completeness bar.

4. **User Statistics Verification**
   - Verify the functionality of User Statistics with real data.

5. **Affiliation Statistics Verification**
   - Verify the functionality of Affiliation Statistics with real data.

6. **Active Users Verification**
   - Verify the functionality of Active Users with real data.

7. **CV's Counter Verification**
   - Verify the functionality of CV's Counter with real data.

8. **Job Profile Alignment**
   - Verify that Employer, Candidate, and Job profiles align with the schema.

9. **Messenger Inclusion**
   - Include Messenger in the Admin panel.

10. **Missing Withdraw Features**
    - Address missing Referral withdraw and Hired withdraw in the Admin dashboard.

11. **Registration Tracking**
    - Implement Registration Tracking in the Admin dashboard.


## Infrastructure
1. **Microservices Containerization**
   - Containerize all components as microservices.

2. **Micro Frontends**
   - Implement micro frontends for the Homepage, Employer Dashboard, Candidate Dashboard, and Admin Dashboard.

3. **Notification System**
   - Implement a notification system using socket.io.

4. **Messenger Implementation**
   - Integrate messenger functionality using socket.io.

5. **AI Machine Learning for Score Report**
   - Incorporate AI and machine learning for generating score reports.

6. **Payment Transactions**
   - Ensure payment transactions work seamlessly with PayPal, Stripe, and USDT.

7. **Employee Activity Analytics Dashboard**
   - Implement an Employee Activity Analytics Dashboard.

8. **Incognito Apply Feature**
   - Implement the Incognito Apply feature.

9. **Template Management Service**
   - Develop and implement a Template Management Service.

10. **Candidate Cross-Process Status Tracking**
    - Implement cross-process tracking for candidate statuses.

## Website Flow

1. **Follow Website Flow**
   - Address issues related to the [website flow](https://github.com/Recruiteq-io/Dashboard/issues/47).
