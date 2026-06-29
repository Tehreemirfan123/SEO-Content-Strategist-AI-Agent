# Google Form Setup

## Objective

The Google Form serves as the entry point for the SEO Content Strategist AI Agent workflow. It collects the required information from the user and triggers the Make.com automation whenever a new response is submitted.

---

## Purpose

The form standardizes user input before it enters the workflow. Every submission contains all the information required by the AI agents to generate an SEO content strategy.

---

## Workflow Position

```text
User
   │
   ▼
Google Form
   │
   ▼
Make.com Trigger
```

---

## User Inputs

| Field                   | Type         | Required |
| ----------------------- | ------------ | :------: |
| Blog Topic              | Short Answer |    Yes    |
| Primary Keyword         | Short Answer |    Yes    |
| Target Audience         | Dropdown     |    Yes    |
| Business Type           | Dropdown     |    Yes    |
| Writing Tone            | Dropdown     |    Yes    |
| Word Count              | Dropdown     |    Yes    |
| Language                | Dropdown     |    Yes    |
| Additional Instructions | Paragraph    |    No     |

---

## Target Audience Options

* Beginners
* Intermediate
* Professionals
* Business Owners
* Students
* General Audience

---

## Business Type Options

* Technology
* Healthcare
* Education
* Finance
* E-commerce
* Marketing
* Construction
* Real Estate
* Travel
* Food & Beverage
* Other

---

## Writing Tone Options

* Professional
* Conversational
* Informative
* Persuasive
* Friendly
* Technical

---

## Word Count Options

* 500
* 1000
* 1500
* 2000
* 2500

---

## Language Options

* English
* Urdu

---

## Expected Output

Each Google Form submission creates a new response that is detected by Make.com, initiating the SEO Content Strategist AI workflow.

