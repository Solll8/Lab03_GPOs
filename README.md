# Lab 03 – Organizational Units and Group Policy

## Objective
Create Organizational Units (OUs) and apply Group Policy Objects (GPOs) to manage domain users and computers.

## Environment
- Windows Server 2022
- Windows 10 Pro
- Domain: solvexlab.local
- Group Policy Management Console (GPMC)

## Configuration
- Created Organizational Units for departments (HR, IT, Sales)
- Moved users and computers into appropriate OUs
- Created Group Policy Objects
- Linked GPOs to the correct OUs
- Configured basic policy settings
- Forced Group Policy updates

## Validation
- Verified OU structure in Active Directory Users and Computers
- Confirmed GPOs are linked to correct OUs
- Verified policy application using `gpresult`
- Confirmed settings applied on Windows 10 client

