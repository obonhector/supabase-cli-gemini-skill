---
name: supabase-cli
description: "Native Supabase CLI integration for managing PostgreSQL databases, Auth, Edge Functions, and cloud project configurations. Use when Gemini CLI needs to interact with Supabase projects for local development, migrations, or managing cloud services."
---

# Supabase CLI Skill

This skill enables Gemini CLI to use the official `supabase` command.

## Key Workflows

### 1. Authentication
To use Supabase CLI with cloud projects, you must be logged in. If you are not logged in, ask the user to run:
`supabase login`

### 2. Local Development
- **Initialize project**: `supabase init`
- **Start containers**: `supabase start`
- **Check status**: `supabase status`
- **Stop containers**: `supabase stop`

### 3. Database Management
- **Database migrations**: `supabase migration list`, `supabase migration new <name>`, `supabase db push`
- **Schema generation**: `supabase gen types typescript --local`
- **Seed data**: `supabase seed run`

### 4. Edge Functions
- **Create function**: `supabase functions new <name>`
- **Deploy function**: `supabase functions deploy <name>`
- **Serve locally**: `supabase functions serve`

### 5. Cloud Project Management
- **List projects**: `supabase projects list`
- **Link to project**: `supabase link --project-ref <project-id>`
- **Manage secrets**: `supabase secrets list`, `supabase secrets set <name>=<value>`

## Reference
For a complete list of commands, use `supabase help`.
