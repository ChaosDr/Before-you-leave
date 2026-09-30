# Before You Leave

A static browser game for Pop Culture Psychology.

## Publish with GitHub Pages

1. Create a new GitHub repository
2. Upload every file in this folder to the repository root
3. Open **Settings → Pages**
4. Under **Build and deployment**, select **Deploy from a branch**
5. Select the `main` branch and `/ (root)`, then save

GitHub will show the public address after deployment. The game needs no server, database, build command, or API key.

## Run locally

Because the game uses JavaScript modules, open it through a small local web server rather than double-clicking `index.html`.

With Python installed:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
