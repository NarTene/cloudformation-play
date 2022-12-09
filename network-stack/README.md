-  This template deploys a VPC, with a pair of public and private subnets spread
  across two Availability Zones. It deploys an internet gateway, with a default
  route on the public subnets. It deploys a pair of NAT gateways (one in each AZ),
  and default routes for them in the private subnets.


  All resources values will be exported (cross-stack)

  The network stack is used to deploy an ec2 server using the export and import statements.

  ..................................................................................................................................................................