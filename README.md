# AWSEC2
Start and Stop AWS EC2 Instances from another always active Instance

Use it for server development / test / stage that should not always be running.

Install aws-cli into another EC2 instance that is always running 24 hours on 24, write a script like this ec2-start-stop.sh provided.
Put the script into cron (crontab -e) on this instance always active, for example using the cron.txt provided.
ATTENTION: always make a backup and test first using it!
