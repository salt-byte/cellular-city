<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/drive/1pqCUETW7Kw_wM9tEdEXmzpQ5Y7ZK959Z

## Run Locally

**Prerequisites:**  Node.js

1. Install dependencies:
   ```bash
   npm install
   ```
2. Set the `GEMINI_API_KEY` in `.env.local` to your Gemini API key (optional)
3. Run the app:
   ```bash
   npm run dev
   ```

## Deploy to GitHub Pages

This project is configured to automatically deploy to GitHub Pages when you push to the `main` branch.

### Setup GitHub Pages (One-time setup)

1. Go to your repository settings: `https://github.com/salt-byte/cellular-city/settings/pages`
2. Under "Source", select **"GitHub Actions"** (not "Deploy from a branch")
3. The deployment will automatically trigger when you push to `main`

### Manual Deployment

If you want to deploy manually:

```bash
npm run build
# Then push the dist folder to gh-pages branch or use GitHub Actions
```

### View Live Site

After deployment, your site will be available at:
`https://salt-byte.github.io/cellular-city/`

**Note:** The first deployment may take a few minutes. You can check the deployment status in the "Actions" tab of your repository.
