---
name: Change Request
about: Make a CR
title: "[CR]"
labels: submitted
assignees: ''

---

name: Change Request
description: Submit a new change request
labels: ["change-request"]
body:
- type: markdown
  attributes:
    value: "## Change Request Details"
- type: input
  attributes:
    label: Title
    description: Brief description of the change
    required: true
- type: textarea
  attributes:
    label: Description
    description: Detailed description of the proposed change
    required: true
- type: textarea
  attributes:
    label: Impact Analysis
    description: What areas will this change affect?
- type: textarea
  attributes:
    label: Implementation Plan
    description: How will this change be implemented?
