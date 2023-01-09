# portfolio-project
This project is developed with java spring boot framework, in which user can sign up/sign in and can create there profile. The infrastructure of this project is created in AWS Elastic Beanstalk  with load balancing and auto-scaling and ci/cd implemented with AWS Code Pipeline.

# Work-Flow

User push the code (Code Commit)---->Code Build(Maven)---->Build Artifact(s3)---->Code Deploy---->AWS Elastic Benastalk
