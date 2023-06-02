---
name: Turtle
about: FHIR specification's Turtle example
title: ''
labels: Example
assignees: ''

---

**Turtle filename**
Any FHIR Turtle example that exhibits this issue, e.g. codesystem-contact-point-use.ttl

**ShEx shape**
Name of Shape Expression corresponding to the location in the Turtle file, e.g. <Observation.component>.

**FHIR Resource**
URL of corresponding attribute on build.fhir.org, e.g. https://build.fhir.org/observation.html#a26.b

**Description**
What the Turtle should be. Can express as diff à la:
``` diff
-  fhir:value [ a fhir:unsingedInt
+ fhir:value [ a fhir:unsignedInt
```
