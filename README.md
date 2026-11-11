# Little Research Lab — private prototype

## Run it
Open `index.html` in a modern browser. No installation or server is required.

## Included
- Editable baby birth date and selected calendar date
- Age-window scheduling calculated from birth date
- Search, research-area, age-window and status filters
- Sorting by start date, age, duration, title and category
- Experiment guide pages with research question, measures, materials, preparation, steps, observations, caveats and references
- Preparation checklists, completion status, observation notes and a calendar view
- Browser-local persistence using localStorage

## Important privacy limitation
This is a local prototype, not a deployed private website. Records remain in the browser profile on this device. There is no login, cloud database, encrypted clinical record, cross-device sync or backup. Do not enter sensitive information about your baby or upload identifying images. Export/backup is not yet implemented.

## Before private deployment
Set up a private Git repository, deploy to a hosting provider, create a Supabase project with row-level security and private storage, configure authentication for a single approved account, and add export/delete controls. Review security rules before entering personal baby data.

## Scientific note
The library contains research-inspired home adaptations, not validated developmental tests. Age ranges are approximate. Some tasks are deliberately marked exploratory. Read each limitation and stop if your baby is tired, distressed or uninterested.
