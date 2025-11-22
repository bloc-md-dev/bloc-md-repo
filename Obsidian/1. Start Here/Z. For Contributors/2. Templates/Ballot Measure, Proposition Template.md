---
type: ballot_measure
subtype: proposition | initiative | referendum | bond | tax_measure
id: {{title}}
name: {{title}}
label: A | B | 1 | 2 | (the ballot identifier)
updated: {{date}}

election:
  id: election-id-here   # links to the election template
  name:
  date: YYYY‑MM‑DD

jurisdiction:
  city:
  county:
  state: California

text:
  summary:     # the short voter-friendly summary
  full_text_url:    # PDF or web link to full measure text
  ballot_question:  # the exact question voters see

fiscal_impact:
  summary:
  estimate:

arguments:
  pro:
    - author: person-or-org-id
      text:
    # can have multiple
  con:
    - author: person-or-org-id
      text:

authors / sponsors:
  - person-id or org-id
  - ...

vote_requirement:
  type: simple_majority | supermajority
  threshold_percentage:

results:
  yes_votes:
  no_votes:
  yes_percentage:
  no_percentage:
  passed: true | false

related_people:
  - person-id-1
  - person-id-2

related_organizations:
  - org-id-1
  - org-id-2

notes:
  # any commentary or analysis you want to keep in the metadata

sources:
  - name:
    url:
    description:
---
# Summary / Description

Write a human‑readable explanation of the proposition, its purpose, and key debates.

# Argument “Yes”

(Detail pro side arguments)

# Argument “No”

(Detail con side arguments)

# Financial / Fiscal Impact

# Legal / Policy Implications

# Legacy & Significance

# Sources
