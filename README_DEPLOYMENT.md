# Islam Hamad Eljack - Portfolio Website Deployment Package

## What is inside
- `index.html`: the live portfolio page. It is designed as a standalone HTML file with embedded visual assets and embedded evidence pages.
- `.nojekyll`: helps GitHub Pages serve files without Jekyll processing.
- `netlify.toml`: optional Netlify configuration.
- `vercel.json`: optional Vercel configuration.

## Recommended publishing workflow

### Option 1 - Netlify Drag & Drop (fastest)
1. Sign in to Netlify.
2. Create a new project from files / drag and drop.
3. Drag this whole folder, not only the HTML file.
4. Netlify will publish a live URL. Rename the site name from Site settings if needed.
5. Send the live URL to clients and recruiters.

### Option 2 - GitHub Pages (best for long-term public portfolio)
1. Create a GitHub repository, for example `islam-hamad-portfolio` or `islameljack88.github.io`.
2. Upload all files from this folder. Keep the main file named exactly `index.html`.
3. Go to repository Settings > Pages.
4. Choose deployment from the main branch and root folder.
5. Share the generated GitHub Pages URL.

### Option 3 - Vercel
1. Create a new Vercel project.
2. Import the GitHub repository or upload this static folder.
3. Vercel can deploy the files as-is because there is no framework build step.

## Important sending note
Do not send the HTML file as an email attachment for professional use. Some organizations block local scripts or data URLs in attachments. Publish it once and send the live HTTPS link.

## Suggested message to send with the portfolio
Dear [Name],

Please find my online geospatial leadership portfolio here: [Portfolio Link]. It summarizes my work across Enterprise GIS, surveying, remote sensing, GeoAI, spatial data governance, hydrology, automation, and major infrastructure/agricultural programs across Saudi Arabia, Africa, and the wider region.

Best regards,
Islam Hamad Eljack
