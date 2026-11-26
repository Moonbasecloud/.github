<p align="center">
  <a href="https://moonbase.cloud/?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Moonbasecloud/.github/main/profile/assets/banner-dark.png">
      <img src="https://raw.githubusercontent.com/Moonbasecloud/.github/main/profile/assets/banner-light.png" width="100%" alt="moonbase — Build it with AI. Run it with a sentence.">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://moonbase.cloud/?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch"><b>Website</b></a>
  &nbsp;·&nbsp;
  <a href="https://moonbase.cloud/docs/deploy-from-ai-chat?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch"><b>Connect your AI agent</b></a>
  &nbsp;·&nbsp;
  <a href="https://moonbase.cloud/docs/getting-started?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch"><b>Docs</b></a>
  &nbsp;·&nbsp;
  <a href="https://moonbase.cloud/pricing?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch"><b>Pricing</b></a> <sub>(Free plan included)</sub>
</p>

<br/>

<p align="center"><b>moonbase is the platform that runs the apps you build with AI.</b></p>

You build your app in Claude, ChatGPT, Cursor or another AI agent. moonbase gives it everything it needs to live: a managed PostgreSQL database on every plan, hosting on a live HTTPS address, your own domain, versions you can roll back to, and visitor analytics. Then you keep running it from the same chat. No servers to manage, no DevOps.

## Quick start

