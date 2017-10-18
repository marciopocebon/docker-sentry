# A Custom Docker Image Sentry to use on AWS BeanStalk.

## Features

This image recipes has goal to use on AWS BeanStalk but it's possible to use any container service. it's override entrypoint.sh of original Sentry Dockerfile do run web, cron or worker based variable environment. Tested in the BeanStalk, Docker Engine and Docker Compose. Also, it's support New Relic probe support and store objects into S3.


### Variables
WORKER
WEB
CRON
NEW_RELIC_APP_NAME
NEW_RELIC_LICENSE_KEY
AWS_ACCESS_KEY
AWS_SECRET_KEY
AWS_S3_BUCKET_NAME
