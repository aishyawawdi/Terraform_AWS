This code is Running docker image on AWS instance "EC2" . 
the instance is on VPC with TWO subnets.
the code Runs an AWS Load Balancer (ALB) that directs the traffic to the instance.

Docker image: aishy/bitcoin
Description: Python code that shows the latest bitcoin price in USD.

Requirements: 
1- Terraform installed on your machine.
2- AWS account
3- keypair (if you dont have make one in your aws acc) and download it to your machine.
4- place your access_key and secret_key in the aws-provider in the code. (line 4+5).
5- change the key_name in the code(line 157) to yours.


How to run:
-use the command "terraform plan" and then "terraform apply" in your terminal.
- terraform will print for you the server public IP, use that IP with port 5000 on your browser to view the page. (URL: http://THE-PUBLIC-IP:5000 )
  in which you change THE_PUBLIC-IP with the given IP.

