# Task 3: AI Automation Workflow

## Overview

For this task, I created an automated workflow using Zapier to streamline internship application processing.

The workflow automatically:

* Collects internship applications through Google Forms
* Stores applicant data in Google Sheets
* Sends a confirmation email to the applicant using Gmail

---

## Workflow

Google Form Submission

↓

Google Sheets (Store Response)

↓

Gmail (Send Confirmation Email)

---

## Tools Used

* Google Forms
* Google Sheets
* Gmail
* Zapier
* Draw.io

---

## Workflow Description

A Google Form was created to collect internship applications. The form included the following fields:

* Full Name
* Email Address
* Track Applied For
* Reason for Applying

Responses were automatically stored in a linked Google Sheet.

Using Zapier, a workflow was configured to monitor new form responses. Whenever a new response was received, Zapier triggered Gmail to send a personalized confirmation email to the applicant.

---

## Testing

The workflow was tested using three sample submissions.

Results:

| Test Case | Sheet Updated | Email Sent |
| --------- | ------------- | ---------- |
| Test 1    | Yes           | Yes        |
| Test 2    | Yes           | Yes        |
| Test 3    | Yes           | Yes        |

All tests were successful.

---

## Files Included

* Task3_Automation_Workflow.md
* workflow_flowchart.png
* screenshot_1_google_form.png
* screenshot_2_google_sheet.png
* screenshot_3_zapier_trigger.png
* screenshot_4_zapier_action.png
* screenshot_5_zap_live.png
* screenshot_6_email_received.png

---

## Conclusion

This project demonstrates how no-code automation tools can be used to automate repetitive tasks such as data collection and email communication. The workflow reduces manual effort and improves efficiency in handling internship applications.