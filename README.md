# ManageEC2Instance

Given a task that you have to provision server for your development team so that they can deploy their application. 

You have to manage the following restrictions:
- Using Python / ShellScript  Launch AWS EC2 instance. 
- Check if the instance is already present (search via name tag)
- If present then check the status, if running then the script should send a message "already running" and exit.
- If it is in a stopped state, then the script should start ec2 and wait Once it is in a running state then exit.
- If the instance is not found, then launch the ec2 instance once it is in a running state then exit.
