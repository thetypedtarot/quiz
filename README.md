# Discover Your Self-Trust Language

A six-question interactive quiz for **TheTypedTarot**.

## Before publishing

Open `index.html` and find the `SITE_CONFIG` block near the beginning of the JavaScript:

```js
const SITE_CONFIG = Object.freeze({
  bookingUrl: ""
});
```

Paste Lisa's live **Discover: The Map + The Mirror** booking or sales-page URL between the quotation marks.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `.nojekyll`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

GitHub will display the live site URL after deployment.

## Notes

- The quiz is a single-page static site. It does not require npm, a build command, or a database.
- Progress and completed results are stored only in the visitor's browser using `localStorage`.
- The exact brand fonts load from Google Fonts, so internet access is required for the intended typography. Readable serif fallbacks are included.
- The result can be copied or printed/saved as a PDF.
