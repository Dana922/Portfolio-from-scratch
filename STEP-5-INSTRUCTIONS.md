# Step 5 — Add released product evidence

This is a complete replacement package for the portfolio source. It adds a curated, de-identified sequence from the 79-screen desktop and mobile evidence review to the medical-claims case study.

## Update the GitHub repository

1. Extract `dana-portfolio-step-5.tar.gz`.
2. Open the extracted `portfolio-step-5` folder.
3. In GitHub Codespaces, open the root of `Portfolio-from-scratch`—the folder containing `package.json`.
4. Upload or drag **the contents inside** `portfolio-step-5` into that repository root and allow matching files to be replaced.
5. Do not place the files inside `node_modules` or another nested folder.

## Reinstall and preview

From the repository root, run:

```bash
rm -rf node_modules
npm install
npm run dev -- --host 0.0.0.0
```

Open the forwarded preview and visit `/work/medical-claims/`.

## Commit after checking the page

```bash
git add .
git commit -m "Add released medical claims evidence"
git push
```

Cloudflare will rebuild from the pushed repository.

## What changed

- Reviewed 79 unique desktop and mobile product screenshots.
- Added six representative released-product frames to the medical-claims case study.
- Kept the medical-claim narrative separate from the adjacent estimate flow.
- Removed personal names, plan selections, balances, claim amounts, and dates from published evidence.
- Added a responsive evidence narrative and mobile product frame.
