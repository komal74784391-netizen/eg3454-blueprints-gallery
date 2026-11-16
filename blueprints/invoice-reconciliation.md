---
blueprint_key: invoice-reconciliation
title: Invoice Reconciliation
status: published
domain: finance-ops
owner_team: Finance Automation
first_published: 2024-04-02
code_repo: https://github.com/komal74784391-netizen/eg3454-impl-invoice-reconciliation
---

# Invoice Reconciliation

## Overview

Matches supplier invoices to purchase orders and flags the residual differences to the accounts-payable queue every morning.

## How it works

- Tolerance bands are configurable per supplier and per currency.
- Partial receipts are matched against the remaining open quantity.
- Exceptions are routed with a full audit trail of the matching attempt.

## Ownership

Maintained by Finance Automation. Page content is generated from the blueprint repository.
