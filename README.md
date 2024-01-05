# custom-boto3-cli
Subset of aws-cli commands with customization options like extra headers

## Context

This tool is used to make boto3 calls with a custom header, might be useful to debug S3 compatible object storage implementations by appending custom http headers on the regular requests made by this python s3 library. Headers are added to the 'request-created' event of the [Boto3’s event system](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/events.html)https://boto3.amazonaws.com/v1/documentation/api/latest/guide/events.html

### Usage

TBD

### License

[MIT](https://github.com/marmotitude/custom-boto3-cli/blob/main/LICENSE)https://github.com/marmotitude/custom-boto3-cli/blob/main/LICENSE
