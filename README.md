# Cashmere mockup — test site

Built files for the Cashmere certificate mockup, published with GitHub Pages for testing:
https://asamark.github.io/cashmere-mockup-site/

Everything in this repository is generated. The source lives in the private
`asamark/cashmere-mockup` repository; redeploy by rebuilding there
(`npx vite build --base=/cashmere-mockup-site/` in `apps/web`) and replacing these files.

All data entered on the test site (certificates, templates, company details, uploads) stays in
each visitor's own browser. QR codes only resolve in the browser that created the certificate.
