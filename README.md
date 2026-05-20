# CRA-IA-updates

*description of the project*

**Timeframe** 2026-05-06 - 2026-08-12

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/cra-ia-updates-2026](https://cra-test-arc.canada.ca/cra-ia-updates-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-05-20

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Taxes)
    node4(Income tax)
    node1 --x node2
    node1 --> node3
    node3 --> node4
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes.html" _blank
    click node4 "https://www.canada.ca/en/services/taxes/income-tax.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node2,node3,node4 inscope
```
