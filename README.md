# GitHubActions_UsefulSteps

# awsCLI.yaml
- Installs AWS CLI in GitHub Actions container as per [AWS Instructions](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- Runs `aws s3 ls` which lists all the s3 buckets
- Make sure your AWS user you are using has IAM permissions to do so.
- Add secrets 
  - In your repository > Settings > Secrets > Actions
    - Add AWS_ACCESS_KEY_ID 
    - Add AWS_SECRET_ACCESS_KEY
    - Add AWS_REGION 
