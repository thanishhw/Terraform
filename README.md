# Terraform
terrform doc

"Infrastructure Automation: Deploying AWS Environments with Terraform & GitLab Pipelines" Here's what accomplished.

Project Overview:
Built modular Terraform configurations to provision: A VPC Public subnet
Security group EC2 instance (t2.micro, Amazon Linux 2)
Configured GitLab CI/CD with secure stages: validate apply destroy
←
plan
←
→
Managed remote backend using S3 (state file) and DynamoDB (locking)

Why this matters:

Reduced infrastructure setup time by 80%
Enabled version-controlled, repeatable
deployments
Eliminated risks of state conflicts using remote locking

Top Learnings:

Modular Terraform makes scaling and reusing infrastructure code seamless
CI/CD approval flows balance automation with human oversight.

State management is critical when working across environments or teams

✔Final Thoughts:

This project isn't just about spinning up cloud resources-it's about making cloud infrastructure reliable, automated, and auditable. I'll be applying this as a base template for future DevOps and cloud projects.
