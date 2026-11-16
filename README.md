# Ponta plugin for Claude

Ponta lets Claude do real work on your own Windows PCs. Claude can read and sort files, run commands, use desktop apps, work in a web browser and read or draft email on the PCs you add. Anything that could cause harm waits for you to approve it.

This repository is a plugin marketplace with one plugin, ponta. It holds the Ponta connector, a skill that helps Claude use Ponta well, and four starter commands. The plugin's own README is in plugins/ponta.

## Add it

You need Ponta on a Windows 10 or 11 PC first. Get it at https://ponta.ai.

In Claude on the web or the desktop app:

1. Go to Customize, then Plugins.
2. Choose Add, then Add marketplace, and paste https://github.com/pontamcp/ponta-claude-plugin
3. Install Ponta, open its Connectors tab and connect it. Sign in with your Ponta account.

In Claude Code:

```
claude plugin marketplace add pontamcp/ponta-claude-plugin
claude plugin install ponta@ponta
```

Then ask Claude: "Check my Ponta setup and show me what you can do."

## Help and privacy

Help: https://ponta.ai/help. Privacy notice: https://ponta.ai/privacy.

This repository is made from the Ponta source by a build step. Please send changes and questions to support@ponta.ai rather than opening pull requests.

Ponta is made by Roadmap Consulting Ltd, a UK company, trading as Ponta.
