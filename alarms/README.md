# Alarms and notifications
## We followed this tutorial
#https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/US_AlarmAtThresholdEC2.html
first we create a vm and set up per minute monitoring
we need to link EC2 and per instance monitoring,
make the alarms update per minute also,
set up the threshold to an appropriate percentage,
to notify you need to create a notification and link you account email,
set it to static and average.
![Alt text](image-4.png)
![Alt text](image.png)
![Alt text](image-1.png)
![Alt text](image-2.png)
![Alt text](image-3.png)
# have to wait to gather data
![Alt text](image-5.png)
# got an alarm
![Alt text](image-6.png)
![Alt text](image-7.png)
## Do not rename the matric as for some reason it does not work