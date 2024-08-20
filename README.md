# VIRTUAL PRIVATE CLOUD
Definition: A virtual private cloud (VPC) is a virtualized network within a cloud service provider's infrastracture that allows users to create a logically isolated section of the cloud.
We are having some components in this
They are
1)Subnets
2)Route tables
3)Internet gateway
4)NAT gateway
5)Security groups
6)NACLS
7)VPC flow logs
# SUBNETS
Definition: It can divide the VPC'S IP address range into smaller manageable segments subnets can be either public or private.
Types:
1)Public subnets: It have direct internet access through an internet gateway.
2)Private subnets: It didn't have direct internet access it can use NAT gateways or instances for internet access.
# ROUTE TABELS
Definition: A route table in AWS is a set of rules called routes that determine where network traffic from your subnet or gateway should be directed.
We are having some components like
1)Routes: Each route has a destination CIDR block and a target.
2)Destination: The IP range of the destination network the traffic is intended.
3)Target: The destination for the traffic which cloud be an internet gateway.
# INTERNET GATEWAY 
Definition: An internet gateway is a gateway that connects your VPC to the internet enabling resources within the VPC to send and receive internet traffic.
# NETWORK ADDRESS TRASULATION GATEWAY (NAT) 
Definition: NAT gateway in AWS is a managed service that allows instence in a private subnet to intiate outbound internet connections such as for software updates or accessing web services while blocking unsolicited inbound traffic from the internet.
# SECURITY GROUPS
Definition: security groups are used to define rules that control the flow of network traffic and from instences in a VPC this functioned as stateful firewalls.
Security groups in AWS are virtual firewalls that control inbound and outbound traffic for AWS resources such as EC2 instances.
# NETWORK ACCESS CONTROL LISTS (NACLs)
Definition: Network access control lists are stateless firewalls associated with subnets in a VPC that define allowed and denied traffic based on IP addresses,protocols and port ranges.
Network access control lists in AWS are a set of rules that control inbound and outbound traffic and from subnets within a VPC.
# VPC FLOW LOGS
Definition: VPC flow logs provide detailed records of network traffic within your VPC,capturing meta data about each network flow,including source and destination IP adderesses,ports and traffic volume.
      
