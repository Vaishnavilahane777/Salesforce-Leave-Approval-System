# Leave Request Approval System

## Project Overview
A Salesforce-based leave management system that allows employees to submit leave requests and managers to approve or reject them.

## Objectives
- Create and manage employee leave requests.
- Calculate leave duration automatically.
- Validate leave dates and required information.
- Automate manager approval and rejection.
- Monitor requests using Salesforce reports and dashboards.

## Technologies Used
- Salesforce Lightning Experience
- Custom Objects and Custom Fields
- Validation Rules
- Formula Fields
- Salesforce Approval Process
- Salesforce Flow Builder
- Reports and Dashboards
- Salesforce CLI and GitHub for metadata version control

## Main Features
1. Leave request creation and tracking.
2. Automatic calculation of calendar leave days.
3. Validation of incorrect date ranges.
4. Manager approval and rejection.
5. Automatic leave status updates.
6. Pending, approved, and rejected request reports.
7. Leave management dashboard.
8. Permission-based access configuration.

## Workflow
Employee creates a request → submits for approval → manager reviews → request is approved or rejected → status and reports are updated.

## Deployment
The Salesforce metadata is stored in the repository in Salesforce DX project format. Deployment requires an authorized target Salesforce org and any required metadata dependencies.

## Testing
Test request creation, date validation, leave-day calculation, approval submission, approval, rejection, report filters, and dashboard components.

## Limitations
The initial version calculates calendar days and does not automatically exclude weekends or public holidays. Advanced leave balances, holiday calendars, and multi-level approvals can be added in future versions.
