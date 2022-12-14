# Data Engineering Portfolio

This portfolio is a compilation of code which I have created for data engineering works, projects, examples.

## AWS:
* #### AWS Serverless AI Data Engineering Pipeline<br>
    This is an example of a Serverless AI Data Engineering Pipeline.<br>
    AWS Services used: (DynamoDB, Lambda, SQS, CloudWatch, Comprehend, S3)<br>
With CloudWatch Timer we will invoke a AWS Lambda function(Producer) that reads a DynamoDB table and send each item as a message to a SQS queue, when a message feeds the queue a trigger will invoke a AWS Lambda function(Consumer) that will perform a request to Wikipedia API and ask for the first result and the first 2 lines of the content, then we will perform a sentiment analysis using AWS Compehend and store the results in a AWS S3 bucket.<br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/awslambda-toy-model)

## DevOps:
* #### CI Setting Up Workflow Jobs With Github Actions<br>
    This is a Python for DevOps repo, an example of CI using good practices. I have used a EC2 instance on cloud9 AWS environment, git and github actions to check the integrity of the code with a push as a trigger.<br>
Libraries used: (click, pytest, pylint, black, pytest-cov)<br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/aws-cloud9-devops)

## Data Engineering 101: [![](https://badgen.net/badge/101/examples/black)]()

* #### Flask Continuous Deployment with GCP<br>
    Example of deploying a Flask web application with continuous deployment using PaaS and Google App Engine. <br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/cd-on-gcp-flask-web-)

* #### Demo Multi Cloud Continuous Integration Github Actions<br>
    Simple demo of continous integration using Github Actions to perform tests using AWS, Azure or GCP <br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/demo-multi-cloud-continuous-integration-github-actions-)

* #### Testing Techniques<br>
    This is a repo for doing a simple example of testing python code<br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/testing-techniques)



