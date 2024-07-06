
## Steps to Create an On-Demand EC2 Instance

1. **Log in to the AWS Management Console**: Navigate to the Amazon EC2 dashboard.

![](/images/ec2/ec21.png)

2. **Launch Instance**: From the navigation pane, select "Instances" > "Launch Instance".

![](/images/ec2/ec22.png)

3. **Choose an Amazon Machine Image (AMI)**: AMI isa template that contains a software configuration. This configuration can include an operating system, an application server, and applications.

![](/images/ec2/ec23.png)

4. **Select an Instance Type**: Choose an instance type based on your application's needs. Factors to consider include CPU, memory, and storage requirements.

![](/images/ec2/ec24.png)

5. **Select Key pair** : choose your key pair ( file that is used to connect to ur instance ) 
- if there is no pem file then create a new pem file 

![](/images/ec2/ec25.png)

- .pem is used to connect to instance through terminal ssh command 
- .putty is used to connect to instance through putty interface

6. **Configure Instance Details**: Specify details like the number of instances, network settings, and whether to enable auto-assign public IP.

![](/images/ec2/ec26.png)  


7. **Add Storage**: Allocate storage space according to your application's needs. You can choose either Amazon Elastic Block Store (EBS) volumes or instance store volumes.

![](/images/ec2/ec27.png)



8. **Review and Launch**: Review your instance configuration. Make sure you have a key pair if you plan to access your instance via SSH. If you don't have a key pair, you won't be able to access your instance.

![](/images/ec2/ec28.png)

9. **Successfull message** 
![](/images/ec2/ec29.png)

10. **ec2 connection through ssh**   
 open terminal and use below command
 here i used AMI as ubuntu 
       
         ssh -i <pem file name> ubuntu@<ipname>