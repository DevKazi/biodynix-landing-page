# BioDynix Landing Page

Bilingual wellness landing page with an exit-intent lead form connected to n8n.

## Local preview

```powershell
python -m http.server 5500
```

Open `http://127.0.0.1:5500/index.html`.

## Configuration

- Replace the n8n test webhook in `index.html` with the production webhook before launch.
- Add the final affiliate destinations to the `affiliateLinks` object in `index.html`.
- Import `lead-capture-workflow.json` into n8n and connect Google Sheets and email credentials.

No credentials are stored in this repository.
