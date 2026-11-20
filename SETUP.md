# Publish your GitHub profile README

## 1. Create the profile repository

1. Open https://github.com/new
2. Set the repository name to **artushbagratunyan** (exactly the same as your GitHub username).
3. Set visibility to **Public**.
4. Initialize it empty (do not add a README, license, or `.gitignore` because this starter already contains the files).
5. Create the repository.

## 2. Upload these files

Upload the *contents* of this starter folder to the root of the new repository:

- `README.md`
- `assets/hero.svg`
- `.github/workflows/snake.yml`

You can upload them in GitHub's web interface or push them with Git.

## 3. Enable workflow write permission

In the new repository, open **Settings → Actions → General → Workflow permissions** and select **Read and write permissions**, then save.

## 4. Generate the contribution snake

1. Open the repository's **Actions** tab.
2. Select **Generate contribution snake**.
3. Click **Run workflow**.
4. After the run succeeds, GitHub creates/updates the `output` branch with the animated SVG.
5. Refresh your GitHub profile. The README embeds the SVG from that branch.

The workflow also runs once per day automatically. The first run may take a minute or two.

## Notes

- GitHub Stats, top languages, streaks, and the activity graph are external image services. They may take a short time to load or occasionally be rate-limited.
- Stats only reflect activity and repositories visible to the public GitHub profile.
- The README intentionally describes your tools as technologies you have worked with or are learning; it does not claim expert-level proficiency.
