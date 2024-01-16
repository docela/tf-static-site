![The Static Site Deployment](tf-static-site.svg "The Static Site Deployment")

## A Static Website Hosted on S3
This is a static website hosted on S3, deployed through terraform.

The terraform state file is sent to another private S3 bucket that was created beforehand with the Bucket Owner Enforced, disabling the ACL.