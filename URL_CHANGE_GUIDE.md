# How to Change Your Site URL

## Current URL Issue
Your current repository name is `mauribe.github.io`, which creates the URL:
```
https://m-a-uribe.github.io/mauribe.github.io/
```

This URL has your username twice, which isn't ideal.

## Recommended Solution: Rename Repository

To get a cleaner URL like `https://m-a-uribe.github.io/`, follow these steps:

### Steps to Rename Your Repository:

1. **Go to your repository on GitHub:**
   - Navigate to: https://github.com/m-a-uribe/mauribe.github.io

2. **Access Repository Settings:**
   - Click on the "Settings" tab (top right of repository page)

3. **Rename the Repository:**
   - In the "Repository name" field, change `mauribe.github.io` to `m-a-uribe.github.io`
   - Click "Rename" button

4. **Wait for GitHub Pages to Update:**
   - GitHub Pages will automatically redeploy your site
   - This usually takes 1-2 minutes
   - Your new URL will be: `https://m-a-uribe.github.io/`

### Important Notes:
- The old URL will automatically redirect to the new URL
- Any links to your site will continue to work
- This is a one-time change with no ongoing maintenance

## Alternative Solution: Custom Domain

If you own a domain name (like `whatscookin.com`), you can use it instead:

### Steps for Custom Domain:

1. **Create a CNAME file** (already prepared in this repository)
   - Add your domain name to the CNAME file

2. **Configure DNS Settings** (with your domain provider):
   - Add a CNAME record pointing to `m-a-uribe.github.io`
   - Or add A records pointing to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

3. **Enable Custom Domain in GitHub:**
   - Go to Settings → Pages
   - Enter your custom domain
   - Enable "Enforce HTTPS"

For detailed instructions, see: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Recommendation

**Rename the repository** to `m-a-uribe.github.io` - this is the simplest and best solution for a personal GitHub Pages site.
