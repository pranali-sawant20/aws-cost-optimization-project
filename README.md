aws-cost-optimization-project
Problem statement:There are some EBS volume Snapshots,by verifying the following cases detecting the stale EBS snapshot
case1:Just EC2 instance is deleted
case2:Both EC2 instance and snapshots are deleted in any of the case snapshots are useless, the snapshot make sense when the volume is attached to an instance
Architecture:
