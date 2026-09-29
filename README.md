# Auto Ticket Classification using Flow Designer

## Milestone 1: Requirement Analysis & Preparation

### Activity 1: Business Use Case
- **Objective:** Classify IT tickets automatically based on the issue description without manual intervention.
- **Key Logic:** Configured choice logic between Category and Subcategory for incoming tickets.
- **Notification:** Sent automated email notifications to the caller upon ticket creation.
- **Outcome:** Ensured structured, standardized ticket information, improved ease of maintenance, and future scalability.

---

### Activity 2: Creation of New Update Set
- **Objective:** Track and export all configuration changes reliably.
- **Navigation:** System Update Sets -> Local Update Sets
- **Action:** Created a new Update Set for this project, set state to "In Progress", and made it the current active set before making configuration changes.

---

### Activity 3: Navigation Steps in Picture Form
- Documented and captured screenshot steps for:
  - Navigating to Flow Designer and System Update Sets.
  - Creating and verifying choice fields for Category and Subcategory.
  - Setting up trigger conditions for automated ticket routing and email notifications
  ---

## Milestone 3: Automation using Flow Designer & Email Notification

### Activity 1: Auto Classification using Flow Designer
- **Trigger:** Configured trigger condition for newly created ticket records.
- **Flow Logic:** Built automated flow conditions in Flow Designer to parse Short Description/Keywords and automatically assign Category and Subcategory.
- **Notification Action:** Added an Email Notification step to automatically notify the caller/assigned team upon ticket creation and classification.
- **Outcome:** Automated classification and notification workflow executed successfully without manual intervention.
----

## Milestone 4: Testing, Validation & Security

### Activity 1: Test Scenario 1
- **Description:** Verified automatic category assignment for network-related issue descriptions.
- **Expected Result:** Ticket automatically classified under Network Category and Subcategory.
- **Status:** Passed and Verified.

---

### Activity 2: Test Scenario 2
- **Description:** Tested dependent dropdown filtering between Category and Subcategory fields.
- **Expected Result:** Subcategory options dynamically update based on selected Category.
- **Status:** Passed and Verified.

---

### Activity 3: Test Scenario 3
- **Description:** Validated email notification trigger upon new ticket creation.
- **Expected Result:** Confirmation email automatically sent to the caller with classification details.
- **Status:** Passed and Verified.

---

## Milestone 5: Deployment & Conclusion

### Summary & Conclusion
- **Update Set Completed:** Marked project Update Set status as 'Complete' and exported XML.
- **Flow Designer Activated:** Flow trigger and actions successfully tested and activated in target environment.
- **Project Outcome:** Automated ticket classification workflow built using ServiceNow Flow Designer, reducing manual effort and improving routing accuracy.
-
