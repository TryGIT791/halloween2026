# Halloween Movie Nights — v2.5.0

This package contains the public, mobile-friendly website. No comment tools or private feedback are included.

## Preview on your computer

Extract the ZIP first, then double-click **index.html**. Keep the **assets** folder beside it. Try a narrow browser window to preview the phone layout.

## Upload to your existing GitHub website

1. Extract the ZIP on your computer. Upload the extracted files, not the ZIP itself.
2. Open the repository that hosts your website. Go to its publishing folder (normally the repository's main page; use `docs` if that is how your existing Pages site is configured).
3. Choose **Add file → Upload files**. Drag in **index.html**, the entire **assets** folder, **.nojekyll**, and this **README.md**. They must sit together in the publishing folder, without an extra package folder around them.
4. Use **Commit changes** to save the upload. The new index.html replaces an existing index.html at that location. You do not need to remove your other files.
5. If GitHub Pages is already working, keep its current publishing settings. Otherwise, open **Settings → Pages**, choose **Deploy from a branch**, select the branch you uploaded to (usually main), and choose **/(root)** or **/docs**, matching step 2. Save.
6. Wait for the Pages deployment to finish, then open the website link shown under Settings → Pages. If you see the old version, refresh the page.

The homepage is now **index.html**. If you previously shared a link ending in an older HTML filename, share the website's homepage link instead.

## What's included

- index.html — all movie information, styles and browsing functions
- assets/posters/ — 85 compact WebP movie covers, loaded as needed
- .nojekyll — tells GitHub Pages this is a plain static site
- README.md — these instructions

Keep every file's name and folder location unchanged. No installations or build commands are needed.

Phone improvements: larger tap targets, shorter movie cards, a two-by-two collection menu, and a Browse movies button to return to the filters. Tablets use two or three columns depending on screen width. October's watching order, ratings, trailers, and genre filters are preserved.

Official GitHub instructions:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
