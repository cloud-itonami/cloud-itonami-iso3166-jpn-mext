# Business Model: Independent MEXT Research-Grant & School-Accreditation Compliance Service — Japan (MEXT)

## Classification

- Repository: `cloud-itonami-iso3166-jpn-mext`
- ISO 3166 (agency-level): `JPN-MEXT`, parent `JPN`
- Ooyake cross-reference: `gov.jpn.mext` (Ministry of Education, Culture, Sports, Science and Technology / 文部科学省)
- Activity: eligibility and reporting requirements for MEXT-administered research grants (科学研究費助成事業/科研費 and related programs), and school or institutional accreditation rules for an operator delivering an education- or research-adjacent public contract
- Social impact: [:research-grant-access :school-accreditation-clarity :public-spend-transparency]

## Customer

- a research organization or university-adjacent operator applying for a MEXT research grant
- an operator delivering an education-sector public contract requiring school/institutional accreditation review
- a foreign research or EdTech vendor confirming MEXT eligibility rules before applying

## Offer

- MEXT research-grant eligibility and reporting-obligation checklist
- school/institutional accreditation walkthrough for education-sector contracts
- ongoing regulatory-change monitoring for MEXT program updates
- compliance-audit export package for the operator's own records

## Revenue

- per-engagement compliance-review fee
- recurring regulatory-change monitoring subscription
- compliance-audit export package

## Trust Controls

- any actual filing, registration, or compliance-program submission
  requires Research & Education Compliance Governor clearance and always escalates to human
  sign-off (`:filing/submit` is never automated at any phase)
- a false or fabricated regulatory-requirement claim is a HARD hold that
  cannot be overridden by human approval alone — it must be corrected
  against a cited MEXT source first
- this service does **not** provide legal or tax advice; characterization
  and filing on the client's behalf beyond checklist/draft assistance
  routes to Japan-licensed counsel or a registered agent
- every requirement cites the official MEXT source or
  regulation, never invented

## Boundary with adjacent actors (read before forking)

- **`cloud-itonami-iso3166-jpn`**: the COUNTRY-level coordinator (general
  Japan public-sector market entry). This repo is a narrower, deeper
  AGENCY-level leaf — most operators need the country-level blueprint plus
  only the agency-level blueprints that actually apply to their contract.
- **`com-etzhayyim-ooyake`** (etzhayyim/root): read-only civic-wayfinding
  mirror of government structure, non-commercial, barred from acting as or
  for the government (G3 impersonation ban). This blueprint is commercial
  and never claims to be Ministry of Education, Culture, Sports, Science and Technology or an official channel.
- **`matsurigoto`** (etzhayyim/root): sovereign e-government statecraft —
  literally the government. This blueprint is an independent operator that
  engages with MEXT under its public rules — never the
  agency itself.
- **`com-etzhayyim-toritsugi`** (etzhayyim/root): guides a consenting
  INDIVIDUAL citizen through their OWN procedure, non-profit,
  donation-only. This blueprint's client is a business operator, not an
  individual citizen, and it is commercial.
- **`cloud-itonami-M6910`**: helps a client BECOME a legal entity
  (incorporation, ISIC 6910) — a prior, different regulatory phase (company
  law). This blueprint assumes incorporation is already done and handles
  MEXT-specific compliance (a different regulatory domain).
