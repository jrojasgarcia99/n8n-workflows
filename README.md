# n8n workflows

Automation workflows I built in [n8n](https://n8n.io). Each folder has the importable `workflow.json` (credentials removed), a screenshot and setup notes.

| Workflow | What it does | Status |
| --- | --- | --- |
| [Blotato social publisher](blotato-social-publisher/) | Upload a video once through a form; AI writes a caption per platform and publishes to TikTok, Instagram and YouTube via Blotato | Used in production on my own accounts |
| [WhatsApp sales agent](whatsapp-sales-agent/) | AI agent that sells over WhatsApp: searches a Shopify catalog, sends a payment link and creates the order when payment is confirmed | Architecture prototype, not yet run end to end |

## How to import

1. In n8n, go to **Workflows → Import from File** and select the `workflow.json`.
2. Create your own credentials and attach them to the nodes marked with a warning.
3. Replace every `YOUR_...` placeholder (see each folder's README).

Author: [Jesus Rojas García](https://github.com/jrojasgarcia99)
