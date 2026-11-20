# Software Installation Request – ServiceNow

## Project Details
**Name:** Nikitha Gurrala  
**Roll Number:** 23JK1A0566  
**Email:** 23jk1a0566@kitsguntur.ac.in
**Platform:** ServiceNow  
**Project:** An Employee Requests Installation of Licensed Software through the Service Catalog

## Project Overview
This project implements a ServiceNow Service Catalog process for employees to request licensed software installation. The request follows an approval workflow before a catalog task is created for fulfillment.

## Features
- Software Installation Request catalog item
- Five catalog variables: Software Name, Software Version, Installation Type, Business Justification, and Required By Date
- Automated approval using Flow Designer
- Conditional processing after approval
- Automatic catalog task creation
- Assignment of the catalog task to the Software group
- Business Rule named "Create Incident on License Issue"

## Workflow
Employee submits request → Approval requested → Request approved → Catalog task created → Software team handles installation

## Testing
- Tested the Software Installation Request Flow.
- Approval action completed successfully.
- Approved condition evaluated as True.
- Catalog task creation completed successfully.
- Flow test status: Completed.

## Project Files
- ServiceNow Update Set XML
- Flow_Test_Completed.png – Screenshot showing successful flow execution

## Note
The repository contains the ServiceNow configuration export and workflow testing evidence.
