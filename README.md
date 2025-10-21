# Periant Organization Configuration

This repository stores the default community health files and templates for all public and private repositories within the `periant-llc` GitHub organization.

The purpose of this repository is to create a consistent and efficient contribution workflow across all our projects.

---

## What's Inside?

This repository contains the following organization-wide files:

### 1. Pull Request Template (`PULL_REQUEST_TEMPLATE.md`)

This file provides a default template for all new pull requests created in any repository within the organization. It ensures that every PR includes a clear description, links to related issues, and a checklist for the contributor to follow.

### 2. Issue Templates (`./ISSUE_TEMPLATE/`)

This directory contains templates for creating new GitHub issues:

-   **`bug_report.md`**: A template for reporting bugs, with sections for steps to reproduce, expected behavior, and environment details.
-   **`feature_request.md`**: A template for proposing new features, focusing on the problem and the desired solution.

When a user creates a new issue in any of our repositories, they will be prompted to choose one of these templates.

---

## How It Works

GitHub automatically uses the files in this repository as defaults for any repository within the `periant-llc` organization that does not have its own local versions of these files in its own `.github` directory.

This allows for centralized management of our contribution guidelines while still giving individual repositories the flexibility to override them if needed.

---

## Security Notice

⚠️ **This is a public repository.**

Under no circumstances should any proprietary information, internal documentation, secrets, API keys, or configuration details be committed to this repository. Its sole purpose is to host public-facing community health and template files.

For all internal and proprietary documentation, please refer to our private documentation repository.
