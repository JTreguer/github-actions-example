# Github Actions

*What is GitHub Actions?*
* GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform built right into GitHub.
* It lets you automate tasks like building, testing, and deploying your code directly from your repository.
* You can define custom workflows, or pipelines, that are triggered by specific events, such as pushing code, creating a pull request, or scheduling a run.

A workflow is a sequence of jobs
A job is a collection of steps
Steps are individual tasks

*How it Works:*
1. Trigger: A workflow is triggered by an event, such as pushing code to a branch or merging a pull request.
2. Runner Allocation: A runner is assigned to execute the workflow.
3. Job Execution: The runner executes the steps defined in the workflow's jobs.
4. Step Completion: Each step runs in order, and the workflow progresses based on their success or failure.
5. Workflow Completion: The workflow finishes when all jobs are completed.

*Example Workflow:*

Imagine you have a Python project on GitHub. You could create a workflow that:
* Builds the project when code is pushed to the main branch.
* Runs unit tests.
* Deploys the project to a staging environment if the tests pass.

This workflow would be defined in a .yml file in your repository's .github/workflows directory.
    
## References

### Doc Github Actions
Quickstart:
https://docs.github.com/fr/actions/writing-workflows/quickstart

### Deployment to Azure Web app
Have a look at the example .yml file:

https://docs.github.com/en/actions/use-cases-and-examples/deploying/deploying-python-to-azure-app-service

Video here:
https://www.youtube.com/watch?v=QP0pi7xe24s

![1_zRqs67v54MgZtqHx9kl4EA](https://github.com/user-attachments/assets/9d00b0f4-619c-41aa-8df8-be0dd8b751b4)


## Todo
1) Implement the quickstart example
2) Implement this tutorial steps preferably with your own Flask/Django app:
https://blog.devgenius.io/github-actions-101-with-azure-app-service-24b19c093c25
4) Add some tests in the workflow file
