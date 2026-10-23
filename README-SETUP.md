# Hammad Shaikh — PhD Research Portfolio (al-folio content pack)

This is a **content/customisation pack** for the [al-folio Jekyll academic website](https://github.com/alshedivat/al-folio), not a full copy of the upstream repository. Create your site from the al-folio template first, then copy the relevant files/folders from this pack into your repository.

## Recommended GitHub Pages URL
Your site will be `https://YOUR-GITHUB-USERNAME.github.io/`. The GitHub repository must be named exactly `YOUR-GITHUB-USERNAME.github.io`. Replace all `YOUR-GITHUB-USERNAME` placeholders before deploying.

## Setup
1. Open https://github.com/alshedivat/al-folio and click **Use this template** → **Create a new repository**.
2. Name the repository `YOUR-GITHUB-USERNAME.github.io` (replace with your actual GitHub username).
3. Download/extract this pack. Copy its `_pages`, `_projects`, `_bibliography`, `_data`, and `assets` folders into your new repo, merging with existing folders. Copy `_config-personal-snippet.yml` values into your existing `_config.yml`; **do not replace the whole upstream `_config.yml`**.
4. Replace placeholders such as `YOUR-GITHUB-USERNAME`, `YOUR-EMAIL`, and `YOUR-LINKEDIN-URL`.
5. Add your real profile photo as `assets/img/prof_pic.jpg` if desired. Do not leave the placeholder SVG as a profile photo.
6. Check all claims and dates, add verified publications and links, and remove any section that you cannot substantiate.
7. In GitHub: **Settings → Actions → General → Workflow permissions → Read and write permissions → Save**.
8. Push/commit to `main`; check **Actions** for the deploy workflow.
9. In **Settings → Pages**, choose **Deploy from a branch** and select `gh-pages` / root after the workflow creates that branch.
10. Visit `https://YOUR-GITHUB-USERNAME.github.io/`.

For a local preview, follow the current upstream al-folio instructions. The recommended path is Docker:
```bash
docker compose pull
docker compose up
```
Then open `http://localhost:8080`.

## Portfolio structure
- About / research statement
- Selected research and engineering projects
- Publications and thesis (only the thesis record is currently included; verify its public URL and metadata)
- Teaching and mentoring
- CV link placeholder
- Contact and professional links

## Important content notes
- Do not label the master's thesis as a peer-reviewed journal/conference publication unless it has been published as one.
- Add only papers, preprints, talks, awards, and certifications that you can verify.
- Avoid publishing confidential utility diagrams, network maps, vulnerabilities, asset identifiers, or operational data. Describe work at a high level and obtain employer approval for any non-public details.
- The source repository is public by default if you publish it publicly. Keep personal contact information to an email address you are comfortable publishing.
