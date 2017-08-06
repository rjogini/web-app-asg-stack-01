# web-app-asg-stack-01
Stack Name: "web-app-asg-stack-01"

Create two AutoScale Groups (named: "web-asg" and "app-asg") in the Default VPC of "us-east-1" region
Properties for each ASG: Minimum Size: 1, Maximum Size: 3, Desired Size: 1

The instances in "app-asg" should only be accessible by instances in "web-asg"
