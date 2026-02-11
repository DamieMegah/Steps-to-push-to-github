Step 1: Make sure Git is installed

Check by running:

git --version


If it prints a version number (e.g., git version 2.41.0), Git is installed.

If not, download Git from git-scm.com
 and install it.

Step 2: Initialize Git in your project (if not done yet)
cd C:\webdev\backend\auth-project
git init

Step 3: Add your files to Git
git add .
git commit -m "Initial commit"

Step 4: Add GitHub repo as remote

Use the full URL you copied from GitHub. Do NOT type just the URL by itself. Run this:

git remote add origin https://github.com/DamieMegah/Login-user-authentication.git


Replace with your exact GitHub URL. This tells Git where to push your code.

Step 5: Push to GitHub
git branch -M main
git push -u origin main


You may be asked for GitHub username/password or a personal access token.
