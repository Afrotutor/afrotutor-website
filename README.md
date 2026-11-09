# AfroTutor Website

A responsive AfroTutor marketplace website starter for **www.theafrotutor.com**.

## Brand
- Deep green, gold and white
- Official logo asset expected at `assets/afrotutor-logo.png`
- Brand message: Connecting African Tutors with Students Worldwide
- Motto: Find. Learn. Teach. Achieve.

## Files
- `index.html` — homepage and marketplace entry points
- `styles.css` — responsive styles
- `app.js` — mobile navigation and tutor-search interface

## Preview locally
Open `index.html` in a browser, or serve this folder with any static web server.

## Important integration status
This repository currently contains a front-end prototype. Tutor search is a UI demonstration; registration links open email drafts. No live authentication, database, bookings, payment processing, tutor verification, messaging, dashboards or admin workflows are connected yet.

Before launch:
1. Add the supplied official AfroTutor logo at `assets/afrotutor-logo.png` and promotional artwork at `assets/afrotutor-promo.jpg`.
2. Connect the approved Supabase project using public client configuration only. Never commit service-role keys or payment secrets.
3. Implement server-side booking and payment workflows, including the agreed payment holding/release rules and 3% service charge.
4. Configure privacy, terms, safeguarding and refund policies.
5. Test mobile, desktop, accessibility, security and payment flows.
6. Configure hosting and DNS for `www.theafrotutor.com`.

## Deployment
This static front end can be hosted on GitHub Pages, Vercel or Netlify. A production marketplace needs a secure backend and deployment environment in addition to these static files.
