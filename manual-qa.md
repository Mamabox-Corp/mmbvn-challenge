# mmbvn-challenge
## Requirements 1
There is a set of requirements, please write clear and comprehensive Test Cases that would cover all these requirements. Provide as many details as if test cases would be written in an actual test management tool.
      
**##Functional Requirements:**

- Users should be able to login if provided valid credentials. Users should not be able to login if credentials are invalid.

- Users should be able to login using SSO with Google accounts. In case the user doesn’t exist in the system yet, the Member role should be assigned automatically. If the user with the same email exists in the system, no other role should be assigned automatically if SSO login is used. Note: During SSO login feature using, the user should provide valid email & pass for the chosen account. We have only Google SSO implemented - so it means, credentials from Google acc should be valid. However, this validation is implemented on Google side - not directly in our application.

- Users that have more than 100$ on account balance should see an ad on the homepage.

- Only users with role “Handler” should have access to the “Coverage” feature.

- Only users with role “Member” should have access to the “Shop” feature.

- Main body of the page is a list of search results. Search results could be filtered and sorted by name. Default sorting is by date created.
      
**UI Details:**
      
- Login page is a usual one e.g. it has fields login, password and button login. In addition, there is a “Login with SSO” button.
      
- Home page has a sidebar that provides access to different features such as “Coverage” like on the attached image.
      
- Search results have one text field where the user can input values to filter by. Sorting is done by pressing on the column header.

## Requirements 2
During testing, some issues were found. Please create bug reports for these issues providing as much information as you would provide to an actual bug report.
Mind the system allows the user to work with each feature via API as well so bugs may appear both in UI and API - you need to decide how you will describe the problem clearly enough to understand where it should be fixed.

For issues 2-4, it is necessary to provide exhaustive information about the root cause of the faced problem. Provide as many details as possible that help with issue understanding.

**##Functional Requirements:**

- Note: You can provide mocks of screenshots of faced issues or describe in writing what should be seen in screenshots (for UI faced issues).

- You can provide mock samples of API requests and other information for not UI issues.

- Try to think of any other information and/or additional steps that can help.

**Issues:**

- After accessing a feature\page, a 404 error is returned.

- Users with a role Member can access the feature “Coverage.”

- Users with a role Handler can not access feature “Coverage” from the sidebar, but can
access the feature through the interface on the home page body.

- User sees a wrong calculated amount to pay for elements added to the cart.

- Side bar has invalid color when opening the app as a user with the role “Handler”.











