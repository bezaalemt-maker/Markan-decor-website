# Markan Decor & Event Organization Website

A free, GitHub + Netlify-ready website for Markan Decor & Event Organization.

## What you edit

Open **`config.js`** and change the values under `MARKAN`:

- `businessName` — business name
- `phone1` / `phone1Intl` — main phone
- `phone2` / `phone2Intl` — second phone
- `telegram` — Telegram link
- `whatsappIntl` — WhatsApp number without `+`
- `address` — business address
- `email` — email address
- `tagline` — top tagline

Save the file. Netlify can automatically publish the update when your GitHub repository changes.

## Free publishing setup

1. Create a free GitHub account at https://github.com/.
2. Create a **new public repository**, for example `markan-decor-website`.
3. Upload **all files and the `assets` folder** from this folder.
4. Create a free account at https://www.netlify.com/.
5. Choose **Add new project → Import an existing project → GitHub**.
6. Select your `markan-decor-website` repository.
7. For this static site, leave the build command empty and publish directory as the repository root (`.`).
8. Deploy the site.

Netlify will give you a free address such as `your-site-name.netlify.app`.

## How to edit later

In GitHub, open `config.js`, tap the edit/pencil button, change the information, and commit/save the change. Netlify will redeploy automatically when the repository is connected.

## Important

Keep `index.html`, `config.js`, and the `assets` folder together. The logo is in `assets/markan-logo.png`.
