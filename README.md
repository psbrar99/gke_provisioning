# Terraform - Provision a GKE Cluster


1. Create google service account with editor role and download the json file and update in vpc.tf

2. Add the project and region in terraform.tfvars

3. Customize the gke.tf with attributes like machine-types , number of nodes and gke cluster name.


This sample repo also creates a VPC and subnet for the GKE cluster. This is not
required but highly recommended to keep your GKE cluster isolated.
