# Cloudways Node.js App

Minimal Express starter for deploying on Cloudways via Git.

## Run locally

```
npm install
npm start
```

Visit `http://localhost:3000`.

## Deploy to Cloudways

1. Push this project to a new GitHub repository.
2. In your Cloudways app dashboard, go to **Deployment via Git**.
3. Generate SSH keys and add the public key to your GitHub account (Settings → SSH and GPG Keys).
4. Paste your repo's SSH URL into **Git Remote Address**, authenticate, and select the branch.
5. Click **Start Deployment**.
6. Set the entry file to `index.js` and make sure the `PORT` environment variable is respected (already handled in this app).
