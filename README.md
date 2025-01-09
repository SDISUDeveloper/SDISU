# Welcome Email Templates Repository

Welcome to the **Email Templates Repository**! This is where we create and update HTML email templates for our "Welcome" folder. Don’t worry if you’re new to this—just follow these simple steps.

## Key Points
1. Templates are stored in the `Welcome` folder.
2. Templates use special placeholders (listed below) to personalize the emails.
3. Use "branches" to make changes.
4. All changes must be reviewed before going live.

### Placeholders You Can Use
Here are the placeholders available in the email templates:
- `{FIRST_NAME}`: The user’s first name.
- `{LAST_NAME}`: The user’s last name.
- `{MEMBER_NUMBER}`: The user’s membership number.
- `{EMAIL}`: The user’s email address.
- `{DISCORD_INVITE_LINK}`: A unique Discord invite link.

---

## How to Update Email Templates

### Step 1: Get Started
1. **Install Git** if you don’t already have it. You can [download it here](https://git-scm.com/downloads).
2. **Clone the Repository**:
   - Open your terminal or Git application.
   - Run this command:
     ```
     git clone [repository-link]
     ```
   - Replace `[repository-link]` with the link to this repository.

### Step 2: Create a Branch
1. Switch to the `dev` branch:
   ```
   git checkout dev
   ```
2. Create a new branch for your changes. Use a name like `update-template`:
   ```
   git checkout -b update-template
   ```

### Step 3: Make Your Changes
1. Open the `Welcome` folder and find the template you want to update.
2. Use a text editor (like Notepad or VS Code) to edit the file.
3. Add or update placeholders as needed. For example:
   ```html
   <p>Hello {FIRST_NAME} {LAST_NAME},</p>
   <p>Your member number is {MEMBER_NUMBER}. Join us on Discord: {DISCORD_INVITE_LINK}</p>
   ```
4. Save your changes.

### Step 4: Save and Share Your Work
1. Add your changes:
   ```
   git add .
   ```
2. Commit your changes with a message:
   ```
   git commit -m "Updated welcome email template"
   ```
3. Push your branch:
   ```
   git push origin update-template
   ```

### Step 5: Request a Review
1. Go to the repository on GitHub.
2. Click "Create Pull Request" for your branch.
3. Add a short description of what you changed.
4. Assign me as the reviewer.

---

## Notes
1. Always work in a **new branch** created from `dev`.
2. Never edit the `main` branch directly.
3. If you need help, just ask!

Thank you for helping keep our email templates awesome! 🎉

