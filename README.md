# ANIKA LIBRARY

Ready-to-upload static web app for GitHub Pages.

## Files
- `index.html` — complete app
- `setup.sql` — creates the Supabase `student-photos` bucket and storage policies

## GitHub Pages
1. Upload `index.html` to your repository and Commit changes.
2. Repository Settings → Pages.
3. Under Build and deployment, choose **Deploy from a branch**.
4. Branch: `main`, folder: `/ (root)`, then Save.
5. After deployment, your site will be available at:
   `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Photo setup
In Supabase Dashboard → SQL Editor, paste and run `setup.sql`.
