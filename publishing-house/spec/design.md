# Installing the Keycloak Operator on OpenShift

<!-- This file is the design document for your lab or demo. -->
<!-- Fill in each section below, or run /rhdp-publishing-house to have the intake skill help. -->
<!-- Sections marked with [brackets] are placeholders — replace with real content. -->
<!-- The validation gate checks for all required sections before submission. -->

## Overview

This lab gives tech sales staff hands-on experience deploying the Keycloak operator on Red Hat OpenShift Container Platform 4.21. It exists to help sales staff confidently demonstrate the Keycloak operator installation workflow to customers. Participants will navigate to OperatorHub, install the Red Hat build of Keycloak operator, and verify that the operator is running successfully in their namespace.

## Target Audience

- **Role:** Tech sales staff (solution architects, technical account managers)
- **Experience level:** Intermediate
- **What they already know:** Basic OpenShift web console navigation; conceptual familiarity with Kubernetes operators
- **What they don't know:** How to locate, install, and verify the Keycloak operator on OCP via OperatorHub

## Prerequisites

- Basic OpenShift web console navigation skills
- No automated validation — trust-based

## Learning Objectives

1. Install the Red Hat build of Keycloak operator from OperatorHub on OpenShift 4.21
2. Verify a successful operator deployment via the OpenShift web console

## Content Type

Lab (hands-on)

## Products & Technologies

- Red Hat OpenShift Container Platform 4.21
- Red Hat build of Keycloak

## Module Map

| Module | Title | Duration |
|--------|-------|----------|
| 1 | Installing the Keycloak Operator | 30 min |
| — | **Total hands-on** | **30 min** |
| — | Intro / presentation | ~5 min |
| — | **Total lab** | **~35 min** |

## Difficulty Level

Intermediate

## Environment

**Learner view:** Participants receive access to a shared OpenShift 4.21 multinode cluster via the OpenShift web console. The cluster is pre-provisioned with standard operators and authentication configured. Participants work within their own namespace to install and verify the Keycloak operator.

**Automation needed:** Yes — cluster provisioning, namespace setup, and user authentication must be automated before the lab starts.

## Infrastructure Requirements

- **Cloud provider:** CNV
- **Cluster type:** Multinode
- **OCP version:** 4.21
- **Topology:** Shared cluster (max 30 concurrent users)
- **Sizing:** 3 control plane (16 vCPU, 64GB RAM), 2 workers (8 vCPU, 32GB RAM, 100GB disk)
- **Automation approach:** Ansible
- **AI/MaaS:** None
- **External services:** registry.redhat.io, quay.io
- **AAP version:** N/A
- **Non-GA products:** None (all products are GA)

## Assessment Strategy (Optional)

Trust-based — no automated verification. Participants confirm successful operator installation visually via the OpenShift web console (operator status shows "Succeeded").
