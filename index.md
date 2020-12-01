# Cloud Services Rosetta stone

## Compute

| Description | Azure | Alibaba | AWS | GCP |
| --- | --- | --- | --- | --- |
| Virtual Servers | [Azure VMs](https://azure.microsoft.com/en-us/services/virtual-machines/) | [Elastic Compute Service (ECS)](https://www.alibabacloud.com/product/ecs) | [Elastic Compute Cloud (EC2)](https://aws.amazon.com/ec2/) | [Compute Engine VMs](https://cloud.google.com/compute) |
| GPU Servers | [Azure VMs](https://azure.microsoft.com/en-us/services/virtual-machines/) (GPU optimized) | [Elastic GPU Service (EGS)](https://www.alibabacloud.com/product/gpu) | [EC2 Elastic GPUs](https://aws.amazon.com/ec2/elastic-graphics/) | [Cloud GPUs](https://cloud.google.com/gpu) |
| Auto Scale | [VM Scale Sets](https://azure.microsoft.com/en-us/services/virtual-machine-scale-sets/) | [Auto Scaling](https://www.alibabacloud.com/product/auto-scaling) | [Auto Scaling](https://aws.amazon.com/autoscaling/) | [Autoscaler](https://cloud.google.com/compute/docs/autoscaler) |
| Container Management | Container Service for [Kubernetes (AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/) | [Container Service](https://www.alibabacloud.com/product/container-service) | [Elastic Container Service (ECS)](https://aws.amazon.com/ecs/) | [Containers](https://cloud.google.com/containers) |
| Pre-emptible VMs | [Azure Batch Compute](https://docs.microsoft.com/en-us/azure/batch/) | [Alibaba Batch Compute](https://www.alibabacloud.com/product/batch-compute?spm=a3c0i.63551.1097638.dnavproductsa14.4c101cddCur1IF) | [AWS Batch](https://aws.amazon.com/batch/) | [Pre-emptible VMs](https://cloud.google.com/preemptible-vms) |
| High-performance computing | [Azure HPC](https://docs.microsoft.com/en-us/azure/architecture/topics/high-performance-computing) | [ECHP](https://www.alibabacloud.com/product/ehpc?spm=a2c63.l28256.1097650.dznavproductsa7.348b60e940isnd) | [AWS HPC](https://aws.amazon.com/hpc/) | [HPC](https://cloud.google.com/solutions/hpc) |
| Work management | [Azure Batch](https://docs.microsoft.com/en-us/azure/batch/) | [Batch Compute](https://www.alibabacloud.com/product/batch-compute?spm=a2796.11283929.1097650.dzhnavproducts0.39fa31983uEUU1) | [AWS Batch](https://aws.amazon.com/batch/) | [DataFlow](https://cloud.google.com/dataflow) |

## Storage & CDN

| Description | Azure | Alibaba | AWS | GCP |
| --- | --- | --- | --- | --- |
| Object Storage | [Azure Blob Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/) | [Object Storage Service (OSS)](https://www.alibabacloud.com/product/oss) | [Amazon Simple Storage Services (S3)](https://aws.amazon.com/s3) | [Cloud Storage](https://cloud.google.com/storage) |
| NoSQL Database | [Azure Table Storage](https://docs.microsoft.com/en-us/azure/storage/tables/table-storage-overview), CosmosDB | [Table Store](https://www.alibabacloud.com/product/table-store), [MongoDB](https://www.alibabacloud.com/product/apsaradb-for-mongodb) | [DynamoDB](https://aws.amazon.com/dynamodb/), [SimpleDB](https://aws.amazon.com/simpledb/) | [DataStore](https://cloud.google.com/datastore) |
| Content Delivery | [Azure CDN](https://docs.microsoft.com/en-us/azure/cdn/) | [Alibaba Cloud CDN](https://www.alibabacloud.com/product/cdn) | [CloudFront](https://aws.amazon.com/cloudfront/) | [Cloud CDN]() |
| Shared File Storage | Azure File Storage, [Data Lake Store](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction?toc=%2Fazure%2Fstorage%2Fblobs%2Ftoc.json) | [Network Attached Storage (NAS)](https://www.alibabacloud.com/product/nas) | [Elastic File System (EFS)](https://aws.amazon.com/efs/) | [FileStore]() |
| Hybrid Storage | [StorSimple](https://docs.microsoft.com/en-us/azure/storsimple/) | [Hybrid Cloud Storage Array](https://www.alibabacloud.com/product/storage-array?spm=a3c0i.11401437.1097638.dnavproductsb5.29dd5fbdvZAomK) | [Hybrid Cloud Storage](https://aws.amazon.com/products/storage/hybrid-cloud-storage/) | [Through partners] |

## Networking

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
| Networking | [Virtual Network (VNET)](https://azure.microsoft.com/en-us/services/virtual-network/) | [Virtual Private Cloud (VPC)](https://www.alibabacloud.com/product/vpc) | [Virtual Private Cloud (VPC)](https://aws.amazon.com/vpc/) | [Virtual Private Cloud (VPC)](https://cloud.google.com/vpc) |
| Dedicated Connection | [ExpressRoute](https://azure.microsoft.com/en-us/services/expressroute/) | [Express Connect](https://www.alibabacloud.com/product/express-connect) | [Direct Connect](https://aws.amazon.com/directconnect/) | [Cloud Interconnect](https://cloud.google.com/network-connectivity/docs/interconnect/concepts/dedicated-overview) |
| NAT Gateway | N/A (part of Network Load Balancer) | [NAT Gateway](https://www.alibabacloud.com/product/nat) | [NAT Gateway](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html) | [Cloud NAT](https://cloud.google.com/nat/) |
| Load Balancing | [Load Balancer](https://azure.microsoft.com/en-us/services/load-balancer/) | [Server load Balancer(SLB)](https://www.alibabacloud.com/product/server-load-balancer) | [Elastic Load Balancing (ELB)](https://aws.amazon.com/elasticloadbalancing/) | [Cloud Load Balancing](https://cloud.google.com/load-balancing) |
| Elastic IP | [Reserved IP](https://azure.microsoft.com/hu-hu/blog/reserved-ip-addresses/) | [Elastic IP](https://www.alibabacloud.com/product/eip) | [Elastic IP Address](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) | [Static IP](https://cloud.google.com/compute/docs/ip-addresses/reserve-static-external-ip-address) |
| Cross-premises Connectivity | [VPN Gateway](https://azure.microsoft.com/en-us/services/vpn-gateway/) | [VPN Gateway](https://www.alibabacloud.com/product/vpn-gateway) | [VPN Gateway](https://aws.amazon.com/vpn/) | [Cloud VPN](https://cloud.google.com/network-connectivity/docs/vpn) |

## Databases

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
| Relational Database | [Azure MySQL](https://azure.microsoft.com/en-us/services/mysql/) / PostgreSQL, Azure SQL, Azure Managed SQL Instances | [ApsaraDB for RDS (MySQL, PostgreSQL, MS SQL), Distributed RDS](https://www.alibabacloud.com/product/apsaradb-for-rds) | [Amazon Aurora](https://aws.amazon.com/rds/aurora/?c=db&amp;sec=srv), [Amazon RDS](https://aws.amazon.com/rds/?c=db&amp;sec=srv) | [Cloud SQL](https://cloud.google.com/sql), [Spanner](https://cloud.google.com/spanner) |
| Caching | [Azure Cache Redis](https://azure.microsoft.com/en-us/services/cache/) | [ApsaraDB for Redis/Memcache](https://www.alibabacloud.com/product/apsaradb-for-redis) | [Amazon ElastiCache for Memcached](https://aws.amazon.com/elasticache/memcached/?c=db&amp;sec=srv)[Amazon ElastiCache for Redis](https://aws.amazon.com/elasticache/redis/?c=db&amp;sec=srv) | [Memorystore](https://cloud.google.com/memorystore) |
| Elastic Data Warehouse | [Azrue Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) | [HybridDB for PostgreSQL](https://www.alibabacloud.com/product/hybriddb-postgresql) |  [Amazon Redshift](https://aws.amazon.com/redshift/?c=db&amp;sec=srv) | [BigQuery](https://cloud.google.com/bigquery) |
| NoSQL - Document Storage | [CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) for MongoDB,CosmosDB SQL (aka DocumentDB) | [ApsaraDB for MongoDB](https://www.alibabacloud.com/product/apsaradb-for-mongodb) | [Amazon DocumentDB](https://aws.amazon.com/documentdb/?c=db&amp;sec=srv) | [Firestore](https://cloud.google.com/firestore) |
| NoSQL – Key/Value | [CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) Table, [CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) Cassandra | [Table Store](https://www.alibabacloud.com/product/table-store?spm=a2796.7990255.247275.17.7c0a61c50lc9oq) | [Amazon DynamoDB](https://aws.amazon.com/dynamodb/?c=db&amp;sec=srv) | [Cloud BigTable](https://cloud.google.com/bigtable) |
| NoSQL – Graph | [CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) Graph (Tinkerpop, Gremlin) | N/A | [Amazon Neptune](https://aws.amazon.com/neptune/?c=db&amp;sec=srv) | [N/A]() |
| Time-series Database | [Time Series Insights](https://azure.microsoft.com/en-us/services/time-series-insights/) | [High-Performance Time Series Database](https://www.alibabacloud.com/product/hitsdb?spm=a2796.147402.1097650.dznavproductsd8.53243586Ecs5qw) | [Amazon Timestream](https://aws.amazon.com/timestream/?c=db&amp;sec=srv) | [BigTable?](https://cloud.google.com/bigtable) |
| Ledger | [Azure Blockchain Tokens](https://azure.microsoft.com/en-us/services/blockchain-tokens/) | N/A | [Amazon QLDB](https://aws.amazon.com/qldb/?c=db&amp;sec=srv) | [Through partners]() |
| Database Migration | [Database Migration Service](https://azure.microsoft.com/en-us/services/database-migration/) | [Data Transmission Service (DTS)](https://www.alibabacloud.com/product/data-transmission-service) | [Database Migration Services (DMS)](https://aws.amazon.com/dms/) | [Database Migration Service (DMS)](https://cloud.google.com/database-migration) |

## Security

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

## Monitoring & Management

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

## Domains & Websites

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

## Analytics

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

## Application Service

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

## Media Services

| Description | Azure | Alibaba Cloud | AWS | GCP |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |
