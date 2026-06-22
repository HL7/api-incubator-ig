### Changes

#### 2026-06-11

* Replaced the Bundle-based Asynchronous Interaction Request Pattern with a simplified, redirect-based
  revision on [async-interaction.html](async-interaction.html): polling returns `303 See Other` on
  completion (for both succeeded and failed jobs), and the result endpoint returns exactly what the
  synchronous interaction would have returned, with no Bundle wrapper. The prior page location,
  [async-bundle.html](async-bundle.html), now points to the new page; the earlier pattern remains
  published in [FHIR R5](https://hl7.org/fhir/R5/async-bundle.html). ([FHIR-50861](https://jira.hl7.org/browse/FHIR-50861))
