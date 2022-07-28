# Deploying a Static Website on AWS

[![CircleCI](https://circleci.com/gh/kenmusima/Deploy-Static-Website-on-AWS.svg?style=svg)](https://circleci.com/gh/kenmusima/Deploy-Static-Website-on-AWS)

## Project Overview

Deploying a website to a S3 Bucket and use CloudFront for the website distribution to enhance cache content thus improving access speed for the content.

### Project Goals

The project does the following:

* Create S3 Bucket.
* Upload content from website folder to S3 Bucket.
* Change S3 bucket to static website hosting.
* Change object policy access within S3 bucket.
* Create CloudFront.

## Setup the Environment

* Create [AWS Account](https://aws.amazon.com/free/).
* Create [CircleCI Account](https://circleci.com/signup/).
* Guide on getting started with [CircleCi](https://circleci.com/docs/getting-started).
* Add Environment Variables in the CircleCi project for AWS_SECRET_KEY, AWS_REGION and AWS_ACCESS_KEY.

### Running the application

* Trigger CircleCI either through Setup of project or change the contents inside the website folder.

### Troubleshooting and Links

In AWS S3 objects content type for html can default to binary/octet-stream. Go to the bucket, select the index.html and click on **Object actions** then select **Edit metadata** and change Content Type to text/html.
For reference [AWS S3 not serving files](https://stackoverflow.com/questions/2618168/amazon-s3-is-not-serving-files-correctly)

### Screenshots

|<img src="screenshots/CloudFront UI.png" width=200/>|<img src="screenshots/S3 Bucket UI.png" width=200/>|
|:----:|:----:|
|<img src="screenshots/CloudFront UI 2.png" width=200/>|<img src="screenshots/S3 Bucket UI 2.png" width=200/>|

|<img src="screenshots/AWS S3 Bucket.png" width=200/>|<img src="screenshots/AWS CloudFront.png" width=200/>|

|<img src="screenshots/AWS CloudFormation.png" width=200/>
