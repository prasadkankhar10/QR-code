# Department Rooms & Labs (GitHub Pages)

A clean, static site for showcasing department rooms and labs. Deployed via GitHub Pages.

## Structure
- `index.html` – Home with room cards
- `rooms/<room>/index.html` – Room pages (each has its own `style.css`)
- `assets/css/style.css` – Base site styles
- `assets/css/themes/*.css` – Optional theme overrides
- `assets/images/` – Logo and per-room images (create subfolders `room1`, `room2`, ...)
- `.nojekyll` – Ensures GitHub Pages serves files as-is

## Local preview
Open `index.html` in a browser, or serve locally with any static server.

## Add a new room
1. Duplicate an existing folder in `rooms/` (e.g., `room2`) and rename it.
2. Update page content (title, room number, equipment, capacity, faculty name).
3. Add images under `assets/images/<your room>/` and update image paths.
4. Add a card on `index.html` pointing to your new room folder.

## Notes
- Faculty names are now Indian figures for placeholders. Replace with real names anytime.
- The `_template.html` in `rooms/` is an internal template for creating new pages.
