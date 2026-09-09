# Fringelo
Please approve 26h for Horizons, since 75 of 101 hourse were already submitted to HCTG:
<img width="1026" height="694" alt="Screenshot 2026-09-09 at 11 57 01 PM" src="https://github.com/user-attachments/assets/f72114ae-0c2b-4f40-879e-ebe489c15e65" />

## Demo

- **URL:** [app.fringelo.com](https://app.fringelo.com)
- **Email:** demo@fringelo.com
- **Password:** demo1234

## What is Fringelo?

Fringelo is basically very similar to Vercel or Coolify, but it's running on my own server and is heavily personalized for my use case.

That means:

- **Integrated APIs in web IDE:** integrated DB, ChatGPT API, Gemini API etc., with automatic API key management of these APIs.
- **Web IDE:** simple VS Code–like web IDE for quick fixes.
- **MCP support:** everything can be done with MCP by Claude.
- **Automatic DNS:** all my domains are connected — I don't need to set DNS records, it's automatically handled by Fringelo via the Cloudflare API.

## Usage

Log in to the [demo](https://app.fringelo.com) with the credentials above and explore:

- **Dashboard:** overview of your projects, deployments and usage.
- **Codespaces:** create a codespace, open the built-in web IDE, edit files and commit/push straight from the browser.
- **Deployments:** view deployments per project, including custom domains.
- **Domains:** manage coonected domains (Cloudflare-backed DNS automation).
- **APIs:** browse the integrated API catalog (DB, ChatGPT, Gemini, etc.) and manage keys.
- **Tables:** create and manage database tables/columns without writing SQL by hand.

There are 3 demo projects, demonstrating some of the features:
- Orbit: Databse + OpenAI API
- Media-Uploads: Database + File Storage API
- guestbook: Database (4 codespaces each with an own domain connected)
    1. guestbook.polan.dev
    2. todos.polan.dev
    3. links.polan.dev
    4. poll.polan.dev
    
## Tech Stack

- **Frontend:** Vue + Vite + a little bit of TypeScript
- **Backend:** native PHP + MariaDB

## AI Declaration

I used AI for repetitive tasks like migrating my old hand-written (you can tell) backend to a new proper architecture with routes and middleware. Also for changing the accent color and some general stuff which would take ages to go through all files.
