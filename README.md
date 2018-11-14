# cajon_desastre
Stuff that I had to look for in DuckDuckGo more than 1 time

## SH one liners
```sh
# Telling SSH to not verify or store the server signature
ssh -vv -o UserKnownHostsFile=/dev/null -o StrictHostKeyChecking=no manolo@127.0.0.1 -p 2222
```

# Amazon AWS
## S3
```
aws.cmd s3api get-bucket-accelerate-configuration
aws.cmd s3api get-bucket-acl
aws.cmd s3api get-bucket-analytics-configuration
aws.cmd s3api get-bucket-cors
aws.cmd s3api get-bucket-encryption
aws.cmd s3api get-bucket-inventory-configuration
aws.cmd s3api get-bucket-lifecycle-configuration
aws.cmd s3api get-bucket-location
aws.cmd s3api get-bucket-logging
aws.cmd s3api get-bucket-metrics-configuration
aws.cmd s3api get-bucket-notification-configuration
aws.cmd s3api get-bucket-policy
aws.cmd s3api get-bucket-replication
aws.cmd s3api get-bucket-request-payment
aws.cmd s3api get-bucket-tagging
aws.cmd s3api get-bucket-versioning
aws.cmd s3api get-bucket-website
```
