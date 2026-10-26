Assignment 5 – GitHub Repository Link

Objective

To create a GitHub repository, understand how to push project files to GitHub, and learn how to host a website using GitHub Pages.

1. Create a GitHub Repository

1. Open "GitHub" (https://github.com/).
2. Click New repository.
3. Enter the repository name: "html-css-assignments".
4. Select Public.
5. Leave the repository empty if you are pushing an existing local project.
6. Click Create repository.

2. Push the Local Project to GitHub

Run the following commands in the terminal from the local project folder:

git remote add origin https://github.com/<your-username>/html-css-assignments.git
git branch -M main
git push -u origin main

Replace "<your-username>" with your actual GitHub username.

These commands connect the local repository to GitHub, set the main branch, and upload the project files and commit history.

3. Verify the Repository

After pushing the project:

1. Open the repository on GitHub.
2. Refresh the page.
3. Confirm that the project files and commit history are visible.

4. Optional – Host the Website with GitHub Pages

1. Open the repository's Settings.
2. Select Pages.
3. Under the build and deployment settings, select the "main" branch and "/ (root)" folder.
4. Click Save.

After deployment, the website URL will follow this format:

"https://<your-username>.github.io/html-css-assignments/"

GitHub Pages works when the repository contains a suitable website entry file, such as "index.html".

5. Submission

Repository link:

"https://github.com/<your-username>/html-css-assignments"

Replace the placeholder with the actual GitHub username and submit the working repository URL.

Conclusion

GitHub allows developers to store and share their projects online. Git push uploads local changes, while GitHub Pages can publish supported static websites for free.