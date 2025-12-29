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

## Screenshots
- [OU structure in Active Directory](screenshots/L03-01_OU_Structure.png)
- [GPO created in Group Policy Management](screenshots/L03-02_GPO_List.png)
- [GPO linked to OU](screenshots/L03-03_GPO_Linked.png)
- [Client policy verification](screenshots/L03-04_gpresult.png)
- [View all screenshots](screenshots/)
