# Contributing to Systema OS

Thank you for your interest in Systema OS. 

Before submitting any code, issues, or pull requests, please read these contributor guidelines carefully. Systema OS is a **proprietary commercial platform** architected and owned exclusively by **Sk. Mahtabul Islam**.

---

## 📜 1. Mandatory Contributor License Agreement (CLA)
All contributions require acceptance of the [Systema OS CLA](CLA.md):
- Any pull request, patch, or feature submission irrevocably transfers 100% of its intellectual property and copyright exclusively to **Sk. Mahtabul Islam**.
- No contribution can introduce GPL, AGPL, copyleft, or third-party proprietary dependencies without explicit written authorization.

## 🛡️ 2. Lowest Necessary GitHub Role Policy
To ensure strict security and prevent unauthorized modifications:
- External contributors are assigned **only the lowest necessary GitHub role**: **Read-Only / Triage**.
- Direct branch pushes (including `main`) are disabled for all external accounts.
- Code review, CI integrity checks, and manual approval from Sk. Mahtabul Islam are required before any code can be merged.

## 🚫 3. Strict Non-Modification & Non-Distribution Rules
- You may NOT modify, fork, distribute, or sell this software or any part of it without prior written consent from Sk. Mahtabul Islam.
- Pull requests that attempt to modify copyright notices, licenses, architectural provenance anchors (`src/lib/license-guard.ts`), or author attribution will be immediately rejected and closed.

## 🔐 4. Secret Protection & Zero-Leak Mandate
- NEVER commit API keys, `.env` files, database credentials, Clerk keys, or Stripe secrets.
- Always use the sanitized `.env.example` template for development reference.
- Any pull request containing hardcoded credentials will be immediately sanitized, closed, and reported.

---
**Questions & Contributions Contact:**  
Sk. Mahtabul Islam  
Email: alexd2d.01@gmail.com | thewatchtimestudio@gmail.com
