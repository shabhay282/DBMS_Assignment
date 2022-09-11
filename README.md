# DBMS_Assignment
## GIT Installation Windows
  1. Browse to the official Git website: https://git-scm.com/downloads
  2. Click the download link for Windows and allow the download to complete.
  3. Browse to the download location (or use the download shortcut in your browser).
  4. Double-click the file to extract and launch the installer.
  5. Allow the app to make changes to your device by clicking Yes on the User Account Control dialog that opens.
  6. On next screen click **Next**.
  7. Now, without changing anything, keep clicking on **Next** until you get a **Finish** option.
  8. Launch Git Bash - Open the Windows Start menu, type git bash and press Enter (or click the application icon).
  9. Configure your local Git installation to use your GitHub credentials by entering the following:
      - git config --global user.name "github_username"
      - git config --global user.email "email_address"
      - **Note:** *Replace **github_username** and **email_address** with your GitHub credentials.*
  10. Congratulations !! Git is setup on your system.
  
## SQLite3 Installation































mkdir git_test

An example of the PowerShell output.

Example of creating a test directory in Windows PowerShell.
Change your location to the newly created directory:

cd git_test

Note: If you already have a GitHub repository, use the name of that project instead of git_test.

Configure GitHub Credentials
Configure your local Git installation to use your GitHub credentials by entering the following:

git config --global user.name "github_username"

git config --global user.email "email_address"

Note: Replace github_username and email_address with your GitHub credentials.

Clone a GitHub Repository
Go to your repository on GitHub. In the top right above the list of files, open the Clone or download drop-down menu. Copy the URL for cloning over HTTPS.

Cloning a GitHub repository over HTTPS
Switch to your PowerShell window, and enter the following:

git clone repository_url


