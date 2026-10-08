# MIDRA Engineering Website

The public MIDRA Engineering website and the MIDRA Property Intelligence experience live in this project.

## Local development

```bash
npm install
npm run dev
```

Website:
http://127.0.0.1:4321

Local Engineering pages fall back to `http://localhost:8000`. For deployment, set `PUBLIC_MIDRA_ENGINEERING_API_BASE_URL` to the HTTPS MIDRA API origin, or reverse-proxy the API at the Engineering site origin.

## Product direction

The website remains the main MIDRA product. Property Intelligence is integrated into the website rather than being a separate application. The visual language follows the approved Property Intelligence Report: MIDRA navy, restrained blue accents, warm gold details, strong grids, clear data cards, and report-style information hierarchy.

The sample report is available at:

`/reports/MIDRA_Property_Intelligence_Report_Example.pdf`
