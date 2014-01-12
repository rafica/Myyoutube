The link.txt file has URL of the hosted site

Features:
Upload button implemented
The page lists all the uploaded videos
Each video has a Rate button
Each video has a delete button
When a video is uploaded or deleted, the page refreshes and the list is updated
*Programmatically created S3 bucket and files are uploaded to S3
Compatible videos are only uploaded and error is thrown for other formats
Error is thrown when no video is uploaded
Video is streamed in browser
Video stored in S3 is distributed using CloudFront
Both type of distributions streaming and downloaded is created
RDS database is used to store details of video like timestamp, name, cumulative rating, number of users who rated the video
Site is hosted in Ec2 server using Elastic Beanstalk
*Mobile based video upload ( for Android )
