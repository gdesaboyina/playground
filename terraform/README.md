
1. parse csv package_approvers.csv

Run terraform local block to get these below details and output them if approvers contains only example.com and not null

   {
     package_name = $package_name
     azgroup = $azgroup
     package_requestors = package_requestors
     manager_fallback_users = manager_fallback_users
     product_owner_users = product_owner_users
   }


3. parse access_packages.yaml

Run terraform local block to get these below details and output them

{
  subscription: $subscription
  package_name: $package_name
  package_group: $package_group
  package_description: $package_description
  package_approvers: $package_approvers
  
}


