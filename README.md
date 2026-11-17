# Skate With Blake

Landing page and lesson booking flow for **Skate With Blake**, private and small-group hockey lessons with Coach Chris Blake on Pro-Time ice at Children's Health StarCenter Multisport Northlake (Northlake, TX).

**Live preview:** https://israelhockey.github.io/skate-with-blake/

## What's here

`index.html` is the full front end in one self-contained file.

- Landing page: lesson formats, skills, levels (Adult E League through travel), the rink and what to bring, FAQ
- 6-step booking flow: lesson type, player info, focus skills (up to 3), Northlake Pro-Time session (first pick + backup), contact and rink checklist, review
- Live request summary, saved draft, confirmation screen
- Responsive down to phone size, keyboard accessible, respects reduced motion

## Status

Front end only. The backend comes next.

- **Session times are sample data.** Replace `PRO_TIME_WEEKLY` / `getSessions()` with Blake's real Pro-Time schedule.
- **Rates** are blank until set in `LESSON_TYPES` (`price`).
- **Submitting** calls `submitRequest(payload)`, which currently logs the request JSON. Point it at the API when it's ready.
- Items marked `TODO(client)` need Chris's input: bio and photo, cancellation policy, rates.
