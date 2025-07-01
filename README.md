# CI-CD-Practice
- This Repository represents how to works Continuous Integrations/Continuous Delivery
## Push Your Code to GitHub
- Commit your Java project and the workflow file (e.g., .github/workflows/main.yml) to your repository.
- Push your changes to the main branch (or open a pull request targeting main).
## GitHub Actions Will Trigger Automatically
- As soon as you push or open a PR, GitHub Actions will start running the workflow as defined.
## View the Output
- Go to your repository on GitHub.
- Click on the “Actions” tab at the top of the page.
- You’ll see a list of workflow runs. Click on the most recent one (should show your commit message).
- Click into the workflow run to see details for each job (e.g., build, test, deploy).
- Click on each step (like “Build with Maven” or “Run Tests”) to expand and view the log output, including build and test results.
