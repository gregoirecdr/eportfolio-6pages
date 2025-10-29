# E-Portfolio – 6 Pages (Static HTML/CSS)

## Files
- `index.html` (Home)
- `engineering-courses.html`
- `mobility.html`
- `civic-engagement.html`
- `sports-hobbies.html`
- `career.html`
- `style.css` (shared styles)
- `images/` (put your photos here)
- `media/` (put PDF slides)
- `cv/` (put cv-en.pdf and cv-fr.pdf)

## Preview locally
- Just double-click `index.html` (and the other pages) in your file explorer.
- Or open the folder in VS Code and use the Live Server extension.

## Publish on GitHub Pages
```bash
git init
git branch -M main
git add .
git commit -m "first publish"
# with GitHub CLI:
gh repo create e-portfolio-6pages --public --source . --remote origin --push
# GitHub → Settings → Pages → Deploy from branch → main / root
```

## Publish on Vercel
```bash
npm i -g vercel
vercel --prod
```
