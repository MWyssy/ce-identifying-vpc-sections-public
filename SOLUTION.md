1.  For now you can assume that all your customers are going to be located within the United Kingdom. What AWS region do you think your VPC should be set up in?

    - eu-west-2

2.  Now you have decided the AWS region it is time to move on to the availability zones. Which availability zones will you use? (Remember to check the diagram as well)

    - I will use all three availability zones to ensure stability. eu-west-2a, eu-west-2b, and eu-west-2c.

3.  What IP range will you use for definining your VPC and why have you chosen that range?

    💡 Hint: You should specify a CIDR range for your VPC

    - I will have a CIDR range of 172.31.0.0/16

4.  Now you have your VPC range, it is time to define the subnets.

        How many subnets do you require?
        What IP range will you use for each subnet?

    💡 Hint: You might want to give each subnet a name that relates to its purpose and location

    - I will require 6 subnets, two for each availability zone, one private, and the other public:
      - 172.31.0.0/24 AZ1 - Public
      - 172.31.1.0/24 AZ1 - Private
      - 172.31.2.0/24 AZ2 - Public
      - 172.31.3.0/24 AZ2 - Private
      - 172.31.4.0/24 AZ3 - Public
      - 172.31.5.0/24 AZ4 - Private
