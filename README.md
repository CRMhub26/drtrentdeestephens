# Dr. Trent Dee Stephens website

A static one-page site. No build step is needed: deploy `index.html` and the `assets` folder.

## Before going live

1. **Coming Soon books.** In `index.html`, find `THE 12 BOOKS` and replace each `comingSoon` entry with a full entry. Add its cover to `assets/covers/`.
2. **Author photo.** `assets/author.jpg` was cropped from a back cover. Replace it with a higher-quality portrait when available.
3. **Contact form.** Set `CONTACT_ENDPOINT` near the top of the script to a form service URL. While it is empty, the form validates and gives the visitor a ready-made email. It does not deliver messages by itself.
4. **Purchase links.** Add confirmed URLs to each book's `link`. A Purchase button then appears in that book's details.

## Deploy to Vercel

In Git Bash, from this folder:

    npx vercel --prod

Choose to create a new project when asked. When you edit the site, run the same command again.
