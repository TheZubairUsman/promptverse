# Daily High-Potential Global Leads Generation Prompt

## Overview
Generate a **daily list of 5 high-potential global leads** that are actively seeking — or are very likely to need — the following services:

- Software Development (Web, Mobile Apps, SaaS Tools)
- Software Security Auditing & Penetration Testing
- Cybersecurity Services (API, Cloud, Network)
- Shopify / eCommerce Store Setup & Maintenance
- Digital Transformation or Technology Consultation

## Lead Requirements
The leads must include:
- **Company / Brand Name**
- **Business Type** (Startup, Agency, E-commerce, etc.)
- **Website URL** or **Social Profile**
- **Primary Contact Email** (decision-maker or professional email preferred)
- **Location** (focus on English-speaking or tech-active regions)
- **LinkedIn Profile(s)** (company or key decision-maker if available)
- **Contact Number** (if public)
- **A short 1-2 sentence insight about their potential pain point or current struggle**  
  (e.g., outdated website, hiring for dev roles, new product launch, lack of security posture)
- **Source Link** (job posting, funding news, LinkedIn activity, etc.)

## Prioritization Rules 🎯
1. Highlight **new startups, growing software houses, marketing agencies, and online businesses** scaling operations or outsourcing tech/security needs.
2. Focus on companies that show **active growth signals** such as:
   - Recent funding announcements
   - Job postings for dev/security roles
   - Launching new SaaS or eCommerce offerings
   - Requests for proposals (RFPs) or tech migrations
3. Exclude irrelevant businesses (e.g., local restaurants, personal blogs, non-tech small shops).

## Output Format 📝
Return cleanly in **JSON array** with these exact keys:

```json
[
  {
    "name": "",
    "type": "",
    "location": "",
    "contact_email": "",
    "website": "",
    "linkedin": "",
    "contact_number": "",
    "potential_need": "",
    "source_link": ""
  }
]
```

Ensure the insights in `potential_need` are concise but actionable for an outreach pitch.
