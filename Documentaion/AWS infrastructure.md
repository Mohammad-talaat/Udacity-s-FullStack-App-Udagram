## Udagram Infrastructure


### AWS
#### RDS Postgres

	The application server uses AWS RDS Postgres as database for storing and retrieving information.
		- Database Link: database-1.ctdc2n7rve8e.us-east-1.rds.amazonaws.com


#### Elastic Beanstalk

	The application server is deployed on AWS Elastic Beanstalk service. The application is build, archived and uploaded
	to and S3 bucket from where Elastic Beanstalk extracts and runs the application on an endpoint.
		- EB link: http://udagram-api-dev.eba-cpjq3mkv.us-east-1.elasticbeanstalk.com
	
#### S3 Bucket

	The frontend application is deployed using AWS S3 Bucket. The bundled assets are uploaded to an S3 bucket and that
	bucket is made publicly accessable.	
	End users can access the application from the Bucket URL
		- S3 Bucket link: http://muhamedtalaatbucket.s3-website-us-east-1.amazonaws.com/

