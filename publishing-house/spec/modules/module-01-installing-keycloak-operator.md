# Module 01 — Installing the Keycloak Operator

## Brief Overview

This module gives tech sales staff hands-on experience deploying the Red Hat build of Keycloak operator on OpenShift Container Platform 4.21. Participants navigate to OperatorHub, locate and install the operator, and verify it is running successfully in their namespace. The goal is to equip sales staff to confidently walk customers through the Keycloak operator installation workflow using the OpenShift web console.

## Audience and Time

- **Target personas:** Tech sales staff — solution architects, technical account managers
- **Experience level:** Intermediate
- **Prerequisites for this module:** Basic OpenShift web console navigation skills; conceptual familiarity with Kubernetes operators
- **Estimated duration:** 30 min

## Learning Objectives

- Install the Red Hat build of Keycloak operator from OperatorHub on OpenShift 4.21
- Verify a successful operator deployment via the OpenShift web console

## Lab Structure

| Section | Title | Duration |
|---------|-------|----------|
| 1 | Navigate to OperatorHub | 5 min |
| 2 | Locate and Install the Keycloak Operator | 15 min |
| 3 | Verify the Operator Deployment | 10 min |

## Detailed Steps

1. Log in to the OpenShift web console for your assigned cluster.
2. In the left navigation, open **Operators** and click **OperatorHub**.
3. In the OperatorHub search field, search for `Keycloak`.
4. Locate the **Red Hat build of Keycloak** operator tile and click it.
5. Review the operator details, then click **Install**.
6. On the Install Operator form, accept the default installation mode and namespace settings, then click **Install**.
7. Wait for the operator installation to complete.
8. Navigate to **Operators > Installed Operators** to view the operator status.
9. Confirm that the Red Hat build of Keycloak operator shows a status of **Succeeded**.

## Key Takeaways

- OperatorHub is the centralized marketplace within the OpenShift web console for discovering and installing Kubernetes operators.
- The Red Hat build of Keycloak operator automates the lifecycle management of Keycloak instances on OpenShift.
- Operator installation status is visible in the **Installed Operators** view; a status of "Succeeded" confirms a healthy deployment.

## Infrastructure Notes

Infrastructure details (cloud provider, cluster type, OCP version, topology, sizing) are TBD and will be confirmed in the infrastructure phase. No automated validation is required — this module uses a trust-based assessment where participants visually confirm the "Succeeded" operator status in the OpenShift web console.
