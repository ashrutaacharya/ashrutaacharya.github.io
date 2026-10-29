# Ashruta Acharya

Static personal website for an academic/professional job-market year.

## Local Files

- `index.html`: homepage content and structure.
- `styles.css`: dependency-free responsive styling.
- `cv.pdf`: public CV. Use the version without personal phone number.
- `assets/ashruta-acharya.jpg`: public headshot from the George Mason University profile page.
- `AGENTS.md`: site brief and maintenance rules.

## Content Sources Used

- George Mason University profile: https://economics.gmu.edu/people/aachar3
- Becker Friedman Institute profile: https://bfi.uchicago.edu/people/ashruta-acharya/
- SSRN working paper page: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5360466
- GitHub profile: https://github.com/ashrutaacharya

## Publishing Notes

The website is published by GitHub Pages from the `main` branch of
`ashrutaacharya/ashrutaacharya.github.io` at https://ashrutaacharya.github.io/.
The `origin` remote points to this website repository. The separate GitHub profile
repository is retained as the `profile` remote.

After saving website edits, stage the files you changed, commit, and push. For example:

```sh
git add index.html styles.css
git commit -m "Update website"
git push origin main
```

Wait for the **pages build and deployment** workflow to finish in GitHub Actions,
then refresh the live website. Saving a local file or refreshing a browser does
not publish local changes.

The public CV is included as `cv.pdf` at the repository root. Stage that file
explicitly when updating it.
