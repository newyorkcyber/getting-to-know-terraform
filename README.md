# getting-to-know-terraform
Terraform notes &amp; information 

# TERRAFORM CONFIGURARION #1 TO PROVISION A GKE CLUSTER (1.13/ALPHA)

resource "google_container_cluster" "new_york_cyber_codeless_gke_cluster" {
 
  # addons_config =
  # cluster_autoscaling =
  # cluster_ipv4_cidr =
  description = "new_york_cyber_codeless_gke_worldwide_cluster"
  enable_binary_authorization =
  enable_legacy_abac = "false"
  enable_kubernetes_alpha = "true"
  enable_tpu = "false"
  additional_config =
  # additional_zones = "us-west2-b"
  initial_node_count = "3"
  ip_allocation_policy =
  logging_service =
  maintenance_policy =
  master_auth =
  master_authorized_networks_config =
  min_master_version = "1.13"
  monitoring_service = "monitoring.googleapis.com/kubernetes"
  name = "new_york_cyber_codeless"
  # network =
  # network_policy =
  node_config =
  node_pool =
  node version = "1.13"
  pod_security_policy_config =
  private_cluster_config =
  project = "new_york_cyber_codeless_p1"
  remove_default_node_pool =
  region = "us-west2"
  resource_labels = 
  subnetwork =
  # zone = "us-west2-a"
  
  # TERRAFORM DOCUMENTATION REFERENCE 
  # https://www.terraform.io/docs/providers/google/r/container_cluster.html
  

}

# ----------

# Terraform module start

module "" {

# examples
# main.tf
# modules 
# outputs.tf
# README.md
# variables.tf
  # NESTED_OMEGA
    # main.tf
    # outputs.tf
    # variables.tf

source = ""


# ----------

data "google_container_registry_repository" "new_york_cyber_codeless_gke_registry" {
  
  # project =
  region = europe-west2
  
  
}



# Reference documentation
# 1.000 - https://cloud.google.com/compute/docs/regions-zones/
# 1.00 - https://www.terraform.io/docs/providers/google/d/google_container_registry_repository.html
# 1.0 - https://www.terraform.io/docs/index.html
# 1.1 - https://www.terraform.io/docs/configuration/modules.html (Terraform module reference documentation)
# 1.2 - https://registry.terraform.io/ (Terraform registry URL)
# 1.3 - https://registry.terraform.io/sign-in (actually register a Terraform module)

}
