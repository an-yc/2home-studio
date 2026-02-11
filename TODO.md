# 2home Website — To-Do List

## After Feb 20, 2025 — Next Update

- [ ] **Remove Chinese New Year banner**
  - Delete HTML: `index.html:1247-1250`
  - Delete CSS: `.cny-notice-banner` at `index.html:185-212`
  - Delete JS logic: `index.html:1472-1478`

- [ ] **Update Google review count**
  - Currently hardcoded as 5.0 / 24 reviews in two places:
    - Visible badge: `index.html:1433-1437`
    - Structured data: `index.html:121-125`
  - Check current rating and count on Google, update both places
  - Last updated: 2026-02-11

## Future — Set up Featurable (auto Google reviews)

- [ ] Sign up at [featurable.com](https://featurable.com) with the Google account linked to 2home's Google Business Profile
- [ ] Create a widget, copy the widget ID
- [ ] Add client-side JS to `index.html` that fetches from `https://featurable.com/api/v2/widgets/{widgetId}`
- [ ] Auto-update the badge rating + review count + structured data
- [ ] Free tier, updates every 24 hours, no Google API key needed

## Ongoing — Monthly

- [ ] Until Featurable is set up, manually check and update Google review rating/count each month
