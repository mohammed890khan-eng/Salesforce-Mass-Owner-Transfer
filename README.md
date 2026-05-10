# Salesforce Mass Owner Transfer

## Project Overview
This project replicates Salesforce's standard "Change Owner" functionality for a custom object setup using Apex and Visualforce.

The solution automatically transfers ownership from parent records (Relationship object) to related child records (Financial Account object), ensuring synchronized ownership updates across related data.

---

## Features Implemented
- Mass record owner transfer
- Parent-child relationship handling
- Bulk record processing
- Visualforce custom interface
- Apex Controller Extension
- Automated email notifications
- Record update optimization using Lists
- Governor Limits best practices

---

## Technologies Used
- Salesforce Apex
- Visualforce
- SOQL
- Apex Email Services
- Salesforce CRM
- VS Code
- GitHub

---

## Project Workflow
1. User selects multiple parent records
2. Visualforce page opens Mass Edit screen
3. Apex Controller processes selected records
4. Related child records are identified
5. Owner fields are updated in bulk
6. New owner receives email notification with record links

---

## Key Learning Outcomes
Through this project, I learned:
- Bulkification in Apex
- Governor Limits handling
- Parent-child data relationships
- Custom Salesforce UI using Visualforce
- Efficient record updates using Lists
- Apex Controller Extensions
- Email automation using Apex

---

## Why Apex Instead of Flow?
This project was intentionally built using Apex and Visualforce to demonstrate Salesforce development skills and backend logic implementation. While similar functionality could be implemented using Flow in Lightning Experience, this project focuses on coding concepts and scalable bulk processing.

---

## Author
Mohammed Javeed

LinkedIn:
https://linkedin.com/in/mohammed-javeed-280692278

GitHub:
https://github.com/mohammed890khan-eng
