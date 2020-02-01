---
title: Implementation Guide Home
layout: default
active: terminology
---

<!-- TOC  the css styling for this is \pages\assets\css\project.css under 'markdown-toc'-->
**Contents**

* Do not remove this line (it will not be displayed)
{:toc}

---

<!-- end TOC -->

<br />

## Introduction

The efforts to standardized clinical assessment data has been ongoing for many years. In 2009, the Office of Nursing Services (ONS) within the Department of Veterans Affairs (VA) initiated an effort to standardize the clinical data documented by VA nurses for wound assessments, eventually expanding that effort to a collaboration chartered by nursing leaders at both VA and Kaiser Permanente. This work resulted in the HL7 Pressure Ulcer Risk domain analysis model (DAM) that passed ballot at HL7 in 2011 (Harris et al, 2015). 
The Skin and Wound Assessment work was continued in 2016 under the direction of the HL7 [Clinical Information Modeling Initiative (CIMI) Workgroup](https://confluence.hl7.org/display/CIMI/Clinical+Information+Modeling+Initiative) and [Logica Health (formerly Health Services Platform Consortrium (HSPC))](https://www.logicahealth.org/). The content development and modeling work was performed in collaboration with Intermountain Healthcare and the Veteran’s Administration (VA). Wound assessment nurses from the VA and the National Pressure Ulcer Advisory Panel (NPUAP) were the validating subject matter experts.
CIMI took on this work in 2017. 
The [Patient Care Workgroup](https://confluence.hl7.org/display/PC/Patient+Care) is the primary sponsor for this work.  The PSS can be found [here](https://confluence.hl7.org/display/CIC/Skin+and+Wound+PSS).

## Overview

### Scope and Usage

#### Scope

The profiles within this wound assessment implementation guide are used to collect a set of standardized and agreed upon data elements for a complete wound assessment. All types of wounds are covered except burns. 

#### Use cases

Use case 1: Stage Four Pressure Injury
Peter Pepper is admitted today for treatment of a stage four pressure injury with tunneling. The wound is 3 cm X 4 cm and 3 cm deep. There is a 3 cm tunnel in the two o’clock direction. The edge of the wound is boggy.

{% include UseCase1.html %}


<br />

## Acknowledgements

**This Implementation Guide was made possible by contributions from the following people and organizations:**

*The [Clinical Information Modeling Initiative (CIMI) Workgroup](https://confluence.hl7.org/display/CIMI/Clinical+Information+Modeling+Initiative)*

- *Nathan Davis, Intermountain Healthcare*
- *Susan Matney, Intermountain Healthcare*
- *Patrick Langford, Intermountain Healthcare*


{% include link-list.md %}
