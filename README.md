Hello Everyone,

I am excited to share my latest project!

I successfully deployed a Kubernetes project utilizing an EKS cluster in AWS. Through this project, I gained an understanding of the process of deploying applications using EKS with Fargate and accessing the application through the load balancer in a secure way.

Pre-requisites:

Kubectl, eksctl, awscli

Process:

1) Install EKS with Fargate and update the kubeconfig file.

2) Deploy the application in the form of a pod.

3) Create a service and ingress.

4) Create an IAM OIDC (OpenID Connect) provider to access the application load balancer.

5) Create an IAM policy and role to access the load balancer.

6) Create Helm charts to interact with the load balancer.

7) Once it is done, we will be able to see the URL of the application in the load balancer.

8) Access the application through the URL.



Special thanks to Abhishek Veeramalla this amazing project. 😊 
