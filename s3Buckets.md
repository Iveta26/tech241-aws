# Intro to S3
 
Same as blob storage in Azure

### Using aws CLI

1. ```pip install awscli```
2. ```aws configure``` <- to tell where in AWS we configure, sync up with Spartas are of AWS and determine who we are so it knows what we can interact with
3. Enter Access Key ID
4. Enter Secret Key ID
5. Default output format: JSON

Now it's all set up.
Useful commands:

```aws s3 ls```

```aws s3 mb s3://tech241-iveta-bucket --region eu-west-1``` (mb - make bucket)