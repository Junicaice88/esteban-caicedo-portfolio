# Esteban Caicedo — Portfolio (Netlify)

Personal portfolio showcasing aerospace research, composite materials projects, and engineering design work.

## Structure
- `index.html` — main page
- `projects.json` — list of projects (edit to add more)
- `assets/` — images (update with your own)
- `style.css` — optional custom styles

## How to deploy on Netlify (UI)
1. Push this folder to a new GitHub repository.
2. In Netlify: **Add new site → Import from GitHub**.
3. Select this repository and click **Deploy site**.
4. Netlify will serve `index.html` automatically. Your site will be live at `https://<your-site-name>.netlify.app`.

## How to add a project
Add a new object to `projects.json`:
```json
{
  "title": "New Project",
  "description": "Short description of what you built / impact.",
  "tags": ["Tag1", "Tag2"],
  "image": "assets/new-image.jpg",
  "link": "https://link-to-more-info"
}
```

## Notes
- Images can be `.jpg/.png/.webp`. Keep sizes small for fast loading.
- Tailwind is loaded via CDN; no build step required.