1. **Add the connector** to your AI tool. You sign in to moonbase in the browser and approve access; no API key goes into the chat.

   ```text
   https://app.moonbase.cloud/mcp
   ```

   Setup steps for Claude, ChatGPT, Cursor, VS Code, Gemini CLI and Devin Desktop: [Deploy from any AI chat](https://moonbase.cloud/docs/deploy-from-ai-chat?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch).
2. **Ask for your app** in the chat, for example: *"Build me a booking app for my yoga studio, with a database for clients and classes, and put it live on moonbase."*
3. **Keep running it from the chat**: *"Connect my domain."* · *"Roll back to yesterday's version."* · *"How many visitors did I get this week?"*

New here? Start with the [getting started guide](https://moonbase.cloud/docs/getting-started?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch) or a ready-made app from [moonbase-examples](https://github.com/Moonbasecloud/moonbase-examples).

<p align="center">
  <img src="https://raw.githubusercontent.com/Moonbasecloud/.github/main/profile/assets/dashboard.png" width="100%" alt="The moonbase dashboard: plan and storage, visitors, daily traffic, countries, sources, devices and top pages">
  <br/><sub>Your moonbase dashboard: every app, its visitors and its storage in one place. (Demo data.)</sub>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Moonbasecloud/.github/main/profile/assets/project-overview.png" width="100%" alt="A project overview in moonbase: health, plan, visitors, live preview, password, domain, MoonGuard, badge and versions">
  <br/><sub>One project: health, visitors, domain, versions. (Demo data.)</sub>
</p>

## What moonbase runs for your app

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>🗄️ Database</h4>
      A managed PostgreSQL database, up to one per project, on every plan — Free included. Created on deploy, connected for you. Export it any time.
    </td>
    <td width="33%" valign="top">
      <h4>🚀 Hosting & deploy</h4>
      Your app goes live on an HTTPS address. Your agent reports when it is up, or tells you why a deploy failed, from the deploy history.
    </td>
    <td width="33%" valign="top">
      <h4>🌐 Custom domains</h4>
      Add your own domain, verify it and check it, step by step.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h4>⏪ Versions & rollback</h4>
      See your app's earlier versions and put one back in one step.
    </td>
    <td width="33%" valign="top">
      <h4>📈 Analytics</h4>
      Visitors over 7 and 30 days, your top pages and where visitors came from.
    </td>
    <td width="33%" valign="top">
      <h4>🔒 Password protection</h4>
      Put a password on a project while you work on it.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h4>🔐 Environment variables</h4>
      List, set and remove them. Secret values are typed on moonbase's own page, never in chat.
    </td>
    <td width="33%" valign="top">
      <h4>👥 Team access</h4>
      Invite members and set their roles. <sub>(paid plans)</sub>
    </td>
    <td width="33%" valign="top">
      <h4>📦 Export</h4>
      Download your app's source any time. It's yours.
    </td>
  </tr>
</table>

## Open source on GitHub

| Repository | What it is |
|---|---|
| **[moonbase-skill](https://github.com/Moonbasecloud/moonbase-skill)** | The moonbase Skill: teaches any AI agent to build, launch and run apps on moonbase, database included. Files for Claude, ChatGPT, Cursor, Copilot and Gemini, plus AGENTS.md for Codex and other agents. MIT licensed. |
| **[moonbase-examples](https://github.com/Moonbasecloud/moonbase-examples)** | Small apps that deploy to moonbase as they are, each with a one-line prompt for your AI agent, including an Express app with a managed PostgreSQL database and a Next.js app. Use one as a template. MIT licensed. |
| **moonbase-deploy-action** <sub>(coming soon)</sub> | A GitHub Action for deploying to moonbase from your workflows. Until it ships, see [Deploying from GitHub Actions](https://moonbase.cloud/docs/github-actions-ci-cd?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch). |

## Connect

| | |
|---|---|
| **Connector (MCP) address** | `https://app.moonbase.cloud/mcp` |
| **Setup for Claude, ChatGPT, Cursor, VS Code, Gemini CLI and Devin Desktop** | [moonbase.cloud/docs/deploy-from-ai-chat](https://moonbase.cloud/docs/deploy-from-ai-chat?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch) |
| **Agent instructions (Skill)** | [moonbase-skill](https://github.com/Moonbasecloud/moonbase-skill) — versioned and updated with the product |
| **CI / GitHub Actions** | [Deploying from GitHub Actions](https://moonbase.cloud/docs/github-actions-ci-cd?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch) |

## Badge

Running on moonbase? Show it in your README:

<a href="https://moonbase.cloud/?utm_source=github&utm_medium=badge&utm_campaign=made-with">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Moonbasecloud/.github/main/profile/assets/badge-made-with-moonbase-dark.svg">
    <img src="https://raw.githubusercontent.com/Moonbasecloud/.github/main/profile/assets/badge-made-with-moonbase-light.svg" alt="made with moonbase" height="40">
  </picture>
</a>

```md
[![made with moonbase](https://raw.githubusercontent.com/Moonbasecloud/.github/main/profile/assets/badge-made-with-moonbase-light.svg)](https://moonbase.cloud/?utm_source=github&utm_medium=badge&utm_campaign=made-with)
```

## Security and trust

- **Report a vulnerability privately:** use **Report a vulnerability** in the Security tab of any of our public repositories, or email [admin@moonbase.cloud](mailto:admin@moonbase.cloud), the contact on [moonbase.cloud/security](https://moonbase.cloud/security?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch) and in [security.txt](https://moonbase.cloud/.well-known/security.txt). Please don't open a public issue. Details: [SECURITY.md](https://github.com/Moonbasecloud/.github/blob/main/SECURITY.md).
- **Verified organization:** this GitHub organization's domain is verified by GitHub.
- **Is moonbase up?** [moonbase.cloud/status](https://moonbase.cloud/status?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch)

## Support and community

- **Help with your account or a project:** [moonbase.cloud/support](https://moonbase.cloud/support?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch) (sign in first), or email [contact@moonbase.cloud](mailto:contact@moonbase.cloud).
- **A wrong fact in the Skill or a broken example:** open an issue in [moonbase-skill](https://github.com/Moonbasecloud/moonbase-skill/issues) or [moonbase-examples](https://github.com/Moonbasecloud/moonbase-examples/issues).
- **Questions and ideas:** [Discussions in moonbase-skill](https://github.com/Moonbasecloud/moonbase-skill/discussions).
- **Follow along:** [X](https://x.com/moonbase_cloud) · [LinkedIn](https://www.linkedin.com/company/moonbase-cloud) · [Changelog](https://moonbase.cloud/changelog?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch)

---

<p align="center">
  <a href="https://moonbase.cloud/changelog?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch">Changelog</a> ·
  <a href="https://moonbase.cloud/status?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch">Status</a> ·
  <a href="https://moonbase.cloud/security?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch">Security</a> ·
  <a href="https://github.com/Moonbasecloud/.github/blob/main/SUPPORT.md">Support</a> ·
  <a href="https://moonbase.cloud/contact?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch">Contact</a> ·
  <a href="https://moonbase.cloud/llms.txt">llms.txt</a> ·
  <a href="https://x.com/moonbase_cloud">X</a> ·
  <a href="https://www.facebook.com/moonbasecloud">Facebook</a> ·
  <a href="https://www.tiktok.com/@moonbase.cloud">TikTok</a> ·
  <a href="https://www.instagram.com/moonbase.cloud/">Instagram</a> ·
  <a href="https://www.linkedin.com/company/moonbase-cloud">LinkedIn</a>
</p>

<p align="center"><sub>Built by <a href="https://moonbase.cloud/about?utm_source=github&utm_medium=org-readme&utm_campaign=gh-launch">Moxie A.R. LTD</a></sub></p>
