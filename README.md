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
> Tables CREATE statements must be run in the following order:
> - user 
> - task
> - bank
> - organisation
> - reg_key
> - reg_key_privileges
> - report
> - manufacturer_code
> - manufacturer
> - g_facility
> - g_component
> - g_item
> - g_service
> - organisation_service
> - date_info
> - contract
> - contract_service
> - contract_mnt_item
> - review

## Triggers
## Users