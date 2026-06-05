# Theme authoring notes

Hermes dashboard themes are YAML files copied into:

```bash
~/.hermes/dashboard-themes/<theme-name>.yaml
```

A theme should include:

- `name`: stable lowercase ID
- `label`: display name
- `description`: short public description
- `palette`: base background/midground/foreground colors
- `typography`: font choices
- `layout`: radius and density
- `terminalBackground`: terminal surface color
- `colorOverrides`: semantic colors
- `customCSS`: optional dashboard polish

## Screenshot rules

Use sanitized demo screenshots. Avoid capturing:

- real conversations
- API keys or tokens
- usernames, email addresses, chat IDs, phone numbers
- local paths, hostnames, private repos, private issue names

Prefer a static demo page when possible.
