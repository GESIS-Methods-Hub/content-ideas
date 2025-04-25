---
name: in review
about: to coordinate on content review for Methods Hub
labels: in review
assignees: taimoorkhan-nlp

---

# Issue Title:

# Description:
Provide a detailed description of the issue. Include any relevant context

**Issue Type:**
- type: dropdown
    id: issue type
    attributes:
      label: What is the type of this issue?
      multiple: true
      options:
        - compliance with checklist
        - reusability: to execute or modify
        - replicability: replicating same output
        - documentation: method reporting or template

**Expected Output:**
Describe what you expected to happen.

**Actual Output:**
Describe what actually happened.

**Priority:**
- type: dropdown
    id: priority
    attributes:
      label: What is the priority of this issue?
      multiple: false
      options:
        - low
        - medium
        - high

**Content type:**
- type: dropdown
    id: contentType
    attributes:
      label: What is the type of content?
      multiple: false
      options:
        - method
        - tutorial
