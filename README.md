# rlt_terraform_k8s_test


# What I have done:

1) Developed Terrafrom templates to create a kubernentes cluster in GCP with "private network" along with "monitoring and alerting". 
2) Built and pushed image into GCR
3) Fixed the issues in helm chart and deployed the helm chart into the kubernetes cluster. 
4) Exposed the application to outside world by modifying values.yaml file in charts directory.


# Instrcuctions :

1) Run the terraform scripts. Enter the region and project-id when prompted. Cluster will be created with private network along with monitoring and alerting. 
2) build an image and push it into GCR using commands specified in "docker commands to build and push" file. Specify your project-id while giving commands.
3) Deploy helm charts. Specify your project-id in the values.yaml file before deploying. You can create different environments(production and stage) in the same cluster while giving commands to deploy helm charts. 





