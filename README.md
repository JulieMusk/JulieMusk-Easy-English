# IELTS 8.5 Adaptive Learning Studio

A Chinese-first, browser-based IELTS study prototype focused on foundational English before test-taking strategies.

## Features
- Daily 6-hour learning plan and 30-day phases
- Foundational grammar lessons and reading sentence-analysis lessons
- Original diagnostic questions, vocabulary notebook, study journal, and local JSON export
- Official IELTS preparation-resource links

## Deploy with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. The workflow in `.github/workflows/pages.yml` deploys `index.html` on pushes to `main`.
4. Wait for the Pages workflow to complete, then open the URL shown in Settings → Pages.

## Important scope and limitations
- This is a static prototype, not yet an AI-powered adaptive tutor. Current adaptation is rule-based and uses local browser storage.
- No API keys are included. Never put model-provider secrets in browser JavaScript. Add a secure server-side API/proxy before connecting an AI model.
- The site links to official public IELTS resources. It does not reproduce copyrighted paid Cambridge books or a complete proprietary official question bank. Import only material you are authorized to use.
- Scores and mastery indicators are practice signals, not official IELTS scores or guarantees.

## Local development
Open `index.html` in a modern browser. Progress is stored in that browser's local storage.
