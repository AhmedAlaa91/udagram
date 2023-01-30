# Pipeline

## Steps 

1- push code to github   
2- commit the code to trigger Circleci
3- Circleci run steps
4- Hold for approval
5- Circleci deploy on AWS

## CircleCI and AWS :

### Build

- Install Node
- Checkout the github repo 
- Install the dependencies for the Backend app
- Build the Backend app
- Install the dependencies for the Frontend app
- Build the Frontend app
- Lint FrontEnd app

### Hold

- Manual approval on CircleCI to deploy

### Deploy 

- Setup AWS CLI
- Setup AWS Access Key ID
- Setup Elastic Beanstalk CLI
- Deploy backend app
- Deploy frontend app

