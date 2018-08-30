# tensorflow-labs

## For instructor

### AWS option 1

Recommend running with the `deeplearning` AMI, which is a fork of Amazon's DL AMI.

Start a new EC2 Instance as follows:
  * AWS us.east region
  * p2.xlarge instance type.
  * make sure network has public IP address
  * `deeplearning` AMI
  *  `hi.pem` key
  * `ubuntu` security group.

### AWS option 2

I used instances c4.4xlarge, at $0.80/hour, or $200/day for 10 students.

For more than 5 students, you may want 
to stop them after the class and restart in the morning.

The speed that you get with these is 2 times faster than my fast Mac.

