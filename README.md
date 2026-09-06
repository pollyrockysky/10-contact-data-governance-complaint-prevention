# Contact Data Governance & Complaint Prevention
## Preventing Complaint Risk Through Better Contact Data Design

> Ensuring customer contact information is not only collected correctly, but also used appropriately across downstream systems and processes.

**Case Study | 2022**

**Customer Experience · Product Improvement · Data Governance · Complaint Prevention · Downstream System Thinking**

---

## Executive Summary

During a digital lending journey, customers could provide both:

- A personal contact number
- A company or workplace telephone number

These two fields served different purposes.

However, the workplace telephone number could be passed into a downstream core banking system as customer contact information.

This created a risk that a number originally provided as workplace information could later be used for customer communication, including debt-collection activities.

The core product question became:

> **Just because a piece of customer data exists, does that mean it should be used for every downstream purpose?**

My objective was to make the purpose of each telephone field clearer and ensure that customer contact data was used appropriately throughout the lending lifecycle.

---

## The Problem

A personal contact number and a workplace telephone number are not equivalent.

A workplace number could belong to:

- An office
- A company reception desk
- A shared business line
- Another person within the customer's organization

It should therefore not automatically become the customer's preferred personal contact channel.

If that number were transferred downstream as a general contact number, it could later be used inappropriately.

In a lending environment, this could create:

- Poor customer experience
- Inappropriate customer contact
- Complaint risk
- Additional risk during collection activities

The issue was therefore not simply:

> “Do we have a telephone number?”

The more important question was:

> **“Why was this number provided, and is it appropriate to use it for customer contact?”**

---

## My Approach

I looked at the issue across the full customer journey rather than only at the application screen.

The key design principle was to clearly distinguish:

**Personal Contact Number**

from

**Company / Workplace Telephone Number**

and ensure that downstream systems preserved that distinction.

The intended usage became:

### Personal Contact Number

Used as the appropriate customer contact channel.

### Company / Workplace Telephone Number

Retained as workplace information and not automatically converted into a general customer contact number.

---

## The Product Decision

The decision was to change the data flow.

The **Company / Workplace Telephone Number** would no longer be passed into the downstream core banking system as the customer's contact number.

Instead, the customer's personal number would be used for the appropriate contact purpose.

The objective was not to remove useful information.

It was to ensure:

> **Each data field is used according to the purpose for which it was collected.**

---

## From Data Collection to Data Governance

The design principle became:

**Collect the Data**

↓

**Understand Its Purpose**

↓

**Control How It Is Used**

↓

**Preserve Meaning Downstream**

rather than:

**Data Exists**

↓

**Send It Everywhere**

↓

**Let Downstream Processes Decide How to Use It**

This shifted the problem from a simple field-mapping issue into a **data-governance decision**.

---

## Downstream System Thinking

The application screen itself was not the real boundary of the problem.

The risk appeared later in the customer lifecycle.

A field could be technically valid in one system but inappropriate for a different downstream purpose.

I therefore considered:

- Why the data was originally collected
- Where the data would be transferred
- How downstream systems might interpret it
- What customer impact could occur later
- Whether the original semantic meaning of the field would be preserved

This required thinking beyond the immediate user interface and into the full data lifecycle.

---

## Solution

The system requirement was updated so that:

### Personal Contact Number

**→ Could be used as customer contact information**

while

### Company / Workplace Telephone Number

**→ Would not be passed downstream as the customer's contact number**

This reduced the possibility that workplace information could later be used unintentionally for:

- Customer communication
- Collection activities
- Other contact-related processes

---

## Outcome

The change was successfully implemented.

It created a clearer separation between personal and workplace contact information.

The improvement also addressed the issue at the **data-flow level**, rather than depending on downstream teams to interpret the field correctly later.

This helped reduce:

- Inappropriate customer contact risk
- Complaint risk
- Ambiguity in downstream data usage

and created a more consistent customer experience across the lending lifecycle.

---

## Why This Design Was Stronger

A weaker solution could have been:

> “Tell the downstream team not to use the workplace number.”

But that would depend on human interpretation every time.

Instead, the design prevented the inappropriate data usage earlier in the flow.

The principle was:

> **If a downstream misuse can be prevented through product and data design, do not rely only on downstream operational discipline.**

---

## Product Leadership Lessons

This case reinforced an important product principle:

> **Customer data should not only be collected correctly — it must also be used correctly throughout its lifecycle.**

A field can be technically valid while still being inappropriate for a specific downstream use.

When designing product and system flows, I therefore consider not only:

> “What data do we have?”

but also:

> **“Why was it collected, where will it go, and how could it be used later?”**

This becomes increasingly important when customer information moves across multiple systems and operating processes.

---

## What This Case Demonstrates

This case demonstrates experience across:

- **Data Governance**
- **Customer Experience**
- **Complaint Prevention**
- **Digital Lending**
- **Customer Data Design**
- **Downstream System Thinking**
- **Product Risk Management**
- **Data Flow Design**
- **System Requirements**
- **Customer Protection**
- **Cross-System Product Thinking**
- **End-to-End Product Ownership**

---

*This portfolio case study has been simplified and sanitized for public presentation. Confidential customer information, internal field names, system identifiers, proprietary data mappings and sensitive operational details have been omitted.*
