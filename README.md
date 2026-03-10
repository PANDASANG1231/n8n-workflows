# n8n Workflows

A collection of customized n8n workflows for automation.

## Structure

```
workflows/       # Exported n8n workflow JSON files
credentials/     # Credential templates (no secrets)
docs/            # Documentation for individual workflows
```

## Usage

1. Open your n8n instance
2. Go to **Workflows** → **Import from File**
3. Select the desired `.json` file from the `workflows/` directory
4. Update credentials and environment-specific settings

## Adding a Workflow

1. Design and test the workflow in n8n
2. Export as JSON via **Workflow** → **Download**
3. Save to `workflows/` with a descriptive name (e.g., `slack-daily-summary.json`)
4. Document the workflow in `docs/`

## Notes

- Never commit real credentials or API keys
- Test workflows in a staging environment before production use
