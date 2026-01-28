# First Assessment

This guide walks you through creating and running your first cloud exit readiness assessment on exitcloud.io.

Assessments are created through a guided, multi-step workflow in the platform.

## Step 1: Add assessment details

Start by creating a new assessment and defining its basic parameters:

- **Assessment name**  
  A human-readable name to identify the assessment.

- **Exit strategy**  
  Select the exit scenario you want to evaluate, for example:
  - Repatriation to On-Premises
  - Hybrid Cloud Adoption
  - Migration to Alternate Cloud

- **Sync frequency**
  - **Single (one-time assessment)**  
    Runs the assessment once and generates a point-in-time report.
  - **Continuous assessment**  
    Runs the assessment automatically on a defined schedule.

- **Sync interval** (only for continuous assessments)
  - Daily
  - Weekly
  - Monthly

- **Description (optional)**  
  Add context or internal notes about the assessment.

## Step 2: Configure cloud provider

Next, select the cloud service provider you want to assess:

- Microsoft Azure
- AWS
- GCP *(coming soon)*
- Alibaba Cloud *(coming soon)*

You will then provide **read-only credentials** for the selected provider.

**Credential handling**

- Credentials are used **only** to collect cloud metadata
- Read-only permissions are required
- Credentials are **not stored in the platform database**
- They are securely handled via an isolated secrets manager with auditing

The platform validates credentials and permissions before allowing you to proceed.

## Step 3: Select package

Choose the assessment package that defines the scope and outputs:

**Basic**
- Resource Inventory
- Cost Inventory
- Risk Assessment
- Summary Report

**Standard**
- Everything in Basic
- Exit Readiness Score
- Detailed Report

> Package selection determines **credit usage** and available reports.

## Step 4: Run assessment

Once submitted:

- The assessment engine schedules the run automatically
- Progress is tracked in the platform
- Status updates are shown during execution
- An email notification is sent when the assessment completes

For continuous assessments, the engine will re-run automatically based on the selected schedule.

## Results

After a successful run, you can:

- View results directly in the platform
- Download generated reports (depending on package)
- Track changes over time for continuous assessments

Your first assessment provides a structured baseline for understanding **cloud exit readiness** and identifying key risks and dependencies.
