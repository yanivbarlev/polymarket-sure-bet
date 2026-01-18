# Polymarket Sure Bet Finder (GitHub Pages Version)

A static, client-side version that runs entirely in the browser.

## How to Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload the `index.html` file to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" and choose `main` branch
5. Your site will be live at `https://yourusername.github.io/repository-name/`

## How It Works

- Fetches data directly from Polymarket's API using CORS proxies
- All processing happens in your browser
- No backend server required

## Limitations

- Relies on third-party CORS proxies (corsproxy.io, allorigins.win)
- May be slower than the Python version
- If proxies are down, the site won't work

## Local Testing

Simply open `index.html` in your browser.
