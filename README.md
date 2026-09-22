# Mohammed Haseeb Ahmed — portfolio

Existing static HTML/CSS/JavaScript portfolio with Bootstrap and its original template assets. No build framework was added.

## Run locally

From this folder, use the existing npm lockfile:

```powershell
npm ci
npm start
```

Open http://127.0.0.1:8088. The preview binds only to loopback. No deployment was performed.

## Interview readiness review — 22 September 2026

- Preserved the initial uncommitted index.html changes: corrected name/profile URL, removed personal detail/count blocks, and retained the move away from undergraduate positioning.
- Updated professional summary and employment/education from the supplied current CV. Omitted unverified production metrics and internal employer architecture.
- Added the AI/backend positioning, an AuditMind case study, and clear evidence/limitations for featured work.
- Removed arbitrary skill percentages, placeholder phone information, and the stale CV download link. The original PDF/DOCX files remain untouched.
- Corrected MNIST layer order from its local notebook. Removed the featured vehicle classifier accuracy claim because it was not revalidated.
- Labeled earlier projects as historical; replaced fragile iframe demos with explicit external links.
- Improved text/link contrast, icon-link names, keyboard filter controls, mobile navigation semantics, section focus, deep-link reloads and reduced-motion behavior.

## Checks actually performed

- Browser visual review at desktop and 390-pixel mobile width; mobile menu navigation and close state, project case-study navigation, deep-link reload.
- Local link/asset scan: no missing local targets.
- JavaScript syntax check, npm dependency check and Git whitespace check passed.
- Existing public GitHub profile and referenced GitHub project URLs returned HTTP 200.
- LinkedIn returned HTTP 999 (automated access blocked); that does not establish a broken profile.
- Older Resume Scanner and DEV hosted endpoints returned 503; PantryDish returned 500; Vehicle Classifier 2.0 host was unreachable. Historical links remain clearly labeled. Do not promise a live demo from them.
- AuditMind actual PDF ingestion, BGE-M3 embedding and retrieval passed; Groq generation returned 401 with the configured credential. Its case study states the blocker.

## Before sharing publicly

The local changes are ready for personal review. The existing hosted URL in Readme.txt has not been updated. Publishing is a separate user action.

Sensitive legacy files already tracked here: assets/Resume(05-06-2024).pdf, assets/Resume(IN).docx, assets/Resume-u.pdf, assets/Resume.pdf, assets/sih.pdf. Removing a download link does not remove these files from a static deployment or Git history. Review what you want public before publishing; this review preserved the files and did not copy the supplied current CV into the site.

Do not describe AuditMind as a live end-to-end demo until the credential is replaced and the supported/unsupported question workflow passes. No AuditMind repository URL has been invented.
