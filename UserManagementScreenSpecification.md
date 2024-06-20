**User Management Screen Specification**

**Overview**

This document provides a detailed specification for the User Management
screen. It describes the UI components, their behaviors, and the
interactions within the page. This will be used by software developers
to implement the user interface.

**Initial State**

When the screen is first loaded, User List Table and upper bar
containing "New User" button and checkbox to "Hide Disabled User" (which
will be unchecked) will be visible. On User List Table, previously
created users should be seen.

**1. User List Table**

Should be located on the left hand side of the screen below the top bar,
as if the screen is divided into two equivalent columns. Inside the
table, each user should be assigned a row. Columns are consisting of the
following:

-   **ID:** Displays the unique identifier for each user.

-   **User Name:** Displays the username of each user.

-   **Email:** Displays the email address of each user.

-   **Enabled:** Indicates whether user has access to services or not

Column headers can be clicked to sort that table by that column. Also
each column should be provided a filter icon to allow filtering based on
the column values.

**2. Hide Disabled User Checkbox**

Should be located on top bar next to "New User Button". Can be checked
to hide the users that are designated as "Disabled", having no access to
services.

**3. New User Button**

Should be located on the very left of the top bar. Can be clicked to
open the "New User Form" on the right hand side of the main screen
defined previously.

**4. New User Form**

Will open a form on the right of User List Table to create a new user
and add it to the list, by containing the following fields:

-   **Username:** Text input for the user\'s username.

-   **Display Name:** Text input for the user\'s display name.

-   **Phone:** Text input for the user\'s phone number.

-   **Email:** Text input for the user\'s email address.

-   **User Roles (Dropdown):** User's role selection, options are
    "Guest", "Admin", "SuperAdmin"

-   **Enabled (Checkbox):** Can be checked to provide user service
    access or not

**5. Save User Button**

Should be located on the very left of the top bar. Can be clicked to
save the user to the User List Table whose information is entered inside
the fields of New User Form.

**User Interaction Flow**

**Adding a New User**

1.  Click the "New User" button.

2.  Enter the information of the user inside the fields of "New User
    Form"

3.  Click the "Save User" button.

4.  The new user appears in the "User List Table"

**Editing an Existing User**

1.  Select a user from the "User List Table"

2.  User's details are prompt in "New User Form" area and its fields

3.  Modify the information as needed.

4.  Click "Save User" button.

5.  User with edited information appears in the "User List Table"

**GitHub Repository Link**

This document is available in the following repository:
