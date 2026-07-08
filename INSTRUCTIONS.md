# How to Upload This to Your GitHub Profile (Start Fresh)

## Step 1 — Delete everything in the existing repo
1. Go to `https://github.com/mohannaik21/mohannaik21`
2. Delete `README.md`, `INSTRUCTIONS.md`, `banner.png`, `banner.svg` (open each file →
   click the trash/delete icon → commit).
   *(Or just delete the whole repo and recreate it — see Step 2.)*

## Step 2 — Recreate (or reuse) the special repo
- Repo name must be exactly: `mohannaik21`
- Visibility: **Public**
- If recreating: check **"Add a README file"** when creating it.

## Step 3 — Upload these 4 files, flat, no folders
This version has **no `assets/` subfolder** — everything sits directly in the
repo root, which avoids the exact problem you just hit (GitHub's drag-and-drop
upload doesn't reliably keep folder structure).

```
mohannaik21/              <- repo root
├── README.md
├── banner.png
├── banner.svg             (optional — kept for later editing, not required)
└── INSTRUCTIONS.md         (optional — just for your reference)
```

**To upload:**
1. Open your repo → click **Add file → Upload files**
2. Drag in all 4 files directly (not inside a folder) — same screen
3. Scroll down, add a commit message like "Add profile README"
4. Click **Commit changes**

## Step 4 — Verify
1. Wait ~30 seconds for GitHub to process the commit
2. Go to `https://github.com/mohannaik21/mohannaik21` and check the README
   preview shows the banner image (not a broken-link icon)
3. Visit `https://github.com/mohannaik21` — your profile page should now show
   the banner, subtitle, and the three buttons

## If the banner still doesn't show
Open this exact URL in your browser:
```
https://raw.githubusercontent.com/mohannaik21/mohannaik21/main/banner.png
```
- If it shows the image → the README path is still wrong somewhere, double-check
  for typos or extra folders.
- If it 404s → `banner.png` wasn't actually committed to the repo; re-upload it.

## Notes
- The GitHub Stats section (`github-readme-stats` / `github-readme-streak-stats`)
  pulls live from third-party public services — those can occasionally be slow
  or briefly down, which is unrelated to your file upload. If one of those two
  cards doesn't load, just refresh the profile page after a minute.
