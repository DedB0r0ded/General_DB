# MySQL scripts for client-server project
Contains the following directories:
- [functions](#functions)
- [grant](#grant)
- [procedures](#procedures)
- [tables](#tables)
- [triggers](triggers)
- [users](#users)

## Functions
## Grant
## Procedures
Contains CREATE statements for all MySQL procedures used in database.

## Tables
Contains CREATE statements for all database tables.  
There are 19 tables currently in the project.  
Foreign and primary keys are described using constraints.

> [!WARNING]
> Tables must be created in the following order:
> 1. `user `
> 2. `task`
> 3. `bank`
> 4. `organisation`
> 5. `reg_key`
> 6. `reg_key_privileges`
> 7. `report`
> 8. `manufacturer_code`
> 9. `manufacturer`
> 10. `g_facility`
> 11. `g_component`
> 12. `g_item`
> 13. `g_service`
> 14. `organisation_service`
> 15. `date_info`
> 16. `contract`
> 17. `contract_service`
> 18. `contract_mnt_item`
> 19. `review`

## Triggers
## Users