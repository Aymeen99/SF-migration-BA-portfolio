# Salesforce CRM Migration — Business Analysis Portfolio

**Prepared by:** Aymen El Ibrahimi — Business Analyst & Salesforce Administrator  
**Organisation:** ARROW ECS — Quote Factory (QF) Team  
**Document version:** v2.0 — Final  
**Date:** April 2025  

---

## Project overview

This repository contains a pre-migration impact assessment produced for the transition from the current Excel/VBA-based QFTools workflow to Salesforce CRM at ARROW ECS.

The assessment covers the full Salesforce implementation lifecycle across five steps:

1. **Requirement Gathering** - stakeholder map, confirmed AS-IS architecture, functional & non-functional requirements
2. **Solution Design** - gap analysis, AS-IS & TO-BE process diagrams, data model, automation design, integration requirements
3. **Development** - build inventory, BA responsibilities, requirements traceability
4. **Testing** - 13 test scenarios covering functional, edge case, bulk, security, and end-to-end flows
5. **Deployment** - go-live checklist, scenario decision matrix, rollback plan

---

## Key findings

- The root cause of manual line filling is a **data freshness lag** from the weekly ODS extract cycle (up to 7 days), not VBA fragility as initially assumed
- Two migration scenarios were designed and assessed:
  - **Scenario A** - Salesforce fully replaces Excel + VBA, with a direct SWB/Unity API providing real-time data (pending feasibility confirmation)
  - **Scenario B** - Salesforce hybrid alongside the existing Part Master DB pipeline (implementable immediately)
- A direct SWB/Unity API connection, if confirmed, would eliminate the data lag entirely and is the most critical open question of the project

---

## Skills demonstrated

`Business Analysis` `Salesforce Administration` `Process Mapping` `BPMN` `AS-IS / TO-BE` `Gap Analysis` `Requirements Engineering` `Stakeholder Management` `Risk Assessment` `UAT Planning` `Data Architecture` `CRM Migration`

---

## Document

📄 [SF_Migration_BA_v2.0_Aymen_El_Ibrahimi.docx](./SF_Migration_BA_v2.0_Aymen_El_Ibrahimi.docx)
