# Scaling
### We scale so that we can provide an adequate service at any time for our users, if more show up we can be flexable.
## images
![Alt text](image.png)
![Alt text](image-1.png)
## setting it up
# We first need to name the SG and give it a template to use
![Alt text](image-11.png)
# We then need to specify the subnets each of the VM's will be using, for availability purposes.
![Alt text](image-12.png)
# We will then need to set up a load balancer, since the LB is accessing external internet traffic it need to accept http requests and needs to be set up that way
![Alt text](image-13.png)
![Alt text](image-14.png)
# we then need to configure how the scaling will act, setting minimum desired and maximum amount of vm's htat can be deployed. We will also define how they act when they need to increase or decrease VM's, or rather when a Vm is unhealthy.
![Alt text](image-15.png)
![Alt text](image-16.png)
# we can then verify it is running and can use the LD DNS name to access the VM's and use its features.
![Alt text](image-17.png)
![Alt text](image-18.png)
# To get rid of it first delete the LD then target group then the sg at the end, the sg can only be delayed from the group view menu