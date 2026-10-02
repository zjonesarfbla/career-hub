CAREER HUB V2 - STATIC EDITION

This version intentionally does NOT use Next.js, npm, TypeScript, React, or a build command.
It is a plain static website so Vercel can serve it without running npm run build.

VERCEL / GITHUB:
1. Replace the old career-hub repository contents with index.html and vercel.json from this folder.
2. Commit and push to GitHub.
3. In Vercel, redeploy the project.
4. If Vercel asks for Framework Preset, choose Other.
5. Leave Build Command EMPTY.
6. Leave Output Directory EMPTY.
7. Root Directory should be the folder containing index.html.

LOCAL TEST:
You do not need npm. Double-click index.html, or use a simple local server if desired.

FEATURES:
Dashboard, certifications with local saving/search/delete/add, resume area, application tracker,
skills, goals, documents, settings, dark mode, responsive mobile navigation.

The site uses localStorage for its data. Supabase can be connected later without changing the deployment method.
