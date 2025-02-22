---
id: encounter
title: "Encounter"
---

import { JsonDataTable } from '@site/src/components/JsonDataTable';

The encounter table is intended to store information that represents a unique 
patient interaction with the healthcare system.  It's intended to be synonymous 
with a healthcare visit (e.g. hospital admission, office visit, etc.).  All 
healthcare analytics use cases involving utilization require an encounter 
concept.  Not only is it important to know about each unique encounter a 
patient has with the healthcare system, but it's also important to know the 
type of visit (e.g. acute inpatient, ED, office visit, inpatient rehab, etc.), 
the start and end dates for the visit, the total amount paid for the visit, and 
other pieces of information about the visit.  The encounter table stores all of 
this important information in a single table.

**Primary Keys:**
  * encounter_id

**Foreign Keys:**
  * person_id

<JsonDataTable jsonPath="nodes.model\.the_tuva_project\.core__encounter.columns" />