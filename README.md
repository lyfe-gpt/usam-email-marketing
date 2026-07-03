# USAM Fund - Email Marketing

SendGrid-ready HTML email templates for USAM Fund (usamortgage.net), built to the usam.net design system.

**Open `index.html`** for the full reviewable list of all emails.

## Contents

- **21 campaigns** (root): weekly rotation, seasonal, new-program launches, lifecycle (welcome + win-back)
- **`Resource Articles/`** - 39 emails, one per live `/resources` guide
- **`Compare Articles/`** - 7 emails, one per live `/compare` page
- **`loan-calculator.html`** - interactive investor loan calculator (prototype)
- **`index.html`** - review checklist of every email, with progress tracking

Every email is table-based, inline-styled, mobile-responsive, and carries the canonical footer, legal line, and a `{{{unsubscribe}}}` merge field for SendGrid.

## Deploy to SendGrid

Create one Dynamic Template per HTML file and paste the file as a version. `{{{unsubscribe}}}` resolves through a marketing unsubscribe group. In-email "Deal calculator" banners link to the live `usamortgage.net/calculators/*` pages.
