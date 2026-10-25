# eTrace — Vercel deployment

The original design, inline CSS, JavaScript, and embedded images are preserved in index.html. Google Fonts needs an internet connection; system fonts are the fallback.

## Deploy with GitHub
1. Extract this ZIP.
2. Create a GitHub repository and upload index.html, vercel.json, and this README.md to the repository root. Upload the extracted files, not the ZIP.
3. In Vercel, choose Add New > Project, and import that repository.
4. Choose Framework Preset: Other. Root Directory: repository root. The included vercel.json sets an empty build command and Output Directory: .
5. Click Deploy and open the URL Vercel provides.

## Preview locally
Double-click index.html to open it in your browser.

## Update
Edit index.html and commit the changes to the connected GitHub repository. Vercel redeploys automatically.

This is a static marketing page. Buy buttons link to the existing contact section; there is no payment processor or software download backend.
