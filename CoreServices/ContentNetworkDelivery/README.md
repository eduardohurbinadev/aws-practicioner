# Amazon VPC and Direct Connect
## Amazon Virtual Private Cloud (VPC)
> A logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define.

![VPC](./VPC.png)
- Enables virtual networks in AWS
- Supports IPv4 and IPv6
- Allows for configuration of
    - IP address range
    - Subnets
    - Route tables
    - Network gateways 
- Support public & private subnets
- Can utilize NAT for private subnets
- Enables a connection to your data center
- Can connect to other VPCs
- Supports private connections to many AWS services

## AWS Direct Connect
> A cloud service solution that makes it easy to establish a dedicated network connection from you data center to AWS.

## Amazon Route 53
> DNS translates more readily memorized domain names to the numerical IP addresses needed for locating and identifying computer services and devices with the underlying network protocols. 

- Domain Name Services (DNS)
- Global AWS service (not regional)
- Highly available
- Enables global resource routing

## Elastic Load Balancing
**Elasticity:** *The ability for the infrastructure supporting an application to grow and contract based on how much it is used at a point in time*

- Distributes traffic across multiple targets
- Integrates with EC2, ECS, and Lambda
- Supports one or more AZs in a region
- Three types of load balancers:
    - Application Load Balancer (ALB)
    - Network Load Balancer (NLB)
    - Classic Load Balancer

## Amazon CloudFront
- Content Delivery Network
- Enables users to get content from server closest to them
- Supports static and dynamic content
- Utilizes AWS edge locations
- Includes advanced security features
    - AWS Shield for DDoS
    - AWS WAF

## Amazon API Gateway
- Fully managed API management service 
- Directly integrates with multiple AWS services
- Provides monitoring & metrics on API calls
- Supports VPC and on-premise private applications

## AWS Global Accelerator
> Is a networking service that sends your user's traffic through Amazon Web Service's global network infrastructure, improving your internet user performance by up to 60%.

- Utilizes IP addresses that route to edge locations
- Once request reaches edge locations, traffic is routed through AWS network
- Can route requests to many AWS resources:
    - Network Load Balancer (NLB)
    - Application Load Balancer (ALB)
    - EC2 Instances
    - Elastic IP Address

### Performance Improvements
- Distance between user and initial endpoint is minimized by using edge locations
- Traffic is optimized by using AWS network instead of Public Internet
- Results in improvement of first byte latency, jitter, and throughput
- Provides superior fault tolerance by not relying on DNS resolution

