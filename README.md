# imageresizeserver


# Env
```
# S3 service envpoint (without http://, https://)
S3_ENDPOINT=localhost:9000
S3_ACCESS_KEY_ID=minio
S3_SECRET_ACCESS_KEY=minio123
S3_BUCKET=media
S3_REGION_NAME=ru-central1

GIN_MODE=debug

# allowed buckets
S3_BUCKETS="media,media2"

CORS_ALLOW_ORIGINS="http://localhost:9000"
```