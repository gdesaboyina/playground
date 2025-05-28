
### parse csv package_approvers.csv

1. Run terraform local block to get these below details and output them if approvers contains only example.com and not null
```json
   {
     package_name = $package_name
     azgroup = $azgroup
     package_requestors = package_requestors
     manager_fallback_users = manager_fallback_users
     product_owner_users = product_owner_users
   }
```

### parse access_packages.yaml

2. Run terraform local block to get these below details and output them

```json
{
  subscription: $subscription
  package_name: $package_name
  package_group: $package_group
  package_description: $package_description
  package_approvers: $package_approvers
  
}

```

