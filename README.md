# ShiftMate — Free Work Toolkit

**Created by Prabhat** · Initial version 0.1

A static, browser-based toolkit for AHT/productivity, target planning, CSV data checks, a single-shift pay estimate, and workplace message templates.

## Run locally
Open `index.html` in a modern browser. No build step or dependencies are required.

## Deploy to GitHub Pages
1. Upload `index.html` and `README.md` to the root of a repository you own.
2. Go to **Settings → Pages**.
3. Choose **Deploy from a branch**, `main`, and `/ (root)`, then save.
4. Wait for GitHub Pages to publish.

## Included tools
- Weighted AHT calculator: handles multiple case types and time units.
- Target planner: completion, remaining work, pace needed, and a simple projection.
- CSV checker: duplicate rows/keys, missing values, whitespace, and required headers.
- Shift estimator: one shift, overnight shifts, unpaid breaks, regular/overtime split, configurable multiplier.
- Workplace writing templates: local editable drafts, no AI API.

## Privacy
No analytics, ads, remote APIs, accounts, or file uploads are included. CSV parsing and calculations happen in the browser. Inputs are not intentionally stored persistently. Avoid processing confidential work data unless your workplace permits it.

## Limitations
CSV only (not XLSX). Pay estimates exclude tax, statutory deductions, full payroll, and legal entitlements. Writing helper uses static templates. Important results should be independently verified. This is not certified error-free software.

## Testing
`tests/core.test.js` is a dependency-free Node.js test file for core calculations and CSV parsing. Run `node tests/core.test.js` in an environment with Node.js installed. These tests do not replace browser, accessibility, security, or real-world validation.

## Copyright and licensing
© Prabhat. All rights reserved unless a separate written license states otherwise. No third-party runtime dependencies are included in this initial version. A copyright notice is not legal advice and is not a substitute for a formal license decision. Public availability does not itself grant a general license to reuse the source; GitHub's applicable terms still apply.
