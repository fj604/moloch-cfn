# moloch-cfn
Deploy Moloch + Suricata to AWS using CloudFormation
----------------------------------------------------
This CloudFormation template will deploy an instance of Moloch, enhanced with Suricata, listening on UDP port 4789 (VXLAN).
You can create a VPC traffic mirroring target pointing at the ENI of this instance, create filters and monitoring sessions and monitor traffic from your EC2 instances.
