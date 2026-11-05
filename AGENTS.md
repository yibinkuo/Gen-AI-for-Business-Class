# AGENTS.md — Rules for working on Yibin Kuo's personal site

These rules apply to any AI agent (Claude Code or otherwise) editing this folder.

## Source of truth
- The CV (`Yibin_CBS_Resume_8.1.2026.pdf`) is the source of truth for all content.
- Do not invent, embellish, or round numbers, titles, dates, employers, or achievements.
  If something is unclear in the CV, ask instead of guessing.
- Keep the CV's section order on the site: Education → Experience → Additional Information.
- Public profiles: LinkedIn https://www.linkedin.com/in/yibinkuo/ · GitHub https://github.com/yibinkuo

## Never publish
- Personal phone number (it is on the CV but stays off the website).
- Home address, date of birth, or any government ID numbers.
- Passwords, API keys, tokens, or any `.env` / credential files.
- Confidential client names or non-public client details beyond what the CV already states
  (the CV deliberately anonymizes clients, e.g. "Fortune 100 Insurance Client"; keep it that way).
- Salary, compensation, or offer details.
- Photos of other people, or anything about third parties (mentees, colleagues) beyond the CV text.
- The CV PDF itself, unless Yibin explicitly says to make it downloadable.

## Ask Yibin first before
- Pushing, committing to, or creating any GitHub repository, or enabling GitHub Pages.
- Publishing or deploying the site anywhere (hosting, artifacts, share links).
- Adding any personal information not already on the site (phone, photo, new projects, etc.).
- Changing content wording in ways that alter meaning, or adding new claims.
- Deleting or overwriting existing files.
- Adding third-party scripts, analytics, trackers, or external dependencies.
- Changing the overall color scheme, layout, or section order.

## Style
- **Vibe:** professional and casual — confident, warm, plain English. No buzzword stacking, no emojis in body copy.
- **Colors:** Columbia blue palette.
  - Columbia blue `#B9D9EB` (accents, tiles, highlights)
  - Navy `#012169` (headings, text accents)
  - Mid blue `#1D4F91` (links, buttons)
  - Off-white background `#F7FAFC`, ink text `#1A2433`
  - Support dark mode via `prefers-color-scheme`.
- **Navigation:** streamlined — one sticky top bar with section links, plus quick-jump tiles at the top.
  No dropdowns, no more than ~5 nav items.
- **Typography:** one clean sans-serif (Inter via Google Fonts, system fallback). Generous whitespace.
- **Tech:** a single static `index.html` with inline CSS and minimal vanilla JS. No frameworks or build step.
- **Accessibility:** semantic HTML, sufficient contrast, visible focus states, works at phone width with no horizontal scroll.
- **Writing:** keep CV bullets verbatim or near-verbatim; use bold sparingly to highlight key metrics.
