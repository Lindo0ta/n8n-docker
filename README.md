---
title: AVA n8n
emoji: ⚡
colorFrom: blue
colorTo: purple
sdk: docker
app_port: 7860
pinned: false
---

# AVA — n8n en Hugging Face

Instancia de n8n para los flujos de automatización de AVA (UNIMINUTO).

## Variables requeridas (configurar en Settings → Secrets)

| Variable | Descripción |
|---|---|
| `N8N_ENCRYPTION_KEY` | Clave de cifrado de n8n (cualquier string largo) |
| `DB_TYPE` | `postgresdb` |
| `DB_POSTGRESDB_HOST` | Host del Transaction Pooler de Supabase |
| `DB_POSTGRESDB_PORT` | `6543` |
| `DB_POSTGRESDB_USER` | `postgres.TUPROJECTREF` |
| `DB_POSTGRESDB_PASSWORD` | Password de Supabase |
| `DB_POSTGRESDB_DATABASE` | `postgres` |
| `B2_KEY_ID` | Application Key ID de Backblaze |
| `B2_APP_KEY` | Application Key de Backblaze |
| `B2_BUCKET` | Nombre del bucket |
| `B2_BUCKET_ID` | ID del bucket |
| `JINA_API_KEY` | API Key de Jina AI |
| `SUPABASE_URL` | URL del proyecto Supabase |
| `SUPABASE_KEY` | Service Role Key de Supabase |
| `GROQ_API_KEY` | API Key de Groq |
