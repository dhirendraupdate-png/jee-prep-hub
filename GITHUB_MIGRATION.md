# JEE Prep Hub — GitHub Migration

This repository is the GitHub-owned source-code baseline for JEE Prep Hub.

## Security
- Real environment files are intentionally excluded.
- Copy `.env.example` to `.env` for local development and fill in secrets locally.
- Never commit Supabase service-role keys, API keys, OAuth secrets, SMTP credentials, or database passwords.

## Current migration state
- Existing application source is preserved.
- Existing Supabase migrations are preserved under `supabase/migrations/`.
- Lovable metadata has been removed from the repository baseline.
- Lovable runtime dependencies/integrations are still present in application code and will be migrated in later steps; do not remove them blindly before replacing their functionality.
