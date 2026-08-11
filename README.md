# CRESCENT Paleoseismology Repository (cpal-book)

MyST-based JupyterBook describing the paleoseismology data compilations included in the CRESCENT CPAL viewer and the compilation submission instructions.

Live site: https://cascadiaquakes.github.io/cpal-book/ (deployed on push to main)

## Local preview

```
npx --yes mystmd start
```

Then open the URL printed by `mystmd`.

## Structure

- `index.md` — repository landing page (Motivation, Scope, Repository Structure, Visualization, Metadata, Project Contacts, Acknowledgments).
- `compilations/` — one Markdown description page per data compilation. Populated by compilation authors; starter stubs are checked in.
- `submission.md` — compilation contribution instructions.
- `myst.yml` — table of contents and site configuration.

## Contributing

See the [Submission Instructions](https://cascadiaquakes.github.io/cpal-book/submission/) on the deployed site for the compilation contribution flow.
