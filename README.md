# Consensus Sequential Convex Programming

Project page for **Consensus / Operator-Splitting SCP (OS-SCP)**.

Live site:  
https://nataliapavlasek.com/consensus-scp/  
(also redirects from https://nataliapavlasek16.github.io/consensus-scp/)

Personal site listing:  
https://nataliapavlasek.com/projects.html

## Edit this page

Collaborators: edit `index.html` and the figure assets in this repo. The personal website only links here and keeps a thumbnail.

| File | Role |
|------|------|
| `index.html` | Project page content |
| `scp_overview.png` / `.pdf` | Standard multi-start SCP figure |
| `osscp_overview.png` / `.pdf` | OS-SCP figure |
| `assets/` | CSS, JS, fonts (usually leave alone) |

## Local preview

```bash
cd /path/to/consensus-scp
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish (one-time setup)

1. Create a GitHub repo named `consensus-scp` under `nataliapavlasek16` (or your org).
2. Push this folder:

```bash
cd /Users/nataliapavlasek/Documents/consensus-scp
git add .
git commit -m "Initial Consensus SCP project page"
git remote add origin git@github.com:nataliapavlasek16/consensus-scp.git
git push -u origin main
```

3. On GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
4. Invite your collaborator: **Settings → Collaborators**.

If the GitHub username or repo name differs, update the URL in
`nataliapavlasek16.github.io/projects.html` to match.
