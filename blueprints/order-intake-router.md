---
blueprint_key: order-intake-router
title: Order Intake Router
status: published
domain: revenue-ops
owner_team: Revenue Systems
first_published: 2024-03-18
code_repo: https://github.com/komal74784391-netizen/eg3454-impl-order-intake-router
---

# Order Intake Router

## Overview

Normalises inbound order payloads from the storefront, the partner portal and the field-sales app before they reach the ERP queue.

## How it works

- Payload schemas are validated against the order contract registry.
- Duplicate submissions are collapsed on the external order reference.
- Routing rules pick the ERP queue by region and order value.

## Ownership

Maintained by Revenue Systems. Page content is generated from the blueprint repository.
