# actions-playground
This is a playground to experiment with GitHub Actions 

## Workflows
### Run on Self-Hosted Runner

This workflow includes examples to help you set up and run workflows on a self-hosted runner.

#### Setting Up a Self-Hosted Runner

1. Navigate to your repository's **Settings**.
2. In the left sidebar, click on **Actions**.
3. Select **Runners** from the submenu.
4. Click on the **New self-hosted runner** button.
5. Follow the provided instructions to configure your self-hosted runner.

### Deploy Lambda Function

This workflow builds a function zip bundle and deploys it to an existing Lambda function.

#### Requirements
- AWS account.
- Existing Lambda function to deploy to.

#### Setup Environment Variables and Secrets
1. Navigate to your repository's **Settings**.
2. In the left sidebar, click on **Secrets and variables**.

This workflow requires the following secrets:
- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`

And the following variables:
- `AWS_REGION`
- `AWS_FUNCTION_NAME`