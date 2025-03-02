# 🚀 API Examples
SafeDep API Client Examples

## 💻 Authentication

All API examples requires authentication using a `Tenant ID` and `API Key`.
To obtain your API key:

1. Install [vet](https://github.com/safedep/vet)
2. Run `vet cloud quickstart` to create a new tenant and get your API key

Refer to [SafeDep Cloud Quickstart](https://docs.safedep.io/cloud/quickstart) on
alternative ways to obtain your API key.

Once you have your API key, you can set it as an environment variable:

```bash
export SAFEDEP_TENANT_ID=<your-tenant-id>
export SAFEDEP_API_KEY=<your-api-key>
```

All examples use authentication information from the environment variables.

