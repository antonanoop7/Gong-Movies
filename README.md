# Gong Moviees website

## Files
- `index.html` – the whole site
- `images/` – logo and posters

## Publish with GitHub Pages
1. Create a repository on GitHub (e.g. `gong-moviees`).
2. Upload `index.html`, `README.md` and the `images` folder, then click **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch*, branch `main`, folder `/ (root)` → Save.
4. The site goes live at `https://<your-username>.github.io/gong-moviees/`.

## Editing the site
1. Open `index.html` on GitHub and click the pencil icon (Edit).
2. Change the text, then click **Commit changes**. The live site updates in about a minute.

- **Upcoming films:** search for `COMING UP`. Each film starts with a `<!-- FILM: ... -->` comment. Change the title, release date, director and cast there.
- **Ticket links:** replace `Tickets coming soon` with a link, e.g. `<a href="https://www.trybooking.com/XXXX">Book tickets</a>`.
- **New poster:** **Add file → Upload files** into `images/`, then update the `src="images/..."` for that film.
- **Past events:** search for `Past events` and copy one `<figure>...</figure>` block for each new event.
