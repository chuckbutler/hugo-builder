# Hugo Builder

Docker container to run automated builds of a Hugo based website.

Requires the following variables to be passed in:

- AWS_ACCESS_KEY_ID
- AWS_SECRET_KEY
- BUCKET
- THEME

Setting the following allow the container to build the static content, and subsequently publish as a sync to a given S3 bucket.

