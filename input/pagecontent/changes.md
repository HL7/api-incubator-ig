**Content moved to the Incubator:**
* [FHIR-54745](https://jira.hl7.org/browse/FHIR-54745):  Type Factory moved to incubator
* [FHIR-54742](https://jira.hl7.org/browse/FHIR-54742):  General Service API moved to incubator
* [FHIR-54078](https://jira.hl7.org/browse/FHIR-54078):  Type Factory moved to incubator
* [FHIR-53954](https://jira.hl7.org/browse/FHIR-53954):  Type Factory and General Service API moved to incubator

### Issues Released in initial Incubator snapshot
**Changes since FHIR R6 ballot4:**
* Replaced the Bundle-based Asynchronous Interaction Request Pattern with a simplified, redirect-based
  revision on [async-interaction.html](async-interaction.html): polling returns `303 See Other` on
  completion (for both succeeded and failed jobs), and the result endpoint returns exactly what the
  synchronous interaction would have returned, with no Bundle wrapper. The prior page location,
  [async-bundle.html](async-bundle.html), now points to the new page; the earlier pattern remains
  published in [FHIR R5](https://hl7.org/fhir/R5/async-bundle.html). ([FHIR-50861](https://jira.hl7.org/browse/FHIR-50861))
* [FHIR-57312](https://jira.hl7.org/browse/FHIR-57312):  Define FHIRPath functions section() and entry() on Composition
