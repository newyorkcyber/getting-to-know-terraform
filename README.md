# getting-to-know-terraform
Terraform notes &amp; information 

# TERRAFORM CONFIGURARION #1 TO PROVISION A GKE CLUSTER (NOT TESTED)

resource "google_container_cluster" "new_york_cyber_codeless_gke_cluster" {
 
  addons_config = 
  cluster_autoscaling=
  cluster_ipv4_cidr = 
  description = "new_york_cyber_codeless_gke_worldwide_cluster"
  enable_binary_authorization =
  enable_legacy_abac =
  enable_kubernetes_alpha =
  enable_tpu =
  additional_config =
  additional_zones = "us-west2-b"
  initial_node_count =
  ip_allocation_policy =
  logging_service =
  maintenance_policy =
  master_auth =
  master_authorized_networks_config =
  min_master_version =
  monitoring_service =
  name = "new_york_cyber_codeless"
  network =
  network_policy =
  node_config =
  node_pool =
  node version =
  pod_security_policy_config =
  private_cluster_config =
  project = "new_york_cyber_codeless_p1"
  remove_default_node_pool =
  region = "us-west2"
  resource_labels =
  subnetwork =
  zone = "us-west2-a"
  
  # TERRAFORM DOCUMENTATION REFERENCE 
  # https://www.terraform.io/docs/providers/google/r/container_cluster.html
  

}
