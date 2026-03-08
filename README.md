# Cronozen Docs

Developer documentation for the Cronozen platform.

## Structure

```
├ getting-started/    Introduction, quickstart, core concepts
├ architecture/       System design, multi-tenant, DPU
├ auth/               Authentication, JWT, multi-tenant auth
├ tenant/             Tenant system, workspaces, membership
├ agents/             AI agents, workflow automation
├ api-reference/      API endpoints documentation
├ llms.txt            AI-readable platform description
└ mint.json           Mintlify configuration
```

## Development

```bash
# Install Mintlify CLI
npm i -g mintlify

# Run locally
mintlify dev
```

## Deployment

Push to `main` → Mintlify auto-deploys to `docs.cronozen.com`.
