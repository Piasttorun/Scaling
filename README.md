# Scaling
## images
![Alt text](image.png)
![Alt text](image-1.png)
## setting it up
# We first need to name the SG and give it a template to use
![Alt text](image-11.png)
# We then need to specify the subnets each of the VM's will be using, for avaialability purposes.
![Alt text](image-12.png)
# We will then need to set up a load balancer, since hte ld is accessign external internet traffic it need to accept http reqquests and needs to be set up that way
![Alt text](image-13.png)
![Alt text](image-14.png)
# we then need to configure how the sclaing will act, settign minimum dsesired and maximum amount of vm's htat can be deployed. We will aslo define how they act when they need to increaese or decrease VM's, or rather when a Vm is unhealthy.
![Alt text](image-15.png)
![Alt text](image-16.png)
# we can then verify it is running and can use the LD DNS name to access the VM's and use its features.
![Alt text](image-17.png)
![Alt text](image-18.png)