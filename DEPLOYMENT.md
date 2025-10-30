Deployment Guide

This project is a single-page portfolio built in a single index.html file. The simplest and most effective way to deploy it for free is by using GitHub Pages.

Prerequisites

A GitHub account.

Git installed on your local machine.

The final index.html file for this portfolio.

Your GitHub repository (e.g., personalportfolio_sagar) created on GitHub.com.

Step-by-Step Deployment

Step 1: Set Up Your Local Repository

If you haven't already, connect your local project folder to your GitHub repository.

# Clone the repository if you haven't
git clone [https://github.com/sangeethsagar/personalportfolio_sagar.git](https://github.com/sangeethsagar/personalportfolio_sagar.git)

# Navigate into the project directory
cd personalportfolio_sagar


Step 2: Add Your Portfolio File

Place your finalized index.html file directly into the root of this personalportfolio_sagar folder.

Your folder structure should look like this:

personalportfolio_sagar/
├── index.html
├── LICENSE
├── README.md
└── (other files like package.json...)


Step 3: Add, Commit, and Push to GitHub

Run the following commands from your terminal within the project folder to upload your file to GitHub.

# 1. Stage the new index.html file
git add index.html

# 2. Commit the file with a clear message
git commit -m "feat: Add final index.html for deployment"

# 3. Push the commit to your 'main' branch on GitHub
git push origin main


(Note: If your main branch is called master, use git push origin master instead.)

Step 4: Configure GitHub Pages

Go to your repository on GitHub.com:
https://github.com/sangeethsagar/personalportfolio_sagar

Click on the Settings tab.

In the left-hand sidebar, click on Pages.

Under the "Build and deployment" section:

Source: Select Deploy from a branch.

Branch: Select main (or master) and keep the folder as / (root).

Click Save.

Step 5: Go Live!

That's it! GitHub will now build and deploy your site. Wait about 1-2 minutes, then refresh the GitHub Pages settings page.

A green box will appear at the top with your live URL, which will look like this:

https://sangeethsagar.github.io/personalportfolio_sagar/
