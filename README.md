[![CircleCI](https://circleci.com/gh/kenmusima/Deploy-Static-Website-on-AWS.svg?style=svg)](https://circleci.com/gh/kenmusima/Deploy-Static-Website-on-AWS)

## Project Overview
Deploying a Static Website on AWS

Deploying a website to a S3 Bucket and use CloudFront for the website distribution to enhance cache content thus improving access speed for the content.

### Project Goals

The project does the following:

* Create S3 Bucket.
* Upload content from website folder to S3 Bucket.
* Change S3 bucket to static website hosting.
* Change object policy access within S3 bucket.
* Create CloudFront.

## Setup the Environment

* Create [AWS Account](https://aws.amazon.com/free/)
* Create [CircleCI Account](https://circleci.com/signup/)
* Guide on getting started with [CircleCi](https://circleci.com/docs/getting-started)

### Running the application

* Trigger CircleCI either through Setup of project or change the contents inside the website folder.
