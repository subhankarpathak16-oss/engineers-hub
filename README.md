# Engineer's Hub — first version

A responsive, single-page student help website for Civil and Mechanical Engineering juniors. It includes search, branch/type filters, starter resource cards, PYQ/lab guidance, semester structures, project ideas, external learning links, and a local demo upload form.

## Open locally
1. Download and unzip the folder.
2. Open `index.html` in a modern browser.
3. Try search, branch filters, resource detail cards, semester buttons, and Admin upload.

## Publish a public static demo with GitHub Pages
1. Sign in to GitHub and create a new public repository, e.g. `engineers-hub`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under build/deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish and open the URL shown on the Pages settings screen.

Alternative: create a project on Netlify and drag the unzipped site folder into its manual deploy area. Hosting dashboards may change, so follow the provider's current prompts.

## Important prototype limitation
The Admin upload form is a front-end demo. Uploaded files are held as temporary browser object URLs and entries exist only in the current page session; they are NOT uploaded to a server or shared with classmates. The starter cards are sample placeholders, not verified official college material. The semester subject lists are illustrative and must be replaced with the college's official syllabus.

## To make it a real shared student portal
- Add an authenticated admin login and role-based access control.
- Store metadata in a database and PDFs in private/public object storage with upload limits and file-type checks.
- Add moderation/approval before student-submitted materials become public.
- Do not store passwords, service-role keys, or other secrets in `index.html`.
- Obtain permission before distributing copyrighted notes, books, or question papers; cite source and version/date.
