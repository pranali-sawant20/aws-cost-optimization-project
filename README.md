aws-cost-optimization-project

Problem statement:There are some EBS volume Snapshots,by verifying the following cases detecting the stale EBS snapshot
case1:Just EC2 instance is deleted
case2:Both EC2 instance and snapshots are deleted in any of the case snapshots are useless, the snapshot make sense when the volume is attached to an instance

Architecture:
![image-alt](https://github.com/pranali-sawant20/aws-cost-optimization-project/blob/dc6f023b9d43ac31d73a3ed253fec4f65ad3c9ad/architecutre-cost-optimization.png)

Output:
![image-alt](https://github.com/pranali-sawant20/aws-cost-optimization-project/blob/15234f756ce5c8f0708382062e63dd53d1e36b3e/cost-optimization-output.png)
