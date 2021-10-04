# terraform-iws-main
# terraform-iws-main
This module will call based on the type of source it will call to respetive module

# Module :

## Branch Name:
    https://github.com/anjijava16/terraform-iws-modules.git?ref=azure-storage

## Example 

module "storage_example" {

source ="git::https://github.com/anjijava16/terraform-iws-modules.git?ref=azure-storage"

resource_group_name="welcomeone1234"

location="EAST US"

storage_account_name="storageiwspwelcome"

storage_container_name="welcome"

}

# Module Source Types 8
1. Local paths
2. Terraform Registry
3. GitHub
4. Bitbucket
5. Generic Git, Mercurial repositories
6. HTTP URLs
8. S3 buckets
9. GCS buckets

# Generic Github Repo Example

module "vpc" {
source = "git::https://example.com/vpc.git"
}

module "storage" {
source = "git::ssh://username@example.com/storage.git"
}

module "vpc" {
source = "git::https://example.com/vpc.git?ref=v1.2.0"
}


