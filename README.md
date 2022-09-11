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
  15. Congratulations !! SQLite is installed on your system.

## Setting Up Repository on your local
  1. Go to your start menu and search for **Git Bash** and press Enter (or click the application icon).
  2. Type **mkdir dbms_assignment** and hit Enter.
  3. Type **cd dbms_assignment** and hit Enter.
  4. Type **git clone https://github.com/moiz-bits/DBMS_Assignment.git** and hit Enter.
  5. Congratulations !! you have successfully setup the git repo on your local.

