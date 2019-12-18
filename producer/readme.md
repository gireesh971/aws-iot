# IOT POC - Spring boot based producer

This is a command line client which generates a sample json content and pushes it to Kinesis Stream

Scripts:

Cleanup:

aws s3 rm s3://gireeesh-firehose --recursive
aws firehose delete-delivery-stream --delivery-stream-name fire-hose
