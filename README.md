## Amazon EC2

It mainly consists in the capability of :
• Renting virtual machines (EC2)
• Storing data on virtual drives (EBS)
• Distributing load across machines (ELB)
• Scaling the services using an auto-scaling group (ASG)


## Amazon S3

Amazon S3 is one of the main building blocks of AWS
• It’s advertised as ”infinitely scaling” storage
• Many websites use Amazon S3 as a backbone
• Many AWS services use Amazon S3 as an integration as well
• We’ll have a step-by-step approach to S3
• The CCP exam requires “deeper” knowledge about S3


S3 Use cases • Backup and storage • Disaster Recovery • Archive • Hybrid Cloud storage • Application hosting • Media hosting • Data lakes & big data analytics • Software delivery • Static website

### Buckets
Amazon S3 allows people to store objects (files) in “buckets” (directories)
• Buckets must have a globally unique name (across all regions all accounts)
• Buckets are defined at the region level
• S3 looks like a global service but buckets are created in a region