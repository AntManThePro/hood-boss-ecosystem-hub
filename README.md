# Hood Boss | Ecosystem Hub

Role-filtered launchpad for the Hood Boss systems — KEC Training, Field Playbook, Team Lead OS, Team Lead Briefing, QA Brain, Service Manager OS, Cycle Gate, Follow-ups, Scorecard, and KEC Shield. Single-file app, zero external dependencies, no data stored.

Live: https://hood-boss-ecosystem-hub.netlify.app/

## How to use

1. Open the live site and pick your role — **Technician, Team Lead, QA Inspector, or Manager** — at the top.
2. The page shows only the systems meant for that role. Click a card to open it in a new tab.
3. Manager cards link to the private team-login sites — if one asks you to sign in, that's the site itself enforcing access, not this hub.

## Role filter is not authentication

The Technician / Team Lead / QA Inspector / Manager selector only changes which cards are shown. It is a view selector, not a gate — manager cards link to the private team-login sites, which enforce access themselves.

## Links verified

All 13 outbound links checked live on 2026-11-18: 12 return HTTP 200; Team Lead OS returns 401 by design (private Netlify Team login) and is linked as a directory entry for authorized users.

## Links

- Live site: https://hood-boss-ecosystem-hub.netlify.app/
- NEXUS World Hub: https://nexus-world-hub.netlify.app/
- Repo: https://github.com/AntManThePro/hood-boss-ecosystem-hub

DoubleA @ AntManThePro · NExtended Xperimental USers
