# Twibbit

An open-source UX agent for bitcoin builders who direct AI agents. This repository is the public waitlist site and the research report behind it.

- `index.html` is the waitlist page.
- `research.html` is the research report: we ask 10 bitcoin builders how they really build.
- `assets/` holds the images.

It is a static site with no build step. Open `index.html` in a browser, or deploy the folder as it is (for example on Vercel).

## Status

Twibbit is being built right now, and the agent is not released yet. The page collects emails for a launch announcement.

## Waitlist form

The form posts to a Google Apps Script web app that appends the email to a Google Sheet. Set the web app URL in the `ENDPOINT` variable at the bottom of `index.html`.

Built by Mogashni, UX designer and researcher, in public.
