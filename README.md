# thestayathomedad — Jekyll + Decap CMS starter


A modern, dark-themed blog for affiliate content. No dates. Managed in a web CMS. Deploy to Netlify.


## Quick start


1. **Create repo** on GitHub and upload this folder.
2. **Netlify** → New site → Import from Git → pick your repo.
3. **Build settings**: leave as provided (Netlify reads `netlify.toml`).
4. **Enable Identity**: Netlify Dashboard → Identity → Enable Identity.
5. **Invite yourself**: Identity → Invite users → accept the email.
6. **Enable Git Gateway**: Identity → Services → Enable Git Gateway.
7. Visit `https://YOUR-SITE.netlify.app/admin/` to log in and create posts.


## Writing posts
- In CMS, open **Blog Posts** and click **New**.
- Fill **Title**, **Slug**, **Cover Image** (optional), **Video URL** (optional), **Summary**, **Body**.
- Use **Featured** to choose a homepage hero.
- Use **Order** to sort. Higher number = higher placement.
- Toggle **Published** to hide/show without deleting.


## Images & videos
- Uploaded images land in `assets/uploads` and are served at `/assets/uploads/...`.
- For video, paste a YouTube/Vimeo share URL or a direct MP4 link.


## Styling
- Pico CSS is included for clean defaults.
- Custom dark theme in `assets/css/custom.css` with teal/green accents.


## Pages
- **Home** shows one featured post plus recent posts.
- **Blog** lists all posts and lets readers expand to read inline without new tabs.
- Each post also has its own page at `/blog/your-slug/`.


## Notes
- No dates are used. Sorting is controlled by the **Order** field.
- Links open in the same window. Add Amazon affiliate links directly in the article body.


## Local development (optional)
```bash
bundle install
bundle exec jekyll serve
