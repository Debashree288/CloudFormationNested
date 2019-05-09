Nested Cloudformation template having files cfn-resources,cfn-networking & cfn-nested for each development, management and production and gives an underlaying infrastructure of 3 separate environments with all their VPCs peered with each other.
  
  1.Development (cfn-dev-resouces, cfn-dev-networking and cfn-nested-dev)
  2.Management (cfn-mgmt-resouces, cfn-mgmt-networking and cfn-nested-mgmt)
  3.Production (cfn-prod-resouces, cfn-prod-networking and cfn-nested-prod)
  4.VPCPeering (cfn-vpc-peering which peers the 3 VPCS)
  5.cfn-master-stack ( final stack which needs to be deployed which has all the environment stacks nested)
  
  
