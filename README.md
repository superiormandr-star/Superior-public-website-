# Superior Maintenance and Remodeling — Owner Website

This is a separate static website for Superior Maintenance and Remodeling, styled black / gold / silver and built for phone screens. It is **not** the Handyman Services subscription directory.

## Preview
Open `index.html` in a browser or host this folder with a static web server.

## Deploy
Upload the files inside this folder (not the ZIP itself) to a **dedicated** Superior Maintenance and Remodeling GitHub repository and deploy as a static site on Render, Netlify or GitHub Pages. Do not overwrite the Handyman Services app repository.

## Important before going live
1. Confirm the company's actual public business email. Set `BUSINESS_EMAIL` in `script.js`. Without it, the estimate form intentionally blocks submissions to avoid losing leads.
2. A mailto form requires the visitor to send the prepared email in their email app; it does not directly save leads or send messages on the server. Integrate a secure backend or form service for reliable submissions.
3. Connect estimate approvals/invoices to Superior Command Center separately; the current static page does not implement customer approval, invoice creation, or storage.
4. Replace generic marketing language with reviewed business facts, then add authentic project photography and verified testimonials with permission.
5. If replacing the existing live `chatgpt.site` website, use the website builder's supported edit/publish workflow rather than assuming GitHub files automatically update it.
