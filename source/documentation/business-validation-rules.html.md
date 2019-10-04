---
title: Business Validation Rules (BVRs) | Income Tax (MTD) End-to-End Service Guide
weight: 25
---

# Business and Agent end-to-end user journey

## 
<!--- Section owner: MTD Programme --->Business Validation Rules (BVRs)

Business Validation Rules (BVRs) are data integrity or data quality checks applied to business information content submitted by third-party applications via the MTD Software APIs.
These are rules that contain a formula or expression that evaluates the data in one or more predetermined business fields and returns a value of ‘True’ or ‘False’.
They are distinct from technical validation rules which check syntax, structure and data types to prevent corrupt, incomplete or badly formed data entering HMRC systems.
BVRs ensure that customer-supplied information is self-consistent, meaningful, within expected bounds and as complete as it needs to be.

If customer-supplied information violates a BVR it may result in an error or a warning. One or more errors will result in the failure of the associated API call and rejection of all the data content (as would any technical validation rule failure).
Warnings will typically require the customer to take remedial action at a later point to avoid potential errors in future.

HMRC may also advise software vendors to provide vendor only warnings, these are similar to nudges and prompts that would normally be delivered by HMRC service for a taxpayer. These should enhance the customers journey and increase accuracy of the submissions before they have been sent to HMRC – but will not be checked by HMRC’s back end systems at the same time.
