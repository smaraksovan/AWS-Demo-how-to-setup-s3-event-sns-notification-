# AWS-Demo-how-to-setup-s3-event-sns-notification-

Pre-Requisites for Configuring S3 Notifications
To enable notifications, you must,

First, Add a notification configuration(SNS) identifying the events you want Amazon S3 to publish,
Update topic policy to allow S3 to publish messages(Refer below for policy json code)
Subscribe to SNS with email notification
Second, Update the destinations where you want Amazon S3 to send the event notifications
Granting Permissions for S3 to Publish Messages to an SNS Topic
IAM policy that needs to be attached to the destination SNS topic,

Note: Dont forget to update to the ARN and Bucketname in the below policy

