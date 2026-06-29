# Google Forms Trigger

## Objective

Connect the Google Form to Make.com so that every new form submission automatically starts the **SEO Content Strategist AI Agent** workflow.

---

## Purpose

The Google Forms trigger serves as the entry point of the automation. Whenever a user submits the form, Make.com automatically retrieves all submitted fields and passes them to the workflow for further processing.

---

## Workflow Position

```text
Google Form
      │
      ▼
Google Forms → Watch Responses
      │
      ▼
Input Validation
```

---

## Make.com Module

**Module:**  
Google Forms → **Watch Responses**

---

## Expected Input

The module should receive the following fields from the Google Form:

- Blog Topic
- Primary Keyword
- Target Audience
- Business Type
- Writing Tone
- Word Count
- Language
- Additional Instructions

---

## Expected Output

The trigger should expose all submitted form fields as variables that can be accessed and used by downstream AI agents throughout the workflow.

---

## Success Criteria

- Google account connected
- Google Form selected
- Trigger runs successfully
- Test submission detected
- All eight fields retrieved successfully