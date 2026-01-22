# AWS Free Tier - Quick Reference


| Service                             | What it is                 | Free Tier Limit                                                | Notes / Tips                                    | Exceeding Limit → What happens                    |
| ----------------------------------- | -------------------------- | -------------------------------------------------------------- | ----------------------------------------------- | ------------------------------------------------- |
| **EC2 (Virtual Machine / Compute)** | Virtual server to run apps | 750 hours/month of **t2.micro / t3.micro** instance            | Enough to run **1 VM continuously** for a month | Bill generated for extra hours, must pay manually |
| **S3 (Storage)**                    | File storage in cloud      | 5 GB standard storage, 20,000 GET requests, 2,000 PUT requests | Keep small files, delete unused ones            | Bill generated for extra storage/requests         |
| **Lambda (Serverless compute)**     | Run code/functions         | 1 million requests per month, 400,000 GB-seconds               | Great for experiments, no server setup needed   | Bill generated for extra requests/compute time    |
| **RDS (Database)**                  | Managed database           | 750 hours of **db.t2.micro**, 20 GB storage                    | Can run 1 small database continuously           | Bill generated for extra hours/storage            |
| **DynamoDB (NoSQL Database)**       | Key-value database         | 25 GB storage, 25 RCUs / 25 WCUs                               | Good for testing apps                           | Bill generated for extra storage / throughput     |
| **CloudWatch**                      | Monitoring & logging       | 10 custom metrics, 10 alarms                                   | Monitor your free-tier usage                    | Bill generated for extra metrics / alarms         |
| **EBS (Block storage)**             | Storage for EC2            | 30 GB standard SSD                                             | Used with EC2, don’t exceed                     | Bill generated for extra storage                  |
| **VPC / Networking**                | Networking                 | 15 GB outbound data transfer                                   | Free limit applies to internet traffic          | Bill generated for extra network usage            |
