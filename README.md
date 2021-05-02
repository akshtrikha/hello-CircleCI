# hello-CircleCI

## Learning CircleCI and diving into CI/CD

---

#### Getting first Green Build  🤙

Using [this](https://circleci.com/docs/2.0/getting-started/) tutorial.\
Branch: circleci-project-setup

#### Using Environment Variables  🤙

Using [this](https://circleci.com/docs/2.0/env-vars/#setting-an-environment-variable-in-a-project) tutorial.\
Branch: circleci-project-env-vars

#### Sharing Files  🤙

Using [this](https://circleci.com/docs/2.0/configuration-reference/#persisttoworkspace) tutorial.\
Branch: circleci-project-sharing-files

#### Reusable Commands  🤙

Using [this](https://circleci.com/docs/2.0/configuration-reference/#commands-requires-version-21) tutorial.\
Branch: circleci-project-reusable-commands

#### Job Failures 🤙

Using [this](https://circleci.com/docs/2.0/configuration-reference/#example) tutorial.\
Branch: circleci-project-job-failures

#### Infrastructure Creation  🤙

Steps:

- Creating Environment Variables:
  - AWS_ACCESS_KEY_ID
  -  AWS_SECRET_ACCESS_KEY
  - AWS_DEFAULT_REGION
- Cloudformation [Script](scripts/template.yml)

Branch: circleci-project-infrastructure-creation

#### Checkout Experiment  🤙

Using [this](https://circleci.com/docs/2.0/configuration-reference/#checkout) tutorial.\
Branch: circleci-project-checkout-experiment


#### Configuration and Deployment 🤙

Steps:

- Create an EC2 instance with a key-pair
- Add the key-pair to CircleCI environment variables
- Create a job to install Ansible on the docker container and add_ssh_keys
- Create an Ansible Playbook to run a simple task on the instance
- Access the EC2 Instance using Ansible Playground

Branch: circleci-project-configuration-deployment
