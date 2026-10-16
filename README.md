# TidalWaterReview

The MHW Submission Review site, live at https://tidalreview.com.

- `index.html` is the whole app (built from the single-file source; libraries and form templates are inlined).
- `ocr/` holds the text-recognition files used to read surveys whose words aren't saved as text in the PDF.
- Pushing to `main` redeploys the site through Cloudflare Workers (`wrangler.jsonc`).
