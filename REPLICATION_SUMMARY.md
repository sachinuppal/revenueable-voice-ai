# Revenueable AI Documentation Replication

This documentation site has been replicated from the structure of `https://docs.ringg.ai` (source: `https://github.com/Stonkr/ringg-api-docs`), with all branding updated to **Revenueable AI**.

## What was done
1.  **Cloned Source**: The original documentation source code was cloned.
2.  **Branding Replacement**: A global find-and-replace was performed to change:
    *   `Ringg AI` -> `Revenueable AI`
    *   `Ringg` -> `Revenueable`
    *   `ringg.ai` -> `revenueable.ai`
    *   `ringg` -> `revenueable`
3.  **Configuration Update**: `docs.json` (Mintlify config) was updated with the new name, colors (preserved), and links.

## How to Run locally

This documentation uses [Mintlify](https://mintlify.com/).

### Prerequisites
- Node.js installed.
- Mintlify CLI: `npm i -g mintlify`

### Steps
1.  Navigate to this directory:
    ```bash
    cd revenueable-docs
    ```
2.  Install dependencies (if any, though Mintlify uses the CLI):
    ```bash
    npm install
    ```
3.  Run the development server:
    ```bash
    mintlify dev
    ```
    (Or `npx mintlify dev` if you didn't install globally)

4.  Open `http://localhost:3000` to view the docs.

## Next Steps
-   **Logos**: Replace `logo/light.svg`, `logo/dark.svg`, and `favicon.png` with Revenueable AI assets.
-   **Links**: Review external links (social media, contact emails) in `docs.json` to ensure they point to the correct Revenueable properties.
-   **Deployment**: You can deploy this repo directly to Mintlify or any static hosting that supports MDX if you build it (though Mintlify hosting is recommended for this structure).
