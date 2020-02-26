## cluster-resources Parkside enhancement notes

This directory accommodates cluster-wide resources that should not be loaded in each developer's namespace. 
The resources are loaded to the cluster via [terraform-modules](https://github.com/parkside-securities/terraform-modules/kubernetes-kafka) and [terraform-live](https://github.com/parkside-securities/terraform-live), and these yamls are not referred but defined in Terraform. 
