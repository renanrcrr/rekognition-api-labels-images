# AWS Rekognition API to Detect Labels from Lambda Through Images via S3 

This code gets the S3 attributes from the trigger event, then invokes the rekognition api to detect labels. If the label matches the one present on the LABELS list, response is written in the S3 bucket with "Status":"Label Found", else the response is written in the S3 bucket with "Status":"Label Not Found".