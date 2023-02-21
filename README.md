# cloudformation-exercises

This is for the assignment for EarthDaily. The following are the steps to recreate the Infrastructure.
1) Go to AWS Console and login
2) Go to AWS IAM and start creating roles and policies.
3) Create the first role name it cloudformation_s3_role.json. its contents should be as follows - https://github.com/djprawns/cloudformation-exercises/blob/earth-daily/cloudformation_s3_role.json
4) Create the second role name it codepipeline_demo_service_role.json. its contents should be as follows - https://github.com/djprawns/cloudformation-exercises/blob/earth-daily/codepipeline_demo_service_role.json
5) Start configuring the CI / CD for the infrastructure which shall be sourced from the Cloudformation YAML file at https://github.com/djprawns/cloudformation-exercises/blob/earth-daily/test.yml.
  5.1) Go to codepipeline and configure all the build steps. This can be expanded on in the F2F demonstration.
  5.2) Once configured, go to CodePipeline and click on release the change.
  5.3) make sure you change the email with the target mail id of your choice
6) at this point, a mail shall be recieved in your mailbox. Confirm the subscription (be sure to see the spam / promotions sections, they arrive there sometimes).
7) Go to the S3 bucket and drop a mail, you shall recieve a mail with the payload.
8) Further explore the cloudwatch events where events shall be recieved as a trail.
