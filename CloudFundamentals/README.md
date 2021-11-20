# Cloud Fundamentals

## Understanding Cloud Computing
### Benefits of Cloud Computing
- Agility 🏃
    - You can deploy technology services in a matter of minutes, and get from the idea to implementation serveral orders of magnitude faster than before. This gives you the **freedom to experiment, test new ideas to differentiate customer experiences, and transform your business**.
- Elasticity 📈
    - You don't have to over-provision resources up front to handle peak levels of business activity in the future. Instead, you provision the amount of resources that you actually need. **You can scale these resources up or down to instantly grow and shrink capacity as your business needs change**.
- Cost Savings 🏦
    - **The cloud allows you to trade capital expenses, and only pay for IT as you consume it**. Plus, the variable expenses are much lower than what you would pay to do it yourself because of the economies of scale.
- Deploy Globally in Minutes 🌎
    - With the cloud, **you can expand to new geographic regions and deploy globally in minutes**. Putting applications in closer proximity to end users reduces latency and improves their experience.
### Types of Cloud Computing
- Infrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)
## AWS Global Infrastructure
### Regions
- Is a physical location around the world where we cluster data centers
- Each AWS Region consists of multiple, isolated, and physically separate AZs within a geographic area.
### Availability Zones
- Consists of one or more data centers.
- Multiple availability zones are included
with each AWS Region.
- Located within the geographic area of
the AWS Region
- Redundant power, networking and
connectivity
- There are currently 69 availability
zones globally
### Edge Locations
- Used as nodes of a global content
delivery network (CDN).
- Utilized by Amazon CloudFront and
Amazon Route 53.
- Located globally at over 200 different
locations.
_ Allows AWS to serve content from
locations closest to users.
## Understanding Cloud Economics 💰
### AWS Migration Evaluator / Total Cost of Ownership (TCO) Calculator 
For organizations that are considering moving workload from their data center to the cloud. Enables an organization to determine what could be saved by leveraging cloud infrastructre.
### AWS Pricing Calculator / Simple Monthly Calculator
Enables an organization to calculate the cost of running specific AWS infrastructure.
### Cost Explorer 💰🔎
- User Interface for exploring your AWS costs
- Provides **breakdowns** including:
    - By service
    - By cost tag
- Provides **predictions for the next three months of costs**.
- Gives **recommendations** for cost
optimization
- Can be accessed via **API**
#### AWS Budgets
Utilizes **data from AWS Cost Explorer to plan and track your usage across AWS services**. It can track cost per
service, service usage, reserved instance utilization and
coverage, and Savings Plans utilization and coverage.

#### AWS Organizations
- Allows organizations to manage multiple accounts under a **single master account**. 
- Provides organizations with the ability to leverage **Consolidated Billing for all accounts**.
- Enables organizations to **centralize logging and security standards accross accounts**.
## Supporting AWS Infrastructure
### Support Resources
#### AWS Support
- Enables support from AWS resources for workloads running in the cloud.
- Provided in different tiers based on need and scope.
- Includes tools to provide automated answers and recommendations.
#### AWS Personal Health Dashboard 🏥
AWS Personal Health Dashboard **provides alerts ⚠️🚨 and remediation guidance** when AWS is experiencing events that may impact you.
#### AWS Trusted Advisor 🕵️
- Automated tool to **check your AWS usage against best practices**. ✅
- Accessed from the **AWS console**. 🖥️
- Different checks are provided based on the AWS Support plan tier.
- All AWS customers get access to seven core checks:
    - Cost Optimization
    - Performance
    - Security
    - Fault Tolerance
    - Service Limits
### Support Plan Tiers
#### AWS Basic Support
- Provided for all AWS customers
- Access to Trusted Advisor 
- 24x7 Access to customer service documentation, forums, & whitepapers
- Access to Personal Health Dashboard
- No monthly cost
#### AWS Developer Support
- Includes all features of Basic Support
- Business hours email access to support engineers
- Limited to 1 primary contact
- Starts at $29 per month (tied to AWS usage)
#### AWS Business Support
- Includes all features of Developer support
- Full set of Trusted Advisor checks
- 24x7 phone, email, and chat access to support engineers
- Unlimited contacts
- Provides third-party software support
- Starts at $100 per month (tied to AWS usage)
#### AWS Enterprise Support
- Includes all features of Business support
- Includes designated Technical Account Manager (TAM)
- Includes concierge support team
- Starts at $15,000 per month (tied to AWS usage)
***
|Support | Developer Support | Business Support | Enterprise Support
|--|--|--|--|
| General Guidance | 24 Business Hours | 24 Hours | 24 Hours |
| System Impaired | 12 Business Hours | 12 Hours | 12 Hours |
| Production System Impaired | | 4 Hours | 4 Hours |
| Production System Down | |1 Hours | 1 Hour
| Business-Critical System Down | | |15 Minutes |
### AWS Support Tools
- AWS Quick Starts
- AWS Partner Network Consulting Partners
    - AWS Partners are professional, consulting, or managed services firms that help customers of all types and sizes accelerate their journey to the cloud.
- AWS Professional Services
    - Is a team of experts that can help you realize your desired business outcomes when using the AWS Cloud.
