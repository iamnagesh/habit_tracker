# User Stories

## Table of Contents

1. [Template](#template)
2. [Login/registraion page](#login)

---
<a name="template"></a>
## Template
```
## Section Title
### Title
As a **user role**, I want _feature/goal_, so that _reason_.

#### Acceptance Criteria:
1. [Criteria 1]
2. [Criteria 2]
3. [Criteria 3]

#### Priority
_[High/Medium/Low]_
#### Story Points
_[Estimated Effort in Points]_
[Reason for estimating effort and assigning the story points]
#### Notes
- [Additional information or edge cases]

```
---
<a name="login"></a>
## Login/registraion page

### Account registration
As a **user**, I want _to register my name, username, age, and country_ so that I can _create an account and access the habit tracking features_ 

#### Acceptance Criteria
1. Users must be able to input their name, username, age, and country into a registration form.
2. The system should validate that all required fields are filled and display an error if any field is missing.
   - Ensure data input validations (e.g., username uniqueness, minimum/maximum age limit, password complexity constraints).
3. The system should provide a confirmation message upon successful registration.

#### Priority
_High_

#### Story Points:
_5_
[Reason for estimating effort and assigning the story points]

#### Notes:
- Users should be informed about privacy policies during registration.

### Account Login
As a **user**, I want _to log in using my username and password_ so that I can _access my account and track my habits_ 

#### Acceptance Criteria
1. Users must be able to input their username and password into a login form.
2. The system should validate the credentials and grant access upon successful login.
3. The system should not store credentials in the browser cache for security purposes.

#### Priority
_High_
#### Story Points:
_3_
[Reason for estimating effort and assigning the story points]

#### Notes:
- Users should be redirected to their account dashboard after a successful login.
- Display a loading indicator while credentials are being validated.

### Error Feedback on Login
As a **user**, I want _receive a message if I enter the wrong username or password_ so that _I know my login attempt was unsuccessful._ 

#### Acceptance Criteria
1. If the username or password is incorrect, the system should display a message indicating the issue.
2. The error message should not specify whether the username or password is invalid for security reasons.
3. Users should have the option to reset their password from the error feedback screen.

#### Priority
_High_
#### Story Points:
_2_
[Reason for estimating effort and assigning the story points]

#### Notes:
- Ensure feedback messages are clear and non-technical (e.g., "Invalid login credentials. Please try again.").

---

## Homepage

### View welcome message
As a **user**, I want to see a personalized welcome message with my name on the homepage,_ so that _I feel recognized and can confirm I am logged into the correct account.

#### Acceptance Criteria:
1. The welcome message should display the user's name.
2. The message should be visible on the homepage immediately after logging in.
3. The message should be personalized and dynamic, reflecting the current user's name.

#### Priority
High
#### Story Points
**3**
The effort is estimated to be moderate due to the need for integrating user data and ensuring dynamic content display.
#### Notes
- Ensure the welcome message is secure and does not expose sensitive user information.
- Consider edge cases where the user's name might be missing or incorrect.


### Display weekly progress
As a **user**, I want _to see my daily progress for each habit on the homepage,_ so that _I can easily monitor my progress._

#### Acceptance Criteria:
1. The homepage should display a section for daily progress of each habit.
2. The progress should be updated in real-time or at least daily.
3. The progress should be visually represented, such as through graphs or charts.

#### Priority
_Medium_
#### Story Points
_5_
The effort is estimated to be higher due to the need for data visualization and real-time updates.
#### Notes
- Ensure the progress data is accurate and up-to-date.
- Consider edge cases where there might be no progress data available.

### View completed habits
As a **user**, I want _to see a section for completed habits on the homepage,_ so that _I can track what I have already achieved._

#### Acceptance Criteria:
1. The homepage should have a dedicated section for completed habits.
2. The section should list all habits that have been completed.
3. The list should be easily accessible and visually distinct from other sections.

#### Priority
_Low_
#### Story Points
_2_
The effort is estimated to be low as it mainly involves displaying a list of completed habits.
#### Notes
- Ensure the completed habits section is updated accurately.
- Consider edge cases where no habits have been completed yet.

---

## Menu

### Access menu options
As a **user**, I want _to access a menu with options for configuring my habits, viewing reports, editing my profile, and signing out,_ so that _I can easily navigate to different parts of the app._

#### Acceptance Criteria:
1. The menu should be accessible from the homepage.
2. The menu should include options for configuring habits, viewing reports, editing profile, and signing out.
3. Each menu option should navigate to the corresponding section of the app.

#### Priority
_High_
#### Story Points
_5_
The effort is estimated to be moderate due to the need for integrating multiple navigation options and ensuring smooth user experience.
#### Notes
- Ensure the menu is easily accessible and intuitive to use.
- Consider edge cases where certain menu options might be restricted based on user permissions.


### Navigate to profile
As a **user**, I want _to access my profile to see my account information like name, username, member since,_ so that _I can have access to my account detials whenever necessary._

#### Acceptance Criteria:
1. The profile should be accessible from the homepage and from the menu options.
2. The displayed information should include user data and an option to signing out at the bottom.

#### Priority
_High_
#### Story Points
_5_
The effort is estimated to be moderate due to the need for integrating multiple navigation options and ensuring smooth user experience.
#### Notes
- Ensure the menu is easily accessible and intuitive to use.
- Consider edge cases where certain menu options might be restricted based on user permissions.


### Navigate to habits page
As a **user**, I want _to access the habits page from the menu,_ so that _I can configure and manage my habits._

#### Acceptance Criteria:
1. The habits page should be accessible from the menu.
2. The menu option for habits should be clearly labeled.
3. Navigating to the habits page should allow users to configure and manage their habits.

#### Priority
_Medium_
#### Story Points
_3_
The effort is estimated to be moderate due to the need for integrating navigation to the habits page and ensuring smooth user experience.
#### Notes
- Ensure the habits page is easily accessible and intuitive to use.
- Consider edge cases where the habits page might be empty or have limited functionality.

### Sign out from menu
As a **user**, I want _to sign out of my account using an option in the menu,_ so that _I can securely log out when I'm finished using the app._

#### Acceptance Criteria:
1. The menu should include a sign-out option.
2. Selecting the sign-out option should log the user out of their account.
3. The user should be redirected to the login page after signing out.

#### Priority
_High_
#### Story Points
_2_
The effort is estimated to be low due to the need for integrating a simple sign-out functionality.
#### Notes
- Ensure the sign-out process is secure and does not expose sensitive user information.
- Consider edge cases where the sign-out process might fail or be interrupted.

---

## Profile page
### View personal information
As a **user**, I want to view my saved name, username, age, and country on my profile page,_ so that _I can see the details I provided during registration._

#### Acceptance Criteria:
1. The profile page should display the user's name, username, age, and country.
2. The information should be accurately reflected as per the registration details.
3. The profile page should be easily accessible from the menu.

#### Priority
_High_
#### Story Points
_3_
The effort is estimated to be moderate due to the need for integrating user data and ensuring accurate display.
#### Notes
- Ensure the profile information is secure and does not expose sensitive user information.
- Consider edge cases where some information might be missing or incorrect.

### Edit personal information
As a **user**, I want _to update my name, username, age, and country on my profile page,_ so that _I can keep my information up to date._

#### Acceptance Criteria:
1. The profile page should allow users to edit their name, username, age, and country.
2. The edit fields should be pre-populated with the current information.
3. The changes should be saved upon submission.

#### Priority
_High_
#### Story Points
_5_
The effort is estimated to be moderate due to the need for implementing edit functionality and ensuring data validation.
#### Notes
- Ensure the edit process is secure and does not expose sensitive user information.
- Consider edge cases where the user might enter invalid data.


### Save updated information
As a **user**, I want _the changes I make to my profile to be saved,_ so that _my updated details are stored and reflected throughout the app._

#### Acceptance Criteria:
1. The profile page should save the updated information upon submission.
2. The saved information should be reflected throughout the app.
3. The user should receive a confirmation message after saving the changes.

#### Priority
_High_
#### Story Points
_3_
The effort is estimated to be moderate due to the need for ensuring data persistence and synchronization across the app.
#### Notes
- Ensure the save process is secure and does not expose sensitive user information.
- Consider edge cases where the save process might fail or be interrupted.

### Update name in header
As a **user**, I want _my updated name to be displayed in the app's header after I change it in the profile,_ so that _my changes are immediately visible._

#### Acceptance Criteria:
1. The app's header should display the user's updated name immediately after saving changes in the profile.
2. The name should be dynamically updated without requiring a page refresh.
3. The header should be consistent across all pages of the app.

#### Priority
_Medium_
#### Story Points
_2_
The effort is estimated to be low due to the need for implementing dynamic content update in the header.
#### Notes
- Ensure the header update is secure and does not expose sensitive user information.
- Consider edge cases where the header might not update correctly.

---

## Habits page
### Add a new habit
As a **user**, I want _to add new habits on the details configuration page_ so that _I can manage and update my habits as needed._

#### Acceptance Criteria:
1. The habits page should allow users to add new habits.
2. The new habit should be added to the list of existing habits.
3. The user should be able to provide details such as habit name, frequency, and start date.

#### Priority
_High_
#### Story Points
_5_
The effort is estimated to be moderate due to the need for implementing habit addition functionality and ensuring data validation.
#### Notes
- Ensure the habit addition process is user-friendly and intuitive.
- Consider edge cases where the user might enter invalid data.


### Delete a habit
As a **user**, I want _to delete existing habits,_ so that _I can keep my habits up to date._

#### Acceptance Criteria:
1. The habits page should allow users to delete existing habits.
2. The deleted habit should be removed from the list of existing habits.
3. The user should receive a confirmation message after deleting a habit.

#### Priority
_Medium_
#### Story Points
_3_
The effort is estimated to be moderate due to the need for implementing habit deletion functionality and ensuring data consistency.
#### Notes
- Ensure the habit deletion process is secure and does not accidentally remove important data.
- Consider edge cases where the user might try to delete a habit that is already completed or in progress.


### Personalize a habit with color
As a **user**, I want _to assign a specific color to each habit_ so that _I can make it personalized._

#### Acceptance Criteria:
1. The habits page should allow users to assign a color to each habit.
2. The assigned color should be displayed with the habit.
3. The user should be able to change the color of a habit at any time.

#### Priority
_Low_
#### Story Points
_2_
The effort is estimated to be low due to the need to implement a simple color assignment feature.
#### Notes
- Ensure the color assignment process is user-friendly and intuitive.
- Consider edge cases where users might assign the same color to multiple habits.

---

## Reports page
### View weekly reports
As a **user**, I want _to see a report of my weekly habit progress,_ so that _I can understand how well I am maintaining my habits._

#### Acceptance Criteria:
1. The reports page should display a weekly report of habit progress.
2. The report should include data for each day of the week.
3. The report should be visually represented, such as through graphs or charts.

#### Priority
_High_
#### Story Points
_5_
The effort is estimated to be moderate due to the need for data visualization and ensuring accurate reporting.
#### Notes
- Ensure the report is accurate and up-to-date.
- Consider edge cases where there might be no progress data available.

### Visualize completed habits
As a **user**, I want _to see a chart of my completed habits for each day of the week_ so that _I can quickly identify trends in my progress._

#### Acceptance Criteria:
1. The reports page should display a chart of completed habits for each day of the week.
2. The chart should be visually represented, such as through bar graphs or line charts.
3. The chart should be interactive and allow users to view detailed information.

#### Priority
_Medium_
#### Story Points
_5_
The effort is estimated to be moderate due to the need for data visualization and ensuring interactive functionality.
#### Notes
- Ensure the chart is accurate and up-to-date.
- Consider edge cases where there might be no completed habits data available.

### View all habits
As a **user**, I want _to see both completed and incomplete habits in my report,_ so that _I have a comprehensive view of my habit-tracking performance._

#### Acceptance Criteria:
1. The reports page should display both completed and incomplete habits.
2. The report should clearly distinguish between completed and incomplete habits.
3. The report should be visually represented, such as through graphs or charts.

#### Priority
_High_
#### Story Points
_5_
The effort is estimated to be moderate due to the need for data visualization and ensuring comprehensive reporting.
#### Notes
- Ensure the report is accurate and up-to-date.
- Consider edge cases where there might be no habit data available.

---

## Notifications page
### Enable/disable notification
As a **user**, I want _to be able to enable or disable notifications for the app,_ so that _I can choose whether or not to receive reminders for my habits._

#### Acceptance Criteria:
1. The notifications page should allow users to enable or disable notifications.
2. The user should receive a confirmation message after enabling or disabling notifications.
3. The notification settings should be saved and reflected throughout the app.

#### Priority
_High_
#### Story Points
_3_
The effort is estimated to be moderate due to the need for implementing notification settings and ensuring data persistence.
#### Notes
- Ensure the notification settings are secure and do not expose sensitive user information.
- Consider edge cases where the user might encounter issues with enabling or disabling notifications.

### Add habits for notifications
As a **user**, I want _to select specific habits to receive notifications for,_ so that _I only get reminders for the habits I am actively working on._

#### Acceptance Criteria:
1. The notifications page should allow users to select specific habits for notifications.
2. The selected habits should be saved and reflected in the notification settings.
3. The user should receive notifications only for the selected habits.

#### Priority
_Medium_
#### Story Points
_3_
The effort is estimated to be moderate due to the need for implementing habit-specific notification settings.
#### Notes
- Ensure the habit selection process is user-friendly and intuitive.
- Consider edge cases where the user might select no habits or all habits for notifications.


### Set notification times
As a **user**, I want _to have the option to receive notifications three times a day (morning, afternoon, evening) for all selected habits,_ so that _I get timely reminders throughout the day to complete my habits._

#### Acceptance Criteria:
1. The notifications page should allow users to set notification times for morning, afternoon, and evening.
2. The notification times should be saved and reflected in the notification settings.
3. The user should receive notifications at the specified times for all selected habits.

#### Priority
_Medium_
#### Story Points
_3_
The effort is estimated to be moderate due to the need for implementing time-specific notification settings.
#### Notes
- Ensure the notification time settings are user-friendly and intuitive.
- Consider edge cases where the user might set the same time for multiple notifications or no notifications at all.
