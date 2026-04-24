# Contributing to PROJECT-COD

Thank you for contributing to this co-op portfolio documentation! Please follow these guidelines to maintain professionalism and protect confidential information.

## Confidentiality Guidelines

### ⚠️ CRITICAL: Before committing any files

This repository is a **public portfolio** that will be shared with future employers. **Protect client confidentiality** at all times:

### Items to REDACT or REMOVE:

**Client Information:**
- [ ] Client company names → Replace with "[CLIENT NAME]" or "Client ABC"
- [ ] Project site addresses → Replace with "[PROJECT LOCATION]" or generic city/region
- [ ] Project-specific location maps or coordinates
- [ ] Client contact information (phone, email, names)

**Confidential Business Information:**
- [ ] Contract values, unit pricing, cost breakdowns → Replace with "[REDACTED]"
- [ ] Project budgets and financial data
- [ ] Detailed cost analyses or quotes
- [ ] Proprietary company processes or methods (if unique to client)
- [ ] Bid information or competitive pricing

**Sensitive Project Data:**
- [ ] Detailed project schedules with client deadlines
- [ ] Strategic timelines that reveal client business plans
- [ ] Personnel names or specific role assignments (unless publicly available)
- [ ] Project delays, issues, or disputes
- [ ] Quality/safety incidents or failures

**Personal Information:**
- [ ] Employee names, phone numbers, personal emails
- [ ] Site supervisor or manager direct contact info
- [ ] Any personally identifiable information (PII)

---

## Redaction Examples

### ❌ BEFORE (Confidential):
```
Project: Highway Expansion - Hamilton, ON
Client: XYZ Construction Ltd.
Budget: $2.5M
Schedule: January 2024 - October 2024
Site Superintendent: John Smith (ext. 4521)
Final Cost: $2.3M (92% of budget)
```

### ✓ AFTER (Redacted):
```
Project: [PROJECT NAME] - [LOCATION]
Client: [CLIENT NAME]
Budget: [REDACTED]
Schedule: [DATE RANGE]
Site Superintendent: [ROLE]
Final Cost: [REDACTED]
```

---

## File Types & Redaction Checklist

### Word Documents & PDFs
- [ ] Use Track Changes or redaction tools to highlight sensitive info
- [ ] Export as PDF and redact using PDF editor
- [ ] Delete and re-create file with placeholders
- [ ] Save with REDACTED in filename: `Project_Report_[REDACTED].docx`

### Drawings & Plans
- [ ] Remove or blank out project site names/addresses
- [ ] Remove client logos or project names
- [ ] Blur or redact specific location identifiers
- [ ] Keep technical details (layouts, dimensions) for portfolio value

### Photos
- [ ] Crop to remove signage with client/location names
- [ ] Blur faces of workers/site personnel
- [ ] Remove any identifying landmarks that reveal location
- [ ] Keep progress photos demonstrating work quality

### Excel/Data Sheets
- [ ] Remove client names or replace with "[CLIENT]"
- [ ] Replace all actual costs with "[REDACTED]" or percentages
- [ ] Remove contract numbers or project codes
- [ ] Keep structure and format for demonstrating analytical skills

### Meeting Minutes
- [ ] Remove attendee names or replace with role titles
- [ ] Redact any decisions about pricing or costs
- [ ] Remove specific client concerns or complaints
- [ ] Keep action items and decisions (in general terms)

---

## Commit Guidelines

### Before Each Commit:

1. **Review Files**: Open each file you're adding
2. **Search for Secrets**: Look for:
   - Company names (Ctrl+F)
      - Addresses, phone numbers, emails
         - Dollar amounts and costs
            - Client names
               - Personnel names
               3. **Redact or Remove**: Use placeholders like `[CLIENT]`, `[AMOUNT]`, `[LOCATION]`
               4. **Commit Message**: Include `[REDACTED]` tag if applicable:
                  ```
                     docs: Add project case study [REDACTED]
                        chore: Update financial template [REDACTED]
                           ```

                           ### Git Commit Message Format:

                           ```
                           type(scope): subject [REDACTED if applicable]

                           Example:
                           chore: Add RFI tracking template [REDACTED]
                           docs: Create project overview for Site Excavation Work
                           feat: Add weekly reflection notes
                           ```

                           **Types:**
                           - `docs:` - Documentation, case studies, reflections
                           - `chore:` - Templates, tools, administrative files
                           - `feat:` - New project portfolio additions
                           - `fix:` - Updates or corrections to existing docs

                           ---

                           ## When in Doubt, Ask!

                           If you're unsure whether information is confidential:
                           - **Err on the side of caution** → Redact it
                           - **Ask your supervisor** at Ritestart Limited
                           - **Use placeholder text** instead of actual values
                           - **Create a private note** and share with trusted reviewers before committing

                           ---

                           ## File Upload Policy

                           **Do NOT commit without review:**
                           - Actual cost sheets or pricing
                           - Client contracts or legal documents
                           - Personal employee information
                           - Site security plans or access information
                           - Any document marked "CONFIDENTIAL" or "PROPRIETARY"

                           **Safe to upload (with redaction):**
                           - Progress reports (client names redacted)
                           - Project photos (identifying landmarks removed)
                           - Meeting minutes (attendees anonymized)
                           - Templates and tools (without actual data)
                           - Schedule files (without client-specific details)

                           ---

                           ## Questions?

                           For questions about what's safe to share, contact your supervisor or review internal NDA and confidentiality agreements.

                           **Repository Purpose:** This is a professional portfolio to showcase your skills and experience—not a place for confidential company information.

                           ---

                           **Last Updated:** [Add Date]
