**Deploy using Github Pages**

[see here](https://create-react-app.dev/docs/deployment/)


**Publish the React application on GitHub Pages**

To publish the user site, follow the below steps.

1)Create an Account in GitHub.

2)Create Repo in GitHub where the repo name should be username.github.io

3)Create React Application.

4)Deploy the React Application using GitHub Pages.

5)Commit and Push the codebase (React Application) into GitHub repo


**Step 1 - Create an Account in GitHub**

- Open the GitHub link
- Create an account using your personal email
- To secure your GitHub account, you can enable MFA (multi-factor authentication) login for your account.

**Step 2 - Create Repo in GitHub**

- Login to your GitHub account.
- Create the new repo by clicking the "+" icon at the right top of the page.

<p align="center">

<img src="https://csharpcorner-mindcrackerinc.netdna-ssl.com/article/how-to-deploy-react-application-on-github-pages/Images/1.png" width="350px">
</p>
 <p align="center">
  
  - Enter the repo name as yourusername.github.io and choose whether the repo should be public or private.
  
  <p align="center">

<img src="https://csharpcorner-mindcrackerinc.netdna-ssl.com/article/how-to-deploy-react-application-on-github-pages/Images/2.png" width="450px">
</p>
 <p align="center">
 
 - Click on the "Create repository" button.Now your repo has been created.
 
 **Step 3 - Create React Application**
 - Create the react application which you want to host as a website. In this article, I am mainly focusing on how to deploy the react application on GitHub Pages. 
 
 **Step 4 - Deploy the React Application**
 - To deploy the application, follow the below steps.
 1) Add GitHub Pages dependency package
 
 Install "gh-pages" package using the below command.
 
 ```
 npm install gh-pages --save-dev
 
 ```
