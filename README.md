AJ Future Tech — GitHub Pages site
=================================

Files included:
- index.html
- about.html
- styles.css
- logo.png (if copied)

How to publish on GitHub Pages (quick):
1. Create a GitHub account (https://github.com) if you don't have one.
2. Create a new repository (example: ajfuturetech.github.io OR any repo name).
3. Upload all files from this folder to the repo.
4. If repo name is <yourusername>.github.io, GitHub Pages will publish at:
   https://<yourusername>.github.io
   Otherwise enable Pages in repo Settings -> Pages -> Choose branch (main) -> Save.
5. After publishing, open the site URL and confirm it loads.

Verify ownership in Google Search Console:
Option A (recommended - HTML file):
1. In Search Console, add property -> URL Prefix -> your site URL.
2. Select "HTML file" verification -> download the file.
3. Upload the file to the root of the repo (same folder as index.html) and push changes.
4. Click VERIFY in Search Console.

Option B (meta tag):
1. In Search Console choose "HTML tag" method.
2. Copy the meta tag.
3. Edit index.html and replace the meta tag placeholder:
   <meta name="google-site-verification" content="REPLACE_WITH_SEARCH_CONSOLE_META_TAG" />
4. Commit and publish, then click VERIFY.

If you want, I can:
- Replace the placeholder meta tag with your actual Search Console meta (paste it here).
- Create the GitHub repo for you (I will provide files and exact steps).