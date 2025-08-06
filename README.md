Delving into the financial operations aspect of cloud computing 


Jenkins Cost Optimization

Server costs will rocket when jenkins utilizes a lot of space for storing builds and logs 
So ideally, a cronjob could be set to loop through the logs daily and back it up to an S3 bucket whiles freeing server space on the jenkins.

Refer to the jenkins-cost.sh commit to fully understand the tasks of the cron job 
