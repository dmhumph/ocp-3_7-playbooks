# Installing OpenShift 3.7 on AWS

When setting up the instance you need to add the following tag to the infrastructure:
Key=kubernetes.io/cluster/37group
Value=37


When provisioning AWS resources I created to storage volumes.  One is for Rhel install and the second is for docker storage that is needed.
