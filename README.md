AgriTech Market Connect — Brenda Maina

This is a project website for AgriTech Market Connect. It shows the progress, achievements, challenges, and metrics of the project. The website is built using one HTML file and runs directly in the browser with no installations needed.

What This Project Is

AgriTech Market Connect is a platform that connects smallholder farmers to local grocery buyers. This website documents the pilot phase of the project, including training workshops, market partnerships, and platform adoption data.

What You Need Before You Start

- A computer (Windows, Mac, or Linux)
- A GitHub account — sign up free at github.com
- An internet connection
- Nothing else — no software to install

How to Set It Up Step by Step

Step 1 — Create a GitHub Account

1. Go to github.com
2. Click Sign Up
3. Enter your email address
4. Create a password
5. Choose a username
6. Verify your email address

If you already have an account, just log in.

Step 2 — Create a New Repository

A repository is like a folder on GitHub where your project lives.

1. Once logged in, click the + button at the top right of the page
2. Click New repository
3. In the Repository name box, type: agritech-market-connect
4. Make sure Public is selected
5. Tick the box that says Add a README file
6. Click the green Create repository button

Step 3 — Open GitHub Codespace

Codespace is an online code editor provided by GitHub. You do not need to download anything.

1. On your repository page, click the green Code button
2. Click the Codespaces tab
3. Click Create codespace on main
4. Wait about 30 seconds for it to load
5. A code editor will open in your browser

Step 4 — Create the Website File

1. In the left sidebar of Codespace, look for the Explorer panel
2. Right click on the empty space in the file list
3. Click New File
4. Name the file exactly: index.html
5. Press Enter
6. The file will open on the right side of the screen

Step 5 — Add the Website Code

1. Go to the repository on GitHub
2. Open the index.html file
3. Copy all the code inside it
4. Go back to Codespace
5. Click inside the empty index.html file you just created
6. Paste the code in using Ctrl+V on Windows or Cmd+V on Mac
7. Press Ctrl+S on Windows or Cmd+S on Mac to save

Step 6 — Push the Code to GitHub

Now you need to send the file from Codespace to GitHub. You do this using the terminal.

1. In Codespace, click Terminal in the top menu
2. Click New Terminal
3. A black panel will open at the bottom of the screen
4. Type the following commands one at a time and press Enter after each one:

git add index.html

git commit -m "add website"

git push

5. Wait a few seconds after each command
6. If it asks for a username, type your GitHub username and press Enter
7. If it asks for a password, you need to use a Personal Access Token, not your normal password. See the section below on how to get one.

Step 7 — Turn on GitHub Pages

GitHub Pages turns your repository into a real live website.

1. Go to github.com and open your repository
2. Click Settings in the top menu bar of your repository
3. Scroll down the left sidebar and click Pages
4. Under the Branch section, click the dropdown that says None
5. Select main
6. Click Save
7. Wait about 2 minutes
8. Refresh the page
9. A link will appear at the top that looks like this: https://yourusername.github.io/agritech-market-connect
10. Click that link — that is your live website

Step 8 — Share Your Website

Copy the link from Step 7 and share it with anyone. It works on any device and any browser.

How to Get a Personal Access Token (if git push asks for a password)

GitHub no longer accepts your normal password in the terminal. You need to create a token instead.

1. Go to github.com and log in
2. Click your profile picture at the top right
3. Click Settings
4. Scroll all the way down the left sidebar and click Developer settings
5. Click Personal access tokens
6. Click Tokens (classic)
7. Click Generate new token
8. Click Generate new token (classic)
9. In the Note box, type: my token
10. Set the Expiration to 90 days
11. Tick the box next to repo
12. Scroll down and click Generate token
13. Copy the token that appears — it starts with ghp_
14. Save it somewhere safe because GitHub will only show it once
15. When the terminal asks for your password, paste this token instead

 How to Make Changes to the Website Later

If you want to update anything on the website:

1. Open your Codespace
2. Click on index.html
3. Make your changes
4. Save the file with Ctrl+S or Cmd+S
5. Open the terminal and run:

git add index.html
git commit -m "update website"
git push


6. Wait about 1 minute and your live website will update automatically

 Project Lead

Brenda Maina
