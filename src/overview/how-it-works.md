# How it works?

exitcloud.io provides a structured, end-to-end workflow for assessing cloud exit readiness without requiring intrusive access to your cloud environments.

The platform is designed to make cloud exit risks **visible, measurable, and repeatable**.

## High-level workflow

At a high level, exitcloud.io works as follows:

1. You create an assessment on the platform  
2. You define scope, exit strategy, and assessment type  
3. You provide read-only cloud credentials  
4. The assessment engine performs the analysis  
5. Results are stored, visualized, and reported in the platform  

The same workflow applies to both **one-time** and **continuous** assessments.

## Assessment creation

Assessments are created directly in the exitcloud.io platform.

When creating an assessment, you define:
- assessment name and optional description
- target cloud provider
- exit strategy
- assessment type (Basic or Standard)
- execution mode (one-time or continuous)

This ensures that each assessment is clearly scoped and repeatable.

## Secure credential handling

To perform an assessment, exitcloud.io requires **read-only access** to the selected cloud provider.

Credentials:
- are used only during assessment execution
- are not stored in the platform database
- are handled via an isolated secrets manager
- are protected with strict access controls and auditing

exitcloud.io never modifies cloud resources and never performs write operations.

## Assessment execution

Once an assessment is submitted:
- the assessment engine takes over execution automatically
- data is collected based on the selected scope and exit strategy
- progress and status are visible in the platform

For continuous assessments, execution is repeated automatically based on the selected schedule (daily, weekly, or monthly).

## Reports and insights

After execution, results become available in the platform.

Depending on the assessment type, exitcloud.io generates:
- resource inventory and dependency insights
- cost overviews and trends
- identified exit risks and constraints
- alternative technology mappings
- exit readiness and vendor lock-in scores (Standard assessments)

Results can be viewed online and, where applicable, downloaded as PDF reports.

## Designed for ongoing visibility

exitcloud.io is designed not only for one-time analysis, but also for **ongoing exit readiness tracking**.

Continuous assessments allow you to:
- monitor changes over time
- track risk evolution
- measure improvement or regression in readiness
- maintain an up-to-date view of exit feasibility

This turns cloud exit readiness from a one-off exercise into a **managed capability**.
