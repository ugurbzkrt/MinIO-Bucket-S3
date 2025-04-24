# MinIO-Bucket-S3


```
mc alias set myminio http://localhost:9000 minioadmin minioadmin123  # Set an alias for MinIO
mc mb myminio/testbucket              # Create a bucket
mc cp file.txt myminio/testbucket/   # Upload a file
mc ls myminio/testbucket             # List bucket contents
mc admin info myminio                # Get system status
```

