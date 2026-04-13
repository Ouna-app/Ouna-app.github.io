# Ouna Website

Public website for Ouna Academic Planner.

## Hosting on GitHub Pages

1. Go to your repository settings on GitHub
2. Navigate to **Pages** (under Code and GitHub Pages)
3. Set **Source** to `Deploy from a branch`
4. Select branch: `main` (or your default branch)
5. Set folder to `/ (root)`
6. Click **Save**

Your site will be live at `https://yourusername.github.io/ouuna/`

## Custom Domain

To use a custom domain (e.g., `ouuna.app`):

1. Add your domain in GitHub Pages settings
2. Create a CNAME file in the website folder:
```
ouuna.app
```
3. Configure DNS at your domain registrar:
   - Add CNAME record: `ouuna.app` → `[username].github.io`

## Files

- `index.html` - Main landing page
- `privacy-policy.html` - Privacy Policy
- `terms.html` - Terms of Service

## Apple-Style Design

This website features:
- Light and dark mode support (follows system preference)
- Apple-inspired typography (SF Pro)
- iOS-style navigation and components
- Responsive design for all device sizes