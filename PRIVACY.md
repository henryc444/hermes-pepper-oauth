# Privacy Policy — hermes-pepper

**Last updated:** 2026-10-28  
**Operator:** Henry Chan  
**Contact:** hermespepperhk852@gmail.com

## Who this covers

This policy applies to the personal OAuth application branded **hermes-pepper** in Google Cloud, used only by Henry Chan and his own automation agents (Hermes / Pepper fleet) to access Google account data belonging to `hermespepperhk852@gmail.com`.

## What data is accessed

With your (the account owner's) explicit Google consent, hermes-pepper may access:

- **Google Drive** files and metadata that the signed-in account can already open (create, read, update, organize, and export as needed for automation)
- Basic Google account identity needed to complete OAuth (email address of the signed-in account)

The app does **not** request access to other people's Google accounts.

## Why data is accessed

Data is used solely to:

- Store and retrieve documents, plans, and deliverables in the operator's own Drive
- Run personal automation workflows (agents acting for the same operator)

## How tokens and data are stored

- OAuth access and refresh tokens are stored in the operator's private infrastructure (local agent hosts and password manager), not in this public repository
- Tokens are used only to call Google APIs for the consented account
- Drive file contents stay in Google Drive unless the operator explicitly exports or copies them for a task

## Sharing

- **No sale** of personal data
- **No sharing** with third-party advertisers or unrelated vendors
- Google receives API traffic as required to provide Drive / OAuth services under Google's own terms

## Retention

- Tokens are kept while the operator continues to use hermes-pepper and can be revoked anytime in [Google Account → Third-party access](https://myaccount.google.com/permissions)
- Revoking access stops further API use; already-downloaded working copies on the operator's machines are deleted when the operator removes them

## Contact

Questions: hermespepperhk852@gmail.com
