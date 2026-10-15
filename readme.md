# MyPDF standalone website starter

## Included working browser-side tools
- Merge PDF
- Split PDF by page ranges
- Rotate PDF pages
- JPG/PNG/WebP images to PDF
- PDF pages to JPG ZIP
- PDF text extraction to TXT
- PDF text export to basic DOCX
- DOCX to basic text PDF
- Image compression to JPG ZIP
- Image-to-text OCR (English/Hindi via Tesseract)
- PDF compression by rasterizing pages (may reduce quality and makes text non-selectable)

## Deliberate limitation
The "Password Protect" card intentionally returns a clear error. The included JSZip library does not encrypt ZIP files, and pdf-lib does not provide PDF encryption. Do not mistake a ZIP container for an encrypted/password-protected PDF. Use a vetted encryption library or backend before offering real password protection.

## Run / deploy
This is a static website. Extract the ZIP and open `index.html`, or deploy all files to Netlify, Cloudflare Pages, or GitHub Pages. Internet access is needed to load CDN libraries. Some browser APIs work best over HTTPS.
- Netlify: https://app.netlify.com/
- Cloudflare Pages: https://pages.cloudflare.com/
- GitHub Pages: https://pages.github.com/

## Domain note
The site is branded "MyPDF" in the files, but ownership/availability of `mypdf.com` has not been verified. A free hosting subdomain can be used while testing. A custom `.com` domain usually costs money, and another party may own it.

## Important
- The visual layout and tool names are original; this is not a copy of iLovePDF's code or brand assets.
- This project has no server upload feature by design. OCR/DOCX features load libraries from CDNs.
- Complex PDFs, scanned pages, tables, fonts, and layout may not convert perfectly. Test with your own non-sensitive sample files.
- No AdSense code or approval guarantee is included. Before applying, add original useful content, real contact information, accurate privacy disclosures, and test every tool.
