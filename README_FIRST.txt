WINTER ARC — ADSENSE FIX PACKAGE
================================

WHY THIS PACKAGE EXISTS
Google's email said the AdSense application needs changes before approval.
The current root index.html is primarily an authenticated dashboard. For
AdSense review, the public root should contain accessible, original content
and clear navigation.

DO THIS IN GITHUB
1. Open repository: gupta234/gupta234.github.io
2. Rename the CURRENT index.html to app.html and commit that rename.
   This preserves your existing Winter Arc dashboard.
3. Extract this ZIP.
4. Upload these files to the repository root:
      index.html
      privacy.html
      terms.html
      ads.txt
      robots.txt
      sitemap.xml
5. Commit the upload.
6. Open:
      https://gupta234.github.io/
      https://gupta234.github.io/app.html
      https://gupta234.github.io/privacy.html
      https://gupta234.github.io/ads.txt
7. Confirm all pages load normally.

ADSENSE
- The new public index contains your existing publisher code:
  ca-pub-6551032201404007
- ads.txt contains:
  google.com, pub-6551032201404007, DIRECT, f08c47fec0942fa0
- In AdSense, check Sites and re-check the site after deployment.
- Request review only after the public pages are live and working.

IMPORTANT
Your old dashboard page contains the AdSense loader. If you later enable
Auto Ads, exclude /app.html in AdSense or remove the AdSense script from
app.html, because the dashboard is primarily an interactive/user-specific
screen rather than publisher content.

This package improves the problems suggested by the email, but Google alone
decides approval. Do not create fake traffic or click your own ads.
