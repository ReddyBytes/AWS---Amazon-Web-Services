## Elastic Compute Cloud ( EC2 ) :
In general when we want to test the application we use different computers are like windowns, ubuntu , macos 

it is difficult to manage/buy diff systems so that AWS created EC2 instances called virtual machines with less cost 

we can launch instance nad deploy our application then test then we can delete instance.

### Key Features

- **Scalability**: Easily adjust capacity to meet demand.
- **Flexibility**: Choose from a wide range of instance types optimized for different use cases.
- **Cost-Effective**: Pay only for the compute power you need.
- **Secure**: Implement security groups to control inbound/outbound traffic.


### Types of EC2 instances  

1) On Demand Instance
2) Reserved Instances
3) Spot Instances
4) Launch Template Instances


### 1) On Demand Instance 
- General instances that we create for daily usecase like testing, development purpose etc .
- it automatically creates EBS volume as the backup
- like buying instance in online market

[see here](/1_EC2/on-demand-instance.md) for how to create on demand instance
![](/images/ec2/on%20demand%20instance.png)

### 2) Reserved Instances 
- when we know that our application need an instances upto long term like years then AWS recommends to use reserved instances because these are like wholesale or cheap instances in terms of cost compared to on demand instances.

- like buying instance in wholesale market

![](/images/ec2/reserved%20instance.png)

see the price difference for `t3.large` for on demand and reserved instances.


### 3) Spot Instance
- depends on the workload this instance will charge
- when the workload increases then spot instance will notify for 2 minutes and automatically terminates 
- in advanced settings we can enable for spot instance 
- buying instacne in discount sale

![](/images/ec2/spot%20instance.png)