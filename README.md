Setting up CI/CD Pipeline with GitHub Actions and Using Secrets

Objective:
Building on your knowledge of GitHub Actions, the goal is to integrate a CI/CD pipeline into your Node.js project and learn how to utilize GitHub Secrets to secure sensitive data.

Steps:

Create a Simple Node.js Project:
Create a basic Node.js project with an HTML file and a JavaScript file. The project should include a simple function, such as adding two numbers.


Create GitHub Secrets:
In your GitHub repository, set up a GitHub Secret named SECRET_API_KEY. This secret will hold a confidential key or password used for local development, such as an API key.

GitHub Actions Pipeline:
Create a GitHub Actions pipeline by adding a .gitignore/workflows/main.yml file. The pipeline should perform the following steps:

Check out the repository code.
Set up Node.js and npm.
Install project dependencies with npm.
Run a simple test for your application (e.g., using npm test).
Utilize the GitHub Secrets in the pipeline (e.g., set the secret key from SECRET_API_KEY as an environment variable in the pipeline).
This CI/CD pipeline will automate the testing and potentially deployment processes for your Node.js project, enhancing the development workflow and ensuring the security of sensitive information through GitHub Secrets.
