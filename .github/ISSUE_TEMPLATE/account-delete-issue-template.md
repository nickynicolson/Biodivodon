---
name: Account delete issue template
about: Delete account from list
title: ''
labels: account delete
assignees: ''
body:
- type: textarea
  attributes:
    label: Account name
    description: What account name would you like removed from the list?
    placeholder: Example: @username@mastodon.social
    value: account name
  validations:
    required: true
- type: markdown
  attributes:
    value: "Thanks for submitting a request"
---
