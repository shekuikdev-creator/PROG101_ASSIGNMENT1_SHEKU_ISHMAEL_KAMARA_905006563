# PROG101_ASSIGNMENT1_SHEKU_ISHMAEL_KAMARA_905006563
# Community Waste Collection and Reporting System 
**Project theme:** Designing Logical Solutions for Sierra Leone Community Challenges  
**Project location:** Wellington Upper Taylor Street, Loko Town, Freetown, Sierra Leone

## Project Overview

The Community Waste Collection and Reporting System is a proposed logical solution for improving how waste-related incidents are reported, prioritised and followed up within the selected community.

It is intended to support reports about issues such as illegal dumping, waste accumulation in public spaces and waste blocking gutters or drainage areas. Reports can be submitted by residents, visitors, passers-by and other community members.

## Problem and Community Benefit

Waste disposed of in gutters and public spaces can create untidy surroundings and may obstruct drainage, particularly during heavy rainfall. These conditions can affect households, shop owners, pedestrians, road users and visitors.

The proposed system provides a more organised way to report incidents, identify their severity, coordinate appropriate follow-up and keep a record of outcomes. This could help urgent cases receive attention first and make it easier to monitor recurring problem areas.

## Main Objectives

- Provide a structured way to report waste-related incidents.
- Check essential report details and identify possible duplicate reports.
- Classify incidents as High, Medium or Low severity.
- Arrange inspection when necessary.
- Coordinate authorised waste collection or refer cases to the relevant authority.
- Track reports until an outcome is recorded.

## Main Workflow

1. Receive a waste incident report.
2. Check that essential information is complete.
3. Check for an existing unresolved report for the same incident or location.
4. Generate a report reference and classify severity for a new report.
5. Forward the report to the community waste coordinator.
6. Arrange inspection where necessary.
7. Coordinate authorised collection or refer the incident to the relevant authority.
8. Record the outcome and update the report status.

## Functional Modules

- Incident Reporting
- Report Validation and Classification
- Inspection and Verification
- Waste Collection Coordination
- Report Monitoring

## Computational Thinking

The design applies decomposition, pattern recognition, abstraction and algorithmic thinking to organise the reporting and follow-up process into manageable steps.

## Sustainable Development Goals

- **SDG 11 – Sustainable Cities and Communities**, particularly Target 11.6.
- **SDG 12 – Responsible Consumption and Production**, particularly Target 12.5.

## Repository Contents

# Pseudocode – Community Waste Collection and Reporting System

```text
START

RECEIVE incident report

REPEAT
    COLLECT location, category, description, date/time
    ACCEPT photo and reporter contact (if provided)

    IF essential information is missing THEN
        REQUEST missing information
    END IF
UNTIL essential information is complete

IF an unresolved report exists for the same incident/location THEN
    LINK new submission to existing report
    SET status to "Linked to Existing Report"
    UPDATE existing record

ELSE
    GENERATE unique report reference
    CLASSIFY severity as High, Medium or Low
    FORWARD report to community waste coordinator

    IF incident is urgent THEN
        FLAG for prompt attention
    END IF

    COORDINATOR reviews report

    IF inspection is necessary THEN
        ASSIGN inspection team
        RECORD inspection findings

        IF incident is NOT confirmed THEN
            SET status to "Unverified / Referred for Further Review"
        ELSE
            ASSIGN authorised collection team
            OR REFER to relevant authority
        END IF

    ELSE
        ASSIGN authorised collection team
        OR REFER to relevant authority
    END IF

    IF status is NOT "Unverified / Referred for Further Review" THEN
        REPEAT
            RECORD collection outcome

            IF completion is NOT confirmed THEN
                KEEP report open
                ARRANGE follow-up or reinspection
            END IF
        UNTIL completion is confirmed

        SET status to "Resolved"
    END IF
END IF

SAVE report and final status

END
```


- `Flowchart_Part_1.png`, `Flowchart_Part_2.png`, `Flowchart_Part_3.png` – The student's flowchart, presented in consecutive sections.
  <img width="2036" height="1392" alt="Screenshot 2026-11-04 at 11 46 06 AM" src="https://github.com/user-attachments/assets/f787383f-2bd0-4e7f-a82a-f533cbee9ce6" />

<img width="2036" height="1430" alt="Screenshot 2026-11-04 at 11 46 50 AM" src="https://github.com/user-attachments/assets/117ba5dc-6ebb-42f6-8b7d-8a29720b78bb" />

<img width="2036" height="1430" alt="Screenshot 2026-11-04 at 11 47 55 AM" src="https://github.com/user-attachments/assets/224c58c9-4552-4fb7-a2a9-f7f0dd7c3922" />




## Project Contribution

Proper waste management contributes to cleaner surroundings, safer drainage, healthier communities and a better living environment. By making waste-related incidents easier to report, prioritise and follow up, this project aims to support a cleaner and more responsible Wellington community.
