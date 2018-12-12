Have you been in a situation where you need a quick deploy for a test environment, but sadly, one or more of these things happen to you:

- You don't remember which AMI you used

- Did I install all necessary dependencies?

- Did I update my image?

If so, this JSON file in conjunction with Packer (https://www.packer.io/), will make sure you deploy an updated, consistent and fully equipped AMI Base Image, that is absolutely ready to deploy.

Bear in mind the file contains very general requirements, and it's based on CentOS 7 AWS Marketplace Image, which means you must authorize your account to use it prior to building.

In the Provisioners section, feel free to add, remove and customize according to your own needs.

If you have any questions, don't hesitate to contact me at https://www.linkedin.com/in/pdelpino/
