# terraform-iws-main
# terraform-iws-main
This module will call based on the type of source it will call to respetive module

# Module :
``
module "storage_example" {
source ="git::https://github.com/anjijava16/terraform-iws-modules.git?ref=azure-storage"
resource_group_name="welcomeone1234"
location="EAST US"
storage_account_name="storageiwspwelcome"
storage_container_name="welcome"

}

``
