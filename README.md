# AWS touchdown

## Story

You and your team will need a Linux server to upload a demo version of an application that you've been working on. Buying a server is not a reasonable option at this stage of development and a server is required for a couple of days only. This is the perfect opportunity to start your first server in the Cloud.

## What are you going to learn?

- What is AWS and how to sign up
- What is AWS Free Tier
- What is an EC2 instance
- What types of EC2 instances does AWS provide
- What is Amazon Machine Image (AMI)
- How to launch an EC2 instance with an AMI of your choice
- How to connect to an EC2 instance using SSH
- How to terminate an EC2 instance

## Tasks

1. Sign up for AWS Free Tier account.
    - Student has an account in AWS.

2. Launch a Linux server in AWS using the EC2 service.
    - An EC2 instance is successfully started.

3. Connect to your EC2 instance using SSH.
    - SSH connection is successfully established to the EC2 instance. 

4. Copy files to and from the EC2 instance securely using the `scp` command.
    - A local file is copied securely to the EC2 instance using the command `scp`.
    - A file from the EC2 instance is copied securely to the local machine using the command `scp`.

5. Terminate the EC2 instance
    - The EC2 instance is terminated.

6. [OPTIONAL] Launch another EC2 instance, this time use a different Linux distribution AMI.
    - EC2 instance running another Linux distribution was started.

## General requirements

None

## Hints

- Note that verification of your payment details when signing up for AWS can take some time
- Check what is covered by the `AWS Free Tier` if you want to avoid charges while testing
- Notice the different distributions available in the form of AMI images. Since `Ubuntu 18.04` is already familiar to us you may choose it for your first EC2 instance.
- Please don't forget to add an inbound rule that will allow you to connect to the instance via SSH in the `Configure Security Group` tab in the launch wizard.
- In the last step of the wizard you are asked to provide a key pair in case you have not already created one previously. Save your *.pem file to your local machine, this is the key to your EC2 instance, make sure you set the proper permissions for this file.
- Notice that each AMI has its own default user. For the `Ubuntu 18.04` AMI the user is `ubuntu`, required for establishing an SSH connection.
- Terminate your EC2 instances once you have finished working with them.

## Background materials

- <i class="far fa-exclamation"></i> [Cloud computing with AWS](https://aws.amazon.com/what-is-aws/)
- <i class="far fa-exclamation"></i> [AWS Free Tier](https://aws.amazon.com/free/)
- <i class="far fa-exclamation"></i> [What is Amazon EC2?](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
- <i class="far fa-exclamation"></i> [Setting up with Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/get-set-up-for-amazon-ec2.html)
- <i class="far fa-exclamation"></i> [Launching an instance using the Launch Instance Wizard](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/launching-instance.html)
- <i class="far fa-exclamation"></i> [General prerequisites for connecting to your instance](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/connection-prereqs.html)
- <i class="far fa-exclamation"></i> [Connecting to your Linux instance using SSH](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html)
- <i class="far fa-exclamation"></i> [How to upload/download files via SSH using an identity file and SCP](https://devimalplanet.com/how-to-upload-download-files-via-ssh-using-an-identity-file-and-scp)
