
# Deployment Guide for edsaxton.com

These files represent a complete, static build of the Ed Saxton personal website.
To deploy these files to your web hosting provider:

1. Upload all files and folders in this directory to your web hosting service
2. Ensure your domain (edsaxton.com) points to this directory
3. Make sure the server is configured to serve index.html for the root path

For GitHub Pages deployment:
1. Create a GitHub repository named 'edsaxton.github.io' (replace with your username)
2. Upload these files to that repository
3. GitHub Pages will automatically serve your site

For custom domain setup with GitHub Pages, add these DNS records:
- A record: @ → 185.199.108.153
- A record: @ → 185.199.109.153
- A record: @ → 185.199.110.153
- A record: @ → 185.199.111.153
- CNAME record: www → yourusername.github.io
