# Avi Shein’s academic website

## Update your existing website

Replace index.html and style.css with these versions. Add cv.html. The included publications.html has a matching sidebar and header; if you already added papers, copy your paper entries into it before replacing your existing file.

Keep your existing bpe-thesis.pdf, CV, and personal photo. The included photo.svg is only a placeholder. If you use a personal photo, update the image src on all three HTML pages to its filename.

## Personalize the sidebar

On index.html, publications.html, and cv.html:
- Replace `Hometown: add yours` with your hometown.
- Replace `<span>Email: add yours</span>` with `<a href="mailto:YOUR_EMAIL">YOUR_EMAIL</a>`.
- Use your photo filename in the image src and change alt to `Avi Shein`.

## PDFs

Put bpe-thesis.pdf in the same folder as index.html. Both thesis links point to it.

Add cv.pdf and replace the placeholder paragraph on cv.html with the commented download link. Alternatively, change the top navigation href from cv.html to cv.pdf on all three pages.

## News

Edit the news-list in index.html. Each news item is an <li> element. Add a date if desired.

## Publish

Open this repository in VS Code, save your changes, then run:

```bash
git add index.html publications.html cv.html style.css
git commit -m "Add academic sidebar and thesis news"
git push origin main
```

Stage any newly added PDF or photo as well. GitHub Pages republishes after pushing. Open index.html in your browser to preview locally.
