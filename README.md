# Sportside

Sportside is a database-free front-end prototype for connecting young athletes
with trusted sports mentors.

## Included

- Responsive landing page and mobile navigation
- Sample mentor directory with search, filters, and sorting
- Mentor profile and introduction-request flows
- Session-only athlete request dashboard
- Mentor interest application
- Safety center and demo reporting flow
- Guardian email requirement for mentorship requests from users under 18

All people and profiles are fictional. Forms are intentionally not connected to
a database, authentication system, email service, or moderation workflow.
Requests exist only in JavaScript memory and disappear when the page refreshes.

## Run

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before a real launch

Add secure accounts and role-based access, a database, mentor identity and
background verification, guardian consent records, moderation and reporting
operations, protected messaging or session scheduling, privacy controls, and
legal/safeguarding review.
