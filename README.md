# Udagram Full-Stack App Deployed And Hosted On AWS - Udacity

### App link:

	- The Application ( S3) link: 			http://muhamedtalaatbucket.s3-website-us-east-1.amazonaws.com/
	- The server (Elastic Beanstalk) Link: 	http://udagram-api-dev.eba-cpjq3mkv.us-east-1.elasticbeanstalk.com

### Pipeline Status(CircleCi):

	- Circle CI Project link: https://app.circleci.com/pipelines/github/Mohammad-talaat/Hosting_udagram

### GitHub Link:

	- GitHub link: https://github.com/Mohammad-talaat/Udacity-s-FullStack-App-Udagram.git
	
### App Main Parts:

- Front-End runs on  AWS S3 Bucket
- Back-End runs on Elastic Beanstalk 
- RDS micro tier is used for the database `Postgres`.

`CircleCi` for CI & CD is used, as when a new code is pushed the `pipeline` starts to apply the new code and till
the changes will be deployed on the production environment.

### Installation:

Run `npm install` for both frontend part and api part to download the necessary dependencies.

### Run the application locally:

Create a `.env` file in `udagram-api` With the below variables:

POSTGRES_USERNAME
POSTGRES_PASSWORD
POSTGRES_DB
PORT
POSTGRES_HOST
RDS_DIALECT
AWS_REGION
AWS_PROFILE
aws_bucket
AWS_BUCKET
URL
DB_PORT
JWT_SECRET


Open `http://localhost:PORT` in the local browser.


2- Please check the `Doc folder` for more information & clarifying diagrams.
