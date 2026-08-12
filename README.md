# n8n Hosting Fork

This is a fork of the official [n8n hosting repository](https://github.com/n8n-io/n8n-hosting).

This fork adds Helm chart support for `N8N_ENCRYPTION_KEY_FILE`, allowing the
n8n encryption key to be loaded from a mounted file instead of being provided
directly through the `N8N_ENCRYPTION_KEY` environment variable.

For the official hosting configurations, documentation, and current upstream
development, use the [upstream n8n-hosting repository](https://github.com/n8n-io/n8n-hosting).
