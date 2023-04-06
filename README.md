# VPC
   Amazon Virtual Private Cloud (Amazon VPC) enables you to launch AWS resources into a virtual network that you've defined. This virtual network closely resembles a traditional network that you'd operate in your own data center, with the benefits of using the scalable infrastructure of AWS.

#### Features
     The following features help you configure a VPC to provide the connectivity that your applications need:

#### Virtual private clouds (VPC)
     A VPC is a virtual network that closely resembles a traditional network that you'd operate in your own data center. After you create a VPC, you can add subnets.

#### Subnets
     A subnet is a range of IP addresses in your VPC. A subnet must reside in a single Availability Zone. After you add subnets, you can deploy AWS resources in your VPC.

#### IP addressing
     You can assign IP addresses, both IPv4 and IPv6, to your VPCs and subnets. You can also bring your public IPv4 and IPv6 GUA addresses to AWS and allocate them to resources in your VPC, such as EC2 instances, NAT gateways, and Network Load Balancers.

#### Routing
     Use route tables to determine where network traffic from your subnet or gateway is directed.

#### Gateways and endpoints
     A gateway connects your VPC to another network. For example, use an internet gateway to connect your VPC to the internet. Use a VPC endpoint to connect to AWS services privately, without the use of an internet gateway or NAT device.

#### Peering connections
     Use a VPC peering connection to route traffic between the resources in two VPCs.

#### Traffic Mirroring
     Copy network traffic from network interfaces and send it to security and monitoring appliances for deep packet inspection.

#### Transit gateways
     Use a transit gateway, which acts as a central hub, to route traffic between your VPCs, VPN connections, and AWS Direct Connect connections.

#### VPC Flow Logs
     A flow log captures information about the IP traffic going to and from network interfaces in your VPC.

#### VPN connections
     Connect your VPCs to your on-premises networks using AWS Virtual Private Network (AWS VPN).

#### Getting started with Amazon VPC
     Your AWS account includes a default VPC in each AWS Region. Your default VPCs are configured such that you can immediately start launching and connecting to EC2 instances. For more information, see Get started with Amazon VPC.

      we can choose to create additional VPCs with the subnets, IP addresses, gateways and routing that you need. For more information, see Create a VPC.

#### Working with Amazon VPC
       we can create and manage your VPCs using any of the following interfaces:

#### AWS Management Console 
     — Provides a web interface that you can use to access your VPCs.

#### AWS Command Line Interface (AWS CLI)
      — Provides commands for a broad set of AWS services, including Amazon VPC, and is supported on Windows, Mac, and Linux. For more information, see AWS Command Line Interface.

#### AWS SDKs
      — Provides language-specific APIs and takes care of many of the connection details, such as calculating signatures, handling request retries, and error handling. For more information, see AWS SDKs.

#### Query API
      — Provides low-level API actions that you call using HTTPS requests. Using the Query API is the most direct way to access Amazon VPC, but it requires that your application handle low-level details such as generating the hash to sign the request, and error handling. 