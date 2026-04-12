# Resume site (minimal)

This is a minimal static resume site scaffold. Files added:

- `index.html` — main page with About, Resume, Interests, Projects, Contact
- `styles.css` — lightweight styles

To preview locally:

```bash
cd "/Users/mattramos/Downloads/Personal Project"
# Python 3: serves at http://localhost:8000
python3 -m http.server
```

## Deploy (free, anyone can access)

### Option 1: GitHub Pages (easiest)
1. Create a GitHub account at github.com (if you don't have one).
2. Create a new public repo named **`yourusername.github.io`** (replace yourusername).
3. Clone it, copy these files into it, and push:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   # Copy index.html, styles.css, resume.pdf here
   git add .
   git commit -m "Initial site"
   git push
   ```
4. Your site is **live** at `https://yourusername.github.io` — share that link.
1
### Option 2: Vercel (super fast deployment)
1. Push your files to a GitHub repo (any name).
2. Go to [vercel.com](https://vercel.com), sign in with GitHub.
3. Click "Import Project" → select your repo → deploy (one click).
4. Your site gets a live URL instantly; every push auto-deploys.

## Next steps
- Edit `index.html` with your real name, bio, projects.
- Add a `resume.pdf` file next to it.
- Follow the deploy steps above to go live.
