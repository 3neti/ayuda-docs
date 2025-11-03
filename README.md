# Unified Digital Disbursement Framework (UDDF) Documentation

This repository contains the comprehensive documentation for the **Unified Digital Disbursement Framework (UDDF)**, a national infrastructure for transparent government payments.

## Program Overview

**Tagline:** *"Every Peso Accounted For. Every Citizen Empowered."*

UDDF is a national transparency initiative that unifies all government financial releases into a **single programmable disbursement infrastructure** powered by digital micro-vouchers — covering social aid, employee payments, contractor settlements, and more.

## Documentation Structure

- **Program Overview** - Vision, mission, and strategic rationale
- **Context** - Current challenges, opportunities, and national alignment
- **Program Objectives** - Strategic, operational, technical, and public impact goals
- **Technology** - Micro-voucher architecture, system design, and workflow
- **Governance** - Oversight framework and risk mitigation strategies
- **Program Benefits** - Value propositions for government, beneficiaries, and the economy
- **Implementation** - Pilot program design, case studies, and monitoring
- **Sustainability** - Scale-up strategy and communications plan
- **Next Steps** - Actionable roadmap for program deployment

## View Documentation

The documentation is hosted on ReadTheDocs at: [ayuda-docs.readthedocs.io](https://ayuda-docs.readthedocs.io)

## Local Development

To run the documentation locally:

```bash
pip install -r requirements.txt
mkdocs serve
```

Then visit http://localhost:8000

## Building

To build the static site:

```bash
mkdocs build
```

To generate the PDF version:

```bash
mkdocs build
```

The PDF will be available at `site/pdf/uddf_framework.pdf`

## About UDDF

The Unified Digital Disbursement Framework establishes a **single programmable disbursement infrastructure** for **all government payments** — from social aid (G2P) to employee payments (G2E), contractor settlements (G2B) to scholarships (G2F).

By integrating **x-Change voucher infrastructure** with Government Banks (LandBank, DBP), every government financial release becomes a **traceable digital token** that remains within the regulated perimeter while becoming fully auditable and programmable.

**Powered by x-Change voucher technology**  
Developed by 3neti R&D OPC

## Key Features

- Cryptographically unique voucher tokens
- Built-in expiry, value, and merchant category rules
- Immutable issuance and redemption records
- Open audit APIs for COA, DBM, BSP oversight
- Real-time dashboards and automated anomaly detection
