# tf-neal-davis-sap-udemy-hol-labs

## Setup 

- Create aws root account
- From root account
    - Create an `Admins` group that allows `AdministratorAccess`
    - Create an `IAM` user and and add it to the `Admins` group
- Login to the newly created user, all terraform commands will be run from this `IAM` user, not the root account
