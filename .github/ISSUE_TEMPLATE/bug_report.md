name: 🐛 Bug Report
description: Report a bug or unexpected behavior
title: "[Bug] "
labels: bug
body:
  - type: textarea
    attributes:
      label: Describe the bug
      description: What happened? What did you expect?
    validations:
      required: true

  - type: textarea
    attributes:
      label: Steps to Reproduce
      description: Include a code sample or steps.
    validations:
      required: true

  - type: input
    attributes:
      label: Environment
      description: OS, browser, or version info
