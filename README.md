# Serverless Todo App With AWS, Pulumi and Python

## Setup

We will be using AWS lambda functions. To manage our app deployment seemlessly

- Pulumi: For Infrastructure as code (using Python)
- AWS API Gateway: To manage our APIs endpoints, rate limiting, auto scalling and request routing.
- Docker: For packaging code

## CRUD

Our app contains complete CRUD features.

## Setup Pulumi Project.

We will be using Python as a configuration language, so let's initiate pulumi with a python template.

This should be created inside your app root directory


```bash
pulumi new aws-python
```
