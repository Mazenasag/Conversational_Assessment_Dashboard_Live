This is a zero-dependency static frontend. No npm install/build is required.

From the repository root, double-click `run_javascript_dashboard.bat` or run:

```bash
node serve_frontend.js
```

Open `http://localhost:8080` and use **Upload Excel file(s)** in the sidebar.
The browser accepts raw weekly exports (the filename must contain `Week N`) and
processed dashboard workbooks. Processing stays in the browser.

For Vercel, set **Root Directory** to `frontend`, **Framework Preset** to `Other`, leave **Build Command** empty, and use `.` as the output directory if Vercel requests one.
