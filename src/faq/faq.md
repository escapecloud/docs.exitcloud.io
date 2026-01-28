# Frequently Asked Questions

This section answers common questions about exitcloud.io, cloud exit readiness assessments, and how the platform works.

---

## What is cloud exit readiness?

Cloud exit readiness describes how prepared an organization is to **reduce, change, or fully exit** a cloud service provider.

It covers:
- technical dependencies
- service lock-in risks
- cost and operational considerations
- availability of alternative technologies

exitcloud.io helps assess and quantify this readiness in a structured way.

---

## Who is exitcloud.io for?

exitcloud.io is designed for:
- small and medium-sized enterprises (SMEs)
- managed service providers (MSPs)
- consultants supporting cloud strategy and risk assessments
- technical leaders who need visibility into exit risks

---

## Which cloud providers are supported?

Currently supported:
- **AWS**
- **Microsoft Azure**

Planned / coming soon:
- Google Cloud Platform (GCP)
- Alibaba Cloud

Support for additional providers will be added over time.

---

## Does exitcloud.io require admin access to my cloud account?

No.

exitcloud.io requires **read-only permissions** only.  
These permissions are used exclusively to collect metadata such as:
- resource types
- counts
- cost summaries

No changes are made to your cloud environment.

---

## How are credentials handled?

- Credentials are used only during assessment execution
- They are **not stored in the platform database**
- They are securely handled via an **isolated secrets manager**
- Full auditing and strict access controls are applied

exitcloud.io never stores long-term credentials in plaintext.

---

## What is the difference between Basic and Standard assessments?

**Basic** includes:
- Resource Inventory
- Cost Overview
- Risk Inventory
- Executive Summary

**Standard** includes everything in Basic, plus:
- Exit Readiness Scoring
- Detailed Exit Readiness Report
- Benchmarking and trend analysis (for continuous assessments)

---

## What is a continuous assessment?

A continuous assessment automatically re-runs on a schedule:
- daily
- weekly
- monthly

This allows you to:
- track changes over time
- monitor risk evolution
- measure improvement or regression in readiness

---

## Can I export or download reports?

Yes.

Depending on the assessment package, you can download:
- **Executive Summary** (Basic & Standard)
- **Exit Readiness Report** (Standard only)

Reports are available as PDF files via the **Download** button on the Assessment Details page.

---

## Can I change my data region later?

No.

EU and US regions are **fully isolated**, and accounts or assessments cannot be migrated between regions.

Choose your data region carefully based on legal, regulatory, and contractual requirements.

---

## Is exitcloud.io vendor-neutral?

Yes.

exitcloud.io is:
- cloud-provider agnostic
- vendor-neutral
- focused on outcomes, not tooling promotion

Alternative technologies are presented for analysis, not endorsement.
