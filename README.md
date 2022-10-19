# AWS Custom Resource example

This project demonstrates a simple lambda backed custom resource creation in AWS.

### Steps

- Install crhelper dependency - `pip install -t . crhelper`
- Create lambda execution role if not already present
- Package and deploy the lambda in preferred region
- Deploy the cloudformation template in the same region
