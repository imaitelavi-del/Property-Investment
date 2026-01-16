Estate Nexus - Default Property Development Website (Liquid Glass Theme)

What this is
- A static, multi-page website you can modify later.
- No backend required.
- Projects and news posts are editable in: js/data.js
- Filtering, project detail, and form validation are client-side in: js/app.js

Pages
- index.html (Home)
- developments.html (Projects listing with filters)
- project.html?id=<projectId> (Project detail)
- about.html (Story, leadership, credibility placeholders)
- services.html (Service offerings)
- news.html (Insights listing with categories)
- post.html?id=<postId> (Post detail)
- contact.html (Contact and enquiry form)

How to view locally
Option A
- Double-click index.html and it should open in your browser.
- Some browsers restrict certain features when opening files directly. If anything looks off, use Option B.

Option B
- Run a simple local web server (any method is fine), then open the provided local URL.

How to customise
1) Update company info and socials
- Edit window.EstateNexusData.company in js/data.js

2) Update projects
- Edit window.EstateNexusData.projects in js/data.js
- Keep id values unique. Gallery images can be URLs.

3) Update posts
- Edit window.EstateNexusData.posts in js/data.js

4) Liquid glass look
- Change theme variables and glass styles in css/styles.css

Forms
- Forms validate client-side and simulate success/failure states.
- No real email sending is performed.

Licensing
- Placeholder images are loaded from public image URLs. Replace with your own assets for production use.
