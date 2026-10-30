# Ashruta Acharya

Static personal website for an academic/professional job-market year.

## Local Files

- `index.html`: homepage content and structure.
- `styles.css`: dependency-free responsive styling.
- `industry-resume.pdf`: public Industry Resume, with personal phone number omitted.
- `cv.pdf`: legacy CV retained for existing direct links.
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

The current public document is `industry-resume.pdf`, labeled **Industry Resume**
throughout the website. Stage that file explicitly when updating it, and keep
personal phone numbers out of public copies.

When the separate research CV is ready, add it as `research-cv.pdf` and label its
links **Research CV**. The existing `cv.pdf` is retained for legacy direct links.
