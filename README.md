# hello-CircleCI

## Learning CircleCI and diving into CI/CD

---

#### Production

Steps:

- Create a public S3 Bucket
- Create a SPA
- Create a Cloudformation template (cloudfront.yml) to create a Cloudfront Distribution
- Execute the template manually
- Create a Cloudformation template that create a new S3 Bucket and copies production files
- Create a job that executes this template
- Promote to Production by executing the cloudfront.yml template using a job
- Create a job that destroys previous S3 Bucket and Cloudformation Stack
- 