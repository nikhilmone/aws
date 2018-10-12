## Compute

1) EC2 : Elastic Cloud Compute
2) EC2 Container Services : Container Services
3) Elastic Beanstalk: Developers only need to upload the code, AWS manages the Infra for them
4) Lambda : Serverless architecture, no need of infra or compute
5) Lightsail: AWS for noobs, will create EC2 instance, IP address to communicate with server, VPN, ssh etc. It also comes with the Management console.
6) Batch: Used for batch computing in AWS

## Storage

1) S3 Simple Storage Service: Oldest storage service
2) EFS Elastic File System : It is a network file system that can be attached with multiple EC2 instances.
3) Glacier : Used for data archival
4) Snowball: To bring large amount of data in TBs in AWS
5) Storage Gateway: VMs that you install in your DC and it communicates with S3.

## Databases

1) RDS: Relational Database Services
2) Dynamo DB
3) Elasticache : Used as a caching service
4) RedShift: Data warehousing and business intelligence (eg: profit loss calculation from inventory)

## Migration

1) AWS Migration Hub
2) Application Discovery Service
3) Database Migration service : Used to migrate on-premise data to AWS
4) Server Migration Service
5) Snowball

## Networking and Content Delivery

1) VPC: Virtual Private Cloud
2) Cloud Front: AWS Content Delivery Network : Does the edge transfer
3) Route 53: DNS service for AWS
4) API Gateway:
5) Direct Connect: Dedicated line from your corporate head office to AWS VPC

# Developers Tools (Not part of the exam)

1) Codestar: Collaboration Platform
2) CodeCommit: It is a source code Management
3) CodeBuild: Jenkins
4) CodeDeploy: Deploys the code to EC2 instance as well as on-premise as welll as Lambda
5) CodePipeline:
6) XRay: Troubleshoot your Lambda functions and other applications
7) Cloud9: Cloud IDE (Integrated Development Environment)

## Management Tools

1) CloudWatch : Monitoring Service
2) CloudFormation : For Solution Architecture (scripting infrastructure as a code)
3) CloudTrail : Audit trail for all activities
4) Config: Monitors the config of entire AWS, you can visualise the configuration and backup  or create snapshot.
5) OpsWorks : Chef and Puppet to automate the configuration
6) Service Catalog: Catalog of IT services OS, Images etc for complaiance
7) System Manager: for rolling out patches, group resources
8) Trusted Advisor: Suggests around securities, ports, risks, services not utilised, how to save money.
9) Managed Services:

# Media Services

1) Elastic Transcoder:  Converts a media experience better for mobile and pads
2) MediaConvert
3) MediaLive
4) MediaPackage
5) MediaStore : Storeage service optimised for Media
6) Media Tailor

# Machine Learning

1) SageMaker: Deep learning (Neural Networks)
2) Comprehend: Sentiment Analyser
3) DeepLens: Intuative Decision making camera, physical hardware
4) Lex : Amazon Alexa service
5) Machine Learning: Basic Machine Learning, AWS prediction Service
6) Polly : Text to speech converter
7) Rekognition : Image and Video recognition
8) Amazon Translate:
9) Transcribe : Speech Recognition and Text conversion in different languages

## Analytics

1) Athena: To run queries in S3 objects
2) EMR: Elastic Map Reduce, process large amount of data, big data Solution
3) CloudSearch
4) ElasticSearch
5) Kinesis : Way of ingesting large amount of data, Video, hashtags, twitter, facebook
6) Kinesis Video Streams : process video streams
7) QuickSight: Business Intelligence tool
8) Data Pipeline: service used to move data across different AWS resources
9) Glue: ETL, Extract Transform Load

## Security, Identify and Compliance

1) IAM: Identity Access Management
2) Cognito: Device Authentication using facebook/gmail/linkedin etc from your mobile to get temporary access to an AWS resources
3) GuardDuty: Monitors malicious activity
4) Inspector: Agent install on a machine and run tests against it. for eg: to check the security vulnerabilities
5) Macie: Scans S3 bucket for PII personal identification info like credit
6) Certificate Manager: provides SSL certificates if the domains purchased through Route53
7) CloudHSM: Hardware Security Module, store public/private keys.. encrypt objects on S3 etc.
8) Directory Services: Integrates Microsoft AD with AWS
9) WAF : Web Application Firewall, SQL injection, cross-site interferrance
10) Shield: Prevents DDOS attacks on IPGateway, Route53.. Advance Shield: Need not to pay for AWS servoces during DDOS
11) Artifact: SOC Service Organisation Control , Download and inspect amazon documentation, manage agreements, PCI Payment Card Industry report.

# Mobile services

1) Mobile Hub: Management Console for Mobile Apps
2) PinPoint: Targeted push notifications for customers
3) AWS AppSync: updates data between web and mobile at real time, does offline sync once device comes online.
4) Device Farm: test applications on real life devices
5) Mobile Analytics

# AR/ VR (Augmented and Virtual Reality)

1) Sumerian: Language and common set of Tools
2)

## Application Integration

1) Step Functions: For managing Lambda Functions
2) Amazon MQ: JMS, AMQP, MQTT, STOMP
3) SNS: Simple Notification Services (example billing alerts)
4) SQS: Simple Queue Service: decouple your apps
5) SWF: Simple Workflow Services

# Customer Engagement:

1) Connect: Your very own call center
2) Simple Email Service:

# Business Productivity:

1) Alexa for Business: Dial in a meeting room, inform IT printer is broken, or refill the ink
2) Chime: used for video conferencing
3) Work Docs: Drop box like apps
4) WorkMail : Amazon's gmail

## Desktop and App streaming:

1) Workspaces: VDI Solution, Desktops running on Cloud
2) AppStream 2.0: Like Citrix Service

# IOT:

1) iOT
2) iOT Device Management
3) Amazon FreeRTOS: OS for micro-controllers
4) GreenGrass : Software that let you run things on devices

# Game Development

1) GameLift: Service to help you develop the games.
