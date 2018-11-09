# Cloud Computing Essentials

## Presenters
    - Jenni Hartman
    - Matthew Rich
    - Research Computing Services

## What even is cloud
    - Cloud: more than just other people's computers
    - Programmable
    - Scalable
    - On Demand
    - Usage-based billing

## Opportunities!
    - low financial barrier to entry
    - easy experimentation
    - securable (different from "secure"!)
    - automatable

## "Levels" of cloud
    - Ready-to-use applications (SaaS, e.g. notebooks)
	- Managed Servers - deploy your own application (PaaS)
	- Infrastructure - virtual hardware and networks (IaaS)
    - mix and match services from all layers for your needs

## Cloud providers
    - AWS
    - Azure
    - GCP
    - Other (IBM, Oracle, Digital Ocean, others?)

## Compute Services
    - Amazon EC2, Azure Virtual Machines, Google Compute Engine
    - On-demand virtual servers
    - Customer manages from the OS level up, Cloud provider manages virtual hardware
    - Closest to "traditional" computing
    - Many different machine configurations (CPU cores, RAM, GPU, disk IOPS)

## Storage Services
    - Object storage: Amazon S3, Azure Blob Storage, Google Cloud Storage, Wasabi
        - Allows you to put & get files over the web
        - Tiered storage available to fit different access patterns
    - File storage: Amazon EFS, Azure File Storage, Google Cloud Filestore
    - Don't forget storage SaaS: Dropbox, Box, Google Drive, Microsoft OneDrive

## Database Services
    - SQL: Amazon RDS, Azure SQL, Google Cloud SQL
    - NoSQL: Amazon DynamoDB, Azure Cosmos DB, Google Bigtable, Datastore, Firestore...

## Event-driven Function Services
    - Run code in response to events in other services, without managing servers!
    - Example: when an Excel file is uploaded to an S3 bucket, transform it to CSV for easy manipulation
    - AWS Lambda, Azure Functions, Google Cloud Functions

## Networking
    - All cloud providers allow for virtual, software defined networks
    - Cloud networks can be connected to campus via VPN if necessary
    - Sophisticated, flexible software-defined firewalls

## Many (many (many)) other services
    - Cloud providers use their own IaaS and event-driven services to offer:
        - Machine Learning
        - Management & Monitoring
        - Developer tools
        - Content delivery
        - Media services
        - etc etc etc

## SECURITY
    - Shared model: In general, the cloud provider is responsible for everything "beneath the surface".
        - physical access to data centers
        - patching of hypervisor hosts
        - software updates to managed systems
        - physical network
    - Customer is responsible for the security of all resources they create!
        - OS patching
        - Firewall rules
        - User access keys
    - Cloud environments can be extremely secure! Or insecure! We are here to help!

## Compliance
    - Cloud can also be HIPAA-compliant!
    - Main cloud providers have "quickstarts" for creating compliant environments
    - Use cases include health-related applications, sharing high-resolution medical imaging, and high-performance computing on identifiable data

## Pricing
    - Everything is billed based on usage
    - Actually understanding your bill is difficult
    - Example: Instance is created with 1TB hard drive. You pay for instance time while it is turned on.
      Shut it down without deleting it tho and you still pay for hard drive space!
    - Ways to save:
        - instance reservations (only if you know you will be utilizing the instance >80% of the 
        time over 12 months)
        - spot/low priority/preemptible instances
        - data storage tiers and lifecycle policies

## Best practices
    - Tag everything
    - Use temporary access keys and MFA wherever possible
    - Never store credentials on instances or in source code
    - Use roles with minimum possible permissions
    - Automate as much as possible
    - Contact us for help!

## How to get started
    - cloud.northwestern.edu
    - existing agreements with AWS & Azure, in conversation with GCP as well

