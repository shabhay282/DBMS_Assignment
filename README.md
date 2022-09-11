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
  1. Download SQLite precompiled binaries zip from Teams Chat or you can use this [link](https://www.sqlite.org/2022/sqlite-tools-win32-x86-3390300.zip).
  2. After downloading the zip file extract it to anywhere on your system.
  3. Now go to your **C:** drive on your computer and create a folder with name **sqlite**.
  4. Copy all the extracted files from zip to the folder you just created (c:\sqlite).
  5. Now, open your start menu and type **Environment Variable**.
  6. You will see an option called **Edit Environment Variables**. Open it.
  7. On the window opened, on your right hand side bottom corner you will see an option named as **Environment Variables**. Click it.
  8. On the window that opened you will see two sections one is **User Variables** and second is **System variables**.
  9. In **System Variables** search for a variable named **Path**, click on it and click the **Edit** option.
  10. On the new window that appears, click on **New** option.
  11. On the line where the cursor is blinking add this path **"C:\sqlite"** and save it by pressing **OK**.
  12. Now, again go to your start menu and search for **cmd**. Open Comand Prompt.
  13. Type **sqlite3** and hit Enter.
  14. You will find yourself into sqlite console.
  15. Congratulations !! SQLite is installed on ypur system.


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


