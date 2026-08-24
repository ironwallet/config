# IronWallet Config

Centralized repository for IronWallet application configuration entities. It contains structured configuration data used by the wallet application, including application-level settings and currency-related metadata.

## Purpose

This repository serves as a single source of truth for configuration consumed by IronWallet services and applications. It is intended to simplify versioning, review, and controlled delivery of config changes across environments.

## Structure

Based on the current repository layout, the main directories are:

- `application/` — application configuration entities
- `currencies/` — currency and asset configuration entities

## Branch Strategy

For GitHub Enterprise migration, keep only the following long-lived branches:

- `staging` — pre-release validation
- `main` — production-ready state

Repository history can be reset to a clean initial state if a history-free enterprise import is required.

## Usage

Use this repository as a shared configuration source for wallet-related services, CI/CD pipelines, and application builds. It is suitable for controlled updates, review-based changes, and environment-specific delivery workflows.
