# <center>Full Stack Todo App - Requirements</center>

---

## Functional Requirements

#### Signup

- User should be able to sign up using their name, email, and password.
- After signing up, the user should be automatically logged in and redirected to the home page.

#### Login

- User should be able to login using their email and password.
- After logging in, the user should be redirected to the home page.

#### Home

- User can view all lists on their home screen, with all todos visible on each list.
- User can navigate to account screen.

#### List

- Each list has a name `(max 50 characters)` and color.
- User can add, view, edit, or delete lists.

#### Todo

- Each todo has a name `(max 100 characters)`, checkbox indicating if it is completed, deadline, and reminder.
- User can add, view, edit, or delete todos in each list.

---

## Non-Functional Requirements

#### Security

- User should be required to login to store their data on the cloud.
- User cannot use the app without being logged in.
- User can only access their own data, and only if they are logged in.
- User data should be appropriately secure.
- App API keys must not be publicly availably, unless it is meant to be.

#### Scalability/Elasticity

- App should be able to scale with a rapidly increasing number of users, with minimal effort from the development team.

#### Code Quality

- App code should be appropriately abstracted where required.
- App code should follow SOLID and DRY guidelines.
- Any non-obvious code must be appropriately documented.
- Consistent code styles and formatting is required.

#### Testing

- Backend APIs must have at least 25% line coverage.
- Frontend must have unit tests and selenium tests. Required coverage is uncertain, for now.
- Testing should occur automatically on all git commits.

#### Development

- Locally serving and testing the app must be easy and fast.
- Appropriate version control.
  - Git branches must be used to implement new/breaking features.
  - Commits must be frequent and, wherever possible, small.

#### Deployment

- Deploying the app must be easy and fast.
- Deployment should happen automatically on commits to main, but this should require developer authentication and confirmation.
- App should not be deployed if it fails any tests.

#### Cost

- App should be initially free to deploy and use.

#### Usability

- App should be responsive
- App should use a simple, intuitive UI
- App should be performant
- App should be efficient with the number of intense operations, like sorting large lists, or API calls.

---

<!-- ## Screens

#### Home Screen

- Must have:
  - One account button, to take the user to their account page.
    - One title, indicating it is the home screen.
    - One icon, indicating it is the home screen.
    - One “+” button, to add a list.
- Can have:
  - None, one, or multiple lists.
- Users can:
  - Add lists
    - User clicks the “+” button.
    - App shows “Add List” screen as popup.
    - User fills name.
    - User selects color.
    - User clicks “add” to add list.
    - User clicks “cancel” to cancel addition of list.
    - App rejects the addition and shows error if name or color is empty.
  - View lists
    - App shows all lists on the home screen, horizontally.
    - App shows name of all todos on each list.
    - App shows name and color of each list.
  - Edit lists
    - User clicks the "✎" button.
    - App shows "Edit List” screen as popup.
    - User edits name.
    - User selects new color.
    - User clicks “save” to save.
    - User clicks "Cancel” to add.
  - Delete lists
    - App asks for confirmation in popup.
  - Expand list
    - User clicks on list to expand it.
    - App shows list screen as a popup.

#### List Screen

- Must have:
  - One title, which is the name of the list.
  - One background color, which is the color of the list.
- Can have:
  - None, one, or multiple todos.
- Users can:
  - Edit list
    - User clicks the "✎" button.
    - App shows "Edit List” screen as popup.
    - User edits name.
    - User selects new color.
    - User clicks “save” to save.
    - User clicks "Cancel” to add.
    - App rejects the addition and shows error if name or color is empty.
  - Add todo
    - User clicks "+" buton.
    - User clicks the “+” button.
    - App shows “Add List” screen as popup.
    - User fills name.
    - User selects color.
    - User clicks “add” to add list.
    - User clicks “cancel” to cancel addition of list.
    - App rejects the addition and shows error if name or color is empty.
  - View todos
    - Click on a list to show an expanded view.
  - Edit todos
    - Edit either the name or the color of the list.
  - Delete todos
    - App asks for confirmation.

#### Todo

- Must have:
  - One name.
  - Checkbox, indicating whether it is completed
  - Deadline
  - Reminder

--- -->
