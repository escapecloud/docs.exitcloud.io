# Exit Strategy

An **exit strategy** defines the **target scenario** that an organization is planning for when assessing cloud exit readiness.

exitcloud.io uses the selected exit strategy to frame analysis, risks, and recommendations based on a **realistic exit path**.  
It does not initiate or perform a migration — it evaluates readiness for a chosen strategy.

## Why exit strategy matters

The selected exit strategy influences:
- which risks are highlighted
- how dependencies are evaluated
- which alternative technologies are considered relevant
- how exit readiness and scores are interpreted

Selecting the right exit strategy ensures that assessment results align with **realistic planning assumptions**.

## Repatriation to On-Premises

This strategy assumes workloads would be **moved back to on-premises infrastructure**.

It focuses on:
- identifying services that are difficult to run outside the cloud
- highlighting dependencies on managed cloud services
- assessing operational and architectural constraints of self-hosting

This strategy is commonly used by:
- regulated organizations
- environments with strict data residency requirements
- organizations reducing dependency on public cloud providers

## Hybrid Cloud Adoption

This strategy assumes a **mixed target state**, where some workloads remain in the cloud while others are repatriated or relocated.

It focuses on:
- identifying which services can be decoupled from cloud-native dependencies
- assessing portability across environments
- highlighting operational complexity introduced by hybrid models

Hybrid Cloud Adoption is useful when:
- full repatriation is unrealistic
- only specific workloads must be moved
- gradual exit strategies are being considered

## Migration to Alternate Cloud

This strategy assumes workloads would be **migrated to a different cloud provider**.

It focuses on:
- identifying vendor-specific services that limit portability
- evaluating availability and maturity of alternative technologies
- assessing effort required to replace cloud-native services

This strategy is commonly used when:
- organizations want to reduce vendor lock-in
- multi-cloud strategies are being evaluated
- commercial or geopolitical risks drive diversification
