# Walking Water — Capillary Action Science Fair Project

This folder has everything for your daughter's science fair project:

1. **`Capillary_Action_Science_Fair_Project.docx`** — the full background reading, procedure, data tables, and reflection questions as a printable Word document/workbook.
2. **`Walking_Water_App.html`** — an interactive web app that walks her through the same project step-by-step, with a live timer, photo capture, an auto-generated graph, and a one-click printable packet at the end.

## Putting the app online with GitHub Pages (free, no coding needed)

1. Create a free GitHub account at github.com if you don't have one.
2. Click **New repository** (top right → "+" icon). Name it anything, e.g. `walking-water-project`. Set it to **Public**. Click **Create repository**.
3. On the new repo page, click **Add file → Upload files**, and drag in `Walking_Water_App.html`.
4. Rename the uploaded file to `index.html` (click the pencil/edit icon next to it, or upload it as `index.html` directly) — this makes it the default page.
5. Commit the change.
6. Go to **Settings → Pages** (left sidebar). Under "Build and deployment," set **Source** to "Deploy from a branch," branch `main`, folder `/ (root)`. Click **Save**.
7. After a minute, GitHub will show a link like `https://yourusername.github.io/walking-water-project/` — that's your daughter's live, shareable app. Bookmark it on whatever device she'll use for the experiment (phone is great, since it can take the photos too).

## How the app saves progress

Everything she types, checks, or photographs is saved automatically in that browser (using the browser's local storage), so she can close the tab and come back later on the *same device and browser*.

To continue on a **different device**, or as a backup, use the **Save file** button in the top right — it downloads a small `.json` file with everything she's entered. On the new device, open the app and click **Load** to pick that file back up exactly where she left off.

## Suggested workflow

- Do the **Reading** and **Hypothesis** sections together a day or two before the experiment.
- Start the **Experiment** section right when she's ready to set up the cups — that's when she presses **Start timer**.
- Check back at the prompted checkpoints (5 min, 15 min, 30 min, 1 hr, 2 hr, and the next morning) to log measurements and snap photos.
- Once the 24-hour data is in, she can fill out **Reflect** and then hit **Print my packet** on the last tab for a complete printout to assemble onto her display board.
