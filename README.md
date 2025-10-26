# terraform-build-infra-on-gcp

# Add Google Cloud provider in main.tf syntax
,,,
terraform {
  required_providers {
    google = {
      source = "hashicorp/google"
    }
  }
}

provider "google" {

  project = "Project ID"
  region  = "Region"
  zone    = "Zone"
}
,,,
