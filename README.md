# Revenueable Voice AI — Documentation

The official documentation for [Revenueable Voice AI](https://docs.revenueable.ai) — an AI-powered voice agent platform that automates outbound sales calls, inbound customer support, and revenue workflows using human-sounding AI voice agents.

📖 **Live Docs:** [docs.revenueable.ai](https://docs.revenueable.ai)

## About

Revenueable Voice AI enables businesses to deploy AI voice agents that can:
- Make outbound sales calls and qualify leads
- - Handle inbound customer queries 24/7
  - - Follow up on unpaid invoices and renewals
    - - Schedule appointments and collect data via voice
      - - Integrate with CRM and helpdesk tools
       
        - This repository contains the Mintlify-powered documentation source.
       
        - ## Documentation Structure
       
        - ```
          /
          ├── docs.json              # Navigation and site config
          ├── introduction.mdx       # Overview and quickstart
          ├── api-reference/         # API endpoints and SDKs
          ├── agents/                # Building and configuring AI voice agents
          ├── integrations/          # CRM, telephony, and webhook integrations
          └── guides/                # Tutorials and use case walkthroughs
          ```

          ## Local Preview

          ```bash
          npm i -g mint
          mint dev
          ```

          Open [http://localhost:3000](http://localhost:3000) to preview documentation locally.

          ## Contributing

          Spotted a mistake or want to improve the docs? Open a PR or file an issue. All contributions welcome.

          ## Deployment

          Documentation auto-deploys on every push to `main` via the Mintlify GitHub App.

          ## License

          MIT
          
