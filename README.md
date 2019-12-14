# moloch-cfn
Deploy Moloch enhanced with Suricata to AWS using CloudFormation
----------------------------------------------------
This CloudFormation template will deploy an instance of [Moloch](https://molo.ch) full packet capture, enhanced with [Suricata](https://suricata-ids.org/), listening on UDP port 4789 (VXLAN).
You can create a [VPC traffic mirroring target](https://docs.aws.amazon.com/vpc/latest/mirroring/traffic-mirroring-target.html) pointing at the ENI of this instance, create [filters](https://docs.aws.amazon.com/vpc/latest/mirroring/traffic-mirroring-filter.html) and [mirroring sessions](https://docs.aws.amazon.com/vpc/latest/mirroring/traffic-mirroring-session.html) to monitor traffic from your EC2 instances using a web interface.
