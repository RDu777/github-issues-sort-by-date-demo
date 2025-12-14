# Proposal: “Sort by date created” for GitHub Issues

This document describes a feature idea for GitHub Issues: an explicit option to sort issues by their creation date.

## Problem

In large repositories, maintainers and contributors often need to focus either on the most recently created issues or on very old, still open issues.  
Currently, the Issues list offers several sort options (such as newest, oldest, most commented), but there is no clearly labeled, easily discoverable mode that sorts purely by the creation date across repositories.[web:55]

## Proposed solution

Add a dedicated “Sort by date created” option to the Issues sort control:

- “Date created (newest first)”
- “Date created (oldest first)”

These options would appear in the existing **Sort** dropdown and order issues strictly by their creation timestamp.

## Benefits

- Faster triage of new issues in busy repositories.  
- Easier review of very old, still unresolved issues in chronological order.  
- A clearer mental model for users, because the sort option is explicitly tied to the creation date instead of being hidden behind generic labels.
