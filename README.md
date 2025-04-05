# Reltio Environment Switcher

This is a simple static web tool for switching between Reltio documentation environments (UAT, STAGING, PROD) while keeping the same path.

## How It Works

- Detects the current environment from the pasted URL
- Offers to open the same page in other environments
- Supports both staging base URLs:
  - `https://reltio-staging.portal.heretto.com/en`
  - `https://docstaging.reltio.com/en`

## How to Publish

To host using GitHub Pages:

1. Clone this repo
2. Push to `main` branch
3. Go to **Settings → Pages**
4. Select `main` branch, folder: `/ (root)`
5. Access your tool at:
   `https://your-username.github.io/env-switcher/`

## License

MIT
