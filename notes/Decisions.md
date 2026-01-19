# Design Decisions

This document describes the main architectural and configuration decisions
taken while implementing this Google Cloud infrastructure using the
Google Cloud Console.

## Project Scope
- This project focuses on foundational Google Cloud infrastructure concepts.
- All resources were created and managed using the Google Cloud Console.
- Automation tools and Infrastructure as Code were intentionally excluded.

## Networking Decisions
- A default VPC network was used to focus on understanding core components.
- Firewall rules were reviewed and configured to allow required traffic.
- Private Google Access and Cloud NAT concepts were studied conceptually.

## Compute Engine Decisions
- A Compute Engine virtual machine was created using standard machine types.
- CPU and memory configurations were selected based on learning objectives.
- Persistent disks were used to understand storage options and performance.

## Storage Decisions
- A Cloud Storage bucket was created to explore object storage concepts.
- Bucket location and storage class were selected for cost and simplicity.

## Learning Outcome
- This project strengthened practical understanding of Google Cloud Console.
- Emphasis was placed on understanding architecture rather than automation.
