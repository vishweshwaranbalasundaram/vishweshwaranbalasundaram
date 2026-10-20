# Apply the profile README refresh

The online update attempt was rejected by GitHub with HTTP 403, so these files have **not** been pushed automatically.

This is the special GitHub profile repository, not your Attend-IQ project:

`https://github.com/vishweshwaranbalasundaram/vishweshwaranbalasundaram`

## Option A — GitHub website

1. Download and extract `profile-readme-refresh.zip`.
2. Open the profile repository linked above.
3. Upload the new `README.md` to the repository root, replacing the current README.
4. Upload `assets/profile-banner.svg` preserving the `assets/` directory path.
5. Commit the changes on `main`.
6. Open the profile in a fresh browser tab and confirm the local banner appears.

## Option B — local Git clone

Copy `README.md` and the `assets` folder from this bundle into the root of a local clone of `vishweshwaranbalasundaram/vishweshwaranbalasundaram` (not into `Attend-IQ`). Then run:

```powershell
git status
git add README.md assets/profile-banner.svg
git commit -m "docs: curate profile README with verified projects"
git push origin main
```

Only run these commands from the profile repository after checking `git remote -v` points to `vishweshwaranbalasundaram/vishweshwaranbalasundaram.git`.

## Included files

- `README.md` — revised profile content; removes rate-limited stats cards and unverified demo links.
- `assets/profile-banner.svg` — locally stored banner to avoid the broken external banner image.
- `AUDIT.md` — findings and evidence used to decide which projects to feature.
