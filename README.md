#Git Assignment - <MK-DSI>
======================
a. What is an issue?

Issue is a feature on Github that allows us to track request changes and features in a software projects. Issue can also be interpreted as a ticket. Issues are used to track todos, bugs, feature requests, and more. 
======================
b. What is a pull request?

It is a feature that allows proposing a code change to the main code, and allows colaborative way to consier and accept those changes into the main code. 
======================
c. Describe the steps to open a pull request?

In order to open a pull request, the following steps may be taken:
1. Clone repository (git clone <LINK>)
2. Create new branch (git checkout -b <branchname>)
3. Make code changes (edit code in the brunch), save the changes
4. Submit Commit Changes (git add (-A if all, or select files) ), then git commit -m "add comment here"
5. Push changes to GitHub (git push, OR git push origin <branchname>, or git push --set-upstream origin <branchname> if this branch was only created on your local computer)
6. Open pull request on GitHub:
    6.1 Go to the Repository on GitHub: After pushing your branch to GitHub, go to the repository’s page in your web browser.
    6.2 Locate the Branch: You should see an option to compare and open a pull request directly if you recently pushed a new branch. Alternatively, you can manually navigate to the Pull Requests tab.
    6.3 Click on "New Pull Request": In the Pull Requests tab, click the green "New Pull Request" button. 
    6.4 Choose Branches to Compare: Make sure the base branch (the branch you want to merge your changes into, usually main or master) is selected on the left side. On the right side, select your feature branch.
    6.5 Write a Title and Description: Give your pull request a meaningful title and write a detailed description of what your changes do, why they are necessary, and any other relevant information.
    6.6 Submit Pull Request: Once you’ve filled in the details, click the “Create Pull Request” button.
======================
d. Describe the steps to add a collaborator to a repository (share write permissions)

To add a collaborator to a GitHub repository and share write permissions, follow these steps:
Step 1: Navigate to Your Repository
    Log in to GitHub: Go to GitHub and log in to your account.
    Open Your Repository: Find the repository where you want to add a collaborator by navigating to your repositories or searching for it.

Step 2: Go to Repository Settings
    Click on the "Settings" Tab: Inside your repository, locate the Settings tab at the top of the page. It’s usually on the far right of the repository’s navigation bar.

Step 3: Manage Access
    Click on "Manage Access": In the left sidebar of the Settings page, scroll down and find the "Manage Access" section. This section controls who has access to the repository.
    Click on "Invite a Collaborator": Within the "Manage Access" section, you’ll see an option to invite collaborators. Click the "Invite a collaborator" button.

Step 4: Add the Collaborator
    Enter the GitHub Username or Email: In the invite field, start typing the username, full name, or email address of the person you want to invite as a collaborator.
    Select the Correct User: From the dropdown, select the correct user you wish to invite.

Step 5: Send the Invitation
    Click "Add Collaborator": After selecting the user, click the "Add collaborator" button.
    Wait for Acceptance: The collaborator will receive an email invitation. They need to accept the invitation to gain access to the repository.

Step 6: Set Permissions (Optional)
    By default, the collaborator will have write permissions. If you want to adjust their permission level (e.g., Admin access or read-only), you can do so from the "Manage Access" section after they accept the invitation.

Step 7: Collaborator Accepts Invitation
    Collaborator Accepts via Email: The person you invited will receive an email notification. They need to click the link in the email and accept the invitation.
    Collaborator Now Has Access: Once they accept, the collaborator will have write access to the repository and can push changes, create branches, and make other contributions depending on their permissions.
======================
e. What is the difference between git and GitHub?

Git is a version control system that allows to track code changes, while Github is a service, web-based platform designed to support git which allows to host git repositories and provide additional features, including issue tracking, pull requests etc
======================
f. What does git diff do?

Git diff shows the differences between various versions of the code in a git repository.  It compares two states of the code and outputs the lines that have been added, modified, or deleted.
======================
g. What is the main branch?

The main branch on git is the default branch in a Git repository where the production-ready code resides. It's the branch that is typically used as the base for all other feature, bug fix, and development branches.
======================
h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

It is not recommended to push changes directly to the main branch.
======================