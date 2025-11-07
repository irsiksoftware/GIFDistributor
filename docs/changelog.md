# Changelog

## 2025-11-07 - Secret Rotation

### Security
- Rotated OpenAI API keys (OPENAI_API_KEY and OPENAI_API_KEY_DEV)
- Previous rotation date: 2025-01-15 (290 days ago)
- New rotation date: 2025-11-07
- Next rotation due: 2026-02-05 (90 days)

### Actions Taken
- Generated new OpenAI API keys for production and development
- Updated OPENAI_API_KEY_DEV in GitHub Secrets
- Tested AI safety scanner in development environment
- Updated OPENAI_API_KEY in GitHub Secrets (Production environment)
- Monitored production workflows for errors
- Old keys to be revoked after 7-day rollback period (2025-11-14)
- Updated LAST_ROTATION_DATE in .github/workflows/secret-rotation-check.yml

### References
- Issue: #64
- Documentation: docs/secrets-management.md
