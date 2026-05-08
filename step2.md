```bash
aws configure set aws_access_key_id minioadmin
aws configure set aws_secret_access_key minioadmin
aws configure set regio
aws --endpoint-url http://localhost:9000 s3 mb s3://techlogistics-assets
```bash
aws --endpoint-url http://localhost:9000 s3 ls
