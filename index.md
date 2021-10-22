# The Rosetta stone of public clouds

Have you encountered the problem where you didn't know how a different cloud provider named their solution for the similar use-case?

Here's my solution!

## Compute

| Description | Azure | Alibaba | AWS | GCP |
| --- | --- | --- | --- | --- |
| **Virtual Servers** | [Azure VMs](https://azure.microsoft.com/en-us/services/virtual-machines/) | [Elastic Compute Service (ECS)](https://www.alibabacloud.com/product/ecs) | [Elastic Compute Cloud (EC2)](https://aws.amazon.com/ec2/) | [Compute Engine VMs](https://cloud.google.com/compute) |
| **GPU Servers** | [Azure VMs](https://azure.microsoft.com/en-us/services/virtual-machines/) (GPU optimized) | [Elastic GPU Service (EGS)](https://www.alibabacloud.com/product/gpu) | [EC2 Elastic GPUs](https://aws.amazon.com/ec2/elastic-graphics/) | [Cloud GPUs](https://cloud.google.com/gpu) |
| **Auto Scaling** | [VM Scale Sets](https://azure.microsoft.com/en-us/services/virtual-machine-scale-sets/) | [Auto Scaling](https://www.alibabacloud.com/product/auto-scaling) | [Auto Scaling](https://aws.amazon.com/autoscaling/) | [Autoscaler](https://cloud.google.com/compute/docs/autoscaler) |
| **Container Management** | Container Service for [Kubernetes (AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/) | [Container Service](https://www.alibabacloud.com/product/container-service) | [Elastic Container Service (ECS)](https://aws.amazon.com/ecs/) | [Containers](https://cloud.google.com/containers) |
| **Pre-emptible VMs** | [Azure Batch Compute](https://docs.microsoft.com/en-us/azure/batch/) | [Alibaba Batch Compute](https://www.alibabacloud.com/product/batch-compute?spm=a3c0i.63551.1097638.dnavproductsa14.4c101cddCur1IF) | [AWS EC2 Spot Instances](https://aws.amazon.com/ec2/spot/) | [Pre-emptible VMs](https://cloud.google.com/preemptible-vms) |
| **High-performance computing** | [Azure HPC](https://docs.microsoft.com/en-us/azure/architecture/topics/high-performance-computing) | [ECHP](https://www.alibabacloud.com/product/ehpc?spm=a2c63.l28256.1097650.dznavproductsa7.348b60e940isnd) | [AWS HPC](https://aws.amazon.com/hpc/) | [HPC](https://cloud.google.com/solutions/hpc) |
| **Work management** | [Azure Batch](https://docs.microsoft.com/en-us/azure/batch/) | [Batch Compute](https://www.alibabacloud.com/product/batch-compute?spm=a2796.11283929.1097650.dzhnavproducts0.39fa31983uEUU1) | [AWS Batch](https://aws.amazon.com/batch/) | [DataFlow](https://cloud.google.com/dataflow) |
| **Serverless** | [Azure Functions](https://azure.microsoft.com/en-us/services/functions/) | [Function Compute](https://www.alibabacloud.com/product/function-compute) | [AWS Lambda](https://aws.amazon.com/lambda/) | [Cloud Functions](https://cloud.google.com/functions) |

## Storage & CDN

| Description | Azure | Alibaba | AWS | GCP |
| --- | --- | --- | --- | --- |
| **Object Storage** | [Azure Blob Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/) | [Object Storage Service (OSS)](https://www.alibabacloud.com/product/oss) | [Amazon Simple Storage Services (S3)](https://aws.amazon.com/s3) | [Cloud Storage](https://cloud.google.com/storage) |
| **Archival** | [Azure Archive Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-storage-tiers?tabs=azure-portal) | [OSS (Cold) Archive](https://www.alibabacloud.com/solutions/backup_archive) | [S3 Glacier](https://aws.amazon.com/glacier/) | [Cloud Storage for archival](https://cloud.google.com/storage/archival) |
| **NoSQL Database** | [Azure Table Storage](https://docs.microsoft.com/en-us/azure/storage/tables/table-storage-overview), CosmosDB | [Table Store](https://www.alibabacloud.com/product/table-store), [MongoDB](https://www.alibabacloud.com/product/apsaradb-for-mongodb) | [DynamoDB](https://aws.amazon.com/dynamodb/), [SimpleDB](https://aws.amazon.com/simpledb/) | [DataStore](https://cloud.google.com/datastore) |
| **Content Delivery** | [Azure CDN](https://docs.microsoft.com/en-us/azure/cdn/) | [Alibaba Cloud CDN](https://www.alibabacloud.com/product/cdn) | [CloudFront](https://aws.amazon.com/cloudfront/) | [Cloud CDN]() |
| **Shared File Storage** | Azure File Storage, [Data Lake Store](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction?toc=%2Fazure%2Fstorage%2Fblobs%2Ftoc.json) | [Network Attached Storage (NAS)](https://www.alibabacloud.com/product/nas) | [Elastic File System (EFS)](https://aws.amazon.com/efs/) | [FileStore]() |
| **Hybrid Storage** | [StorSimple](https://docs.microsoft.com/en-us/azure/storsimple/) | [Hybrid Cloud Storage Array](https://www.alibabacloud.com/product/storage-array?spm=a3c0i.11401437.1097638.dnavproductsb5.29dd5fbdvZAomK) | [Hybrid Cloud Storage](https://aws.amazon.com/products/storage/hybrid-cloud-storage/) | Through partners |

## Networking

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
| **Networking** | [Virtual Network (VNET)](https://azure.microsoft.com/en-us/services/virtual-network/) | [Virtual Private Cloud (VPC)](https://www.alibabacloud.com/product/vpc) | [Virtual Private Cloud (VPC)](https://aws.amazon.com/vpc/) | [Virtual Private Cloud (VPC)](https://cloud.google.com/vpc) |
| **Dedicated Connection** | [ExpressRoute](https://azure.microsoft.com/en-us/services/expressroute/) | [Express Connect](https://www.alibabacloud.com/product/express-connect) | [Direct Connect](https://aws.amazon.com/directconnect/) | [Cloud Interconnect](https://cloud.google.com/network-connectivity/docs/interconnect/concepts/dedicated-overview) |
| **NAT Gateway** | part of Network Load Balancer | [NAT Gateway](https://www.alibabacloud.com/product/nat) | [NAT Gateway](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html) | [Cloud NAT](https://cloud.google.com/nat/) |
| **Load Balancing** | [Load Balancer](https://azure.microsoft.com/en-us/services/load-balancer/) | [Server load Balancer(SLB)](https://www.alibabacloud.com/product/server-load-balancer) | [Elastic Load Balancing (ELB)](https://aws.amazon.com/elasticloadbalancing/) | [Cloud Load Balancing](https://cloud.google.com/load-balancing) |
| **Elastic IPs** | [Reserved IP](https://azure.microsoft.com/hu-hu/blog/reserved-ip-addresses/) | [Elastic IP](https://www.alibabacloud.com/product/eip) | [Elastic IP Address](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) | [Static IP](https://cloud.google.com/compute/docs/ip-addresses/reserve-static-external-ip-address) |
| **Cross-premises Connectivity** | [VPN Gateway](https://azure.microsoft.com/en-us/services/vpn-gateway/) | [VPN Gateway](https://www.alibabacloud.com/product/vpn-gateway) | [VPN Gateway](https://aws.amazon.com/vpn/) | [Cloud VPN](https://cloud.google.com/network-connectivity/docs/vpn) |

## Databases

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
| **Relational Databases** | [Azure MySQL](https://azure.microsoft.com/en-us/services/mysql/) / PostgreSQL, Azure SQL, Azure Managed SQL Instances | [ApsaraDB for RDS (MySQL, PostgreSQL, MS SQL), Distributed RDS](https://www.alibabacloud.com/product/apsaradb-for-rds) | [Amazon Aurora](https://aws.amazon.com/rds/aurora/?c=db&amp;sec=srv), [Amazon RDS](https://aws.amazon.com/rds/?c=db&amp;sec=srv) | [Cloud SQL](https://cloud.google.com/sql), [Spanner](https://cloud.google.com/spanner) |
| **Caching** | [Azure Cache Redis](https://azure.microsoft.com/en-us/services/cache/) | [ApsaraDB for Redis/Memcache](https://www.alibabacloud.com/product/apsaradb-for-redis) | [Amazon ElastiCache for Memcached](https://aws.amazon.com/elasticache/memcached/?c=db&amp;sec=srv)[Amazon ElastiCache for Redis](https://aws.amazon.com/elasticache/redis/?c=db&amp;sec=srv) | [Memorystore](https://cloud.google.com/memorystore) |
| **Elastic Data Warehouse** | [Azrue Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) | [HybridDB for PostgreSQL](https://www.alibabacloud.com/product/hybriddb-postgresql) |  [Amazon Redshift](https://aws.amazon.com/redshift/?c=db&amp;sec=srv) | [BigQuery](https://cloud.google.com/bigquery) |
| **NoSQL - Document Storage** | [CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) for MongoDB,CosmosDB SQL (aka DocumentDB) | [ApsaraDB for MongoDB](https://www.alibabacloud.com/product/apsaradb-for-mongodb) | [Amazon DocumentDB](https://aws.amazon.com/documentdb/?c=db&amp;sec=srv) | [Firestore](https://cloud.google.com/firestore) |
| **NoSQL – Key/Value** | [CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) Table, [CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) Cassandra | [Table Store](https://www.alibabacloud.com/product/table-store?spm=a2796.7990255.247275.17.7c0a61c50lc9oq) | [Amazon DynamoDB](https://aws.amazon.com/dynamodb/?c=db&amp;sec=srv) | [Cloud BigTable](https://cloud.google.com/bigtable) |
| **NoSQL – Graph** | [CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) Graph (Tinkerpop, Gremlin) | [GraphDB (GDB)](https://www.alibabacloud.com/help/product/102714.htm) | [Amazon Neptune](https://aws.amazon.com/neptune/?c=db&amp;sec=srv) | N/A |
| **Time-series Database** | [Time Series Insights](https://azure.microsoft.com/en-us/services/time-series-insights/) | [High-Performance Time Series Database](https://www.alibabacloud.com/product/hitsdb?spm=a2796.147402.1097650.dznavproductsd8.53243586Ecs5qw) | [Amazon Timestream](https://aws.amazon.com/timestream/?c=db&amp;sec=srv) | [BigTable?](https://cloud.google.com/bigtable) |
| **Ledger** | [Azure Blockchain Tokens](https://azure.microsoft.com/en-us/services/blockchain-tokens/) | N/A | [Amazon QLDB](https://aws.amazon.com/qldb/?c=db&amp;sec=srv) | Through partners |
| **Database Migration** | [Database Migration Service](https://azure.microsoft.com/en-us/services/database-migration/) | [Data Transmission Service (DTS)](https://www.alibabacloud.com/product/data-transmission-service) | [Database Migration Services (DMS)](https://aws.amazon.com/dms/) | [Database Migration Service (DMS)](https://cloud.google.com/database-migration) |

## Security

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
| **DDoS Mitigation** | [DDoS Protection Service](https://azure.microsoft.com/en-us/services/ddos-protection/) | [Anti-DDoS Basic](https://www.alibabacloud.com/product/anti-ddos) | [AWS Shield](https://aws.amazon.com/shield/) | [Google Cloud Armor](https://cloud.google.com/armor) |
| **Mobile Security** | ? | [Mobile Security](https://www.alibabacloud.com/product/mobile-security) | [Cognito](https://aws.amazon.com/cognito/)? | [Endpoint management](https://cloud.google.com/identity/em) |
| **Web Application Security** | [Web Application Firewall](https://azure.microsoft.com/en-us/services/web-application-firewall/) | [Web Application Firewall](https://www.alibabacloud.com/product/waf) | [Web Application Firewall (WAF)](https://aws.amazon.com/waf/) | [Cloud Armor WAF](https://cloud.google.com/armor) |
| **Instance Security** | N/A | [Server Guard](https://www.alibabacloud.com/product/server-guard) | N/A | N/A |
| **Certificate Service** | Part of Azure AppService | [SSL Certificates Service](https://www.alibabacloud.com/product/certificates) | [Certificate Manager](https://aws.amazon.com/certificate-manager/) | Yes |

## Monitoring & Management

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
| **Monitoring** | [Azure Monitor](https://azure.microsoft.com/en-us/services/monitor/) | [CloudMonitor](https://www.alibabacloud.com/product/cloud-monitor?spm=a2796.126074.1097650.dznavproductsf1.79ee3c1fNusYR0) | [CloudWatch](https://aws.amazon.com/cloudwatch/) | [Cloud Monitoring](https://cloud.google.com/monitoring) |
| **Authentication and Authorization** | [Azure Active Directory](https://azure.microsoft.com/en-us/services/active-directory/) | [Resource Access Management](https://www.alibabacloud.com/product/ram) | [Identity & Access Management(IAM)](https://aws.amazon.com/iam/) | [Cloud Identity & Access Management](https://cloud.google.com/iam) |
| **Key Mgmt** | [Azure KeyVault](https://azure.microsoft.com/en-us/services/key-vault/) | [Key Management Service](https://www.alibabacloud.com/product/kms) | [Key Management Service (KMS)](https://aws.amazon.com/kms/) | [Cloud Key Management](https://cloud.google.com/security-key-management) |
| **Resource Orchestration** | [Azure Resource Manager](https://azure.microsoft.com/en-us/features/resource-manager/) | [Resource Orchestration Service](https://www.alibabacloud.com/product/ros) | [CloudFormation](https://aws.amazon.com/cloudformation/) | [Cloud Composer](https://cloud.google.com/composer) |

## Domains & Webapps

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
| **Web Applications** | [Azure AppService](https://azure.microsoft.com/en-us/services/app-service/) | [Web Hosting](https://www.alibabacloud.com/product/hosting) | [Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) | [App Engine](https://cloud.google.com/appengine) |
| **Domain Name** | [Azure DNS](https://azure.microsoft.com/en-us/services/dns/) | [Domains](https://www.alibabacloud.com/domain) | [Route 53](https://aws.amazon.com/route53/) | [Google Domains](https://domains.google/) |
| **Domain Name System (DNS)** | [Azure DNS](https://azure.microsoft.com/en-us/services/dns/), [Azure Traffic Manager](https://azure.microsoft.com/en-us/services/traffic-manager/) | [Alibaba Cloud DNS](https://www.alibabacloud.com/product/dns) | [Route 53](https://aws.amazon.com/route53/) | [Cloud DNS](https://cloud.google.com/dns/) |

## Analytics

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
| **Big Data Processing** | [Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) | [MaxCompute](https://www.alibabacloud.com/product/maxcompute), [E-MapReduce](https://www.alibabacloud.com/product/e-mapreduce) | [Amazon EMR](https://aws.amazon.com/emr/) | [Dataproc]() |
| **Data Visualization** | PowerBI | [DataV](https://www.alibabacloud.com/product/datav), [QuickBI](https://www.alibabacloud.com/product/quickbi?spm=a3c0i.11216507.1097638.dnavproductsh4.54582d07qP2rNX) | [Amazon QuickSight](https://aws.amazon.com/quicksight/) | [Data Studio](https://datastudio.google.com/), [Looker](https://cloud.google.com/looker) |
| **Development Platform** | [Data Lake analytics](https://azure.microsoft.com/en-us/services/data-lake-analytics/) | [DataWorks](https://www.alibabacloud.com/product/ide) | [Data Lake](https://aws.amazon.com/big-data/datalakes-and-analytics/) |   |

## Application Service

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
| **Notification Service** | [Notification Hubs](https://azure.microsoft.com/en-us/services/notification-hubs/), Azure [Event Grid](https://azure.microsoft.com/en-us/services/event-grid/) | [Message Service](https://www.alibabacloud.com/product/message-service) | [Amazon Simple Notification Service (SNS)](https://aws.amazon.com/sns/) | N/A |
| **API Service** | [API Management](https://azure.microsoft.com/en-us/services/api-management/) | [API Gateway](https://www.alibabacloud.com/product/api-gateway) | [API Gateway](https://aws.amazon.com/api-gateway/) | [Cloud APIs](https://cloud.google.com/apis) |
| **Log Service** | Log Analytics, App Insights | [Log Service](https://www.alibabacloud.com/product/log-service) | [CloudTrail?](https://aws.amazon.com/cloudtrail/) | [Cloud Logging](https://cloud.google.com/logging) |
| **Email Sending and Receiving** | Through 3rd party offering SendGrid | [DirectMail](https://www.alibabacloud.com/product/directmail) | [Amazon Simple Email Service (SES)](https://aws.amazon.com/ses/) | through [SendGrid](https://cloud.google.com/compute/docs/tutorials/sending-mail/using-sendgrid) |
| **Queues** | [Azure Queue Storage](https://azure.microsoft.com/en-us/services/storage/queues/), [Azure Service Bus](https://azure.microsoft.com/en-us/services/service-bus/) | [Message Queue](https://www.alibabacloud.com/product/mq?spm=a3c0i.176005.1097638.dznavproductsk2.56794206T5MDv8) | [Amazon Simple Queue Service (SQS)](https://aws.amazon.com/sqs/) | [Pub/Sub](https://cloud.google.com/pubsub) |

## Media Services

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |
