# CRESCENT Paleoseismology Repository Book

[![License: BSD-3-Clause](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)

Documentation for the paleoseismology data compilations included in the CRESCENT CPAL viewer, and instructions for submitting new compilations.

**Read the book:** https://cascadiaquakes.github.io/cpal-book/
**Viewer:** https://cpal.cascadiaquakes.org

---

## Contents

- **Home**: motivation, scope, repository structure, visualization and metadata
- **Data Compilations**: one description page per compilation (`compilations/`)
- **Submission Instructions**: how to contribute a compilation (`submission.md`)

---

## Building Locally

The book is built with [MyST](https://mystmd.org). With Node.js installed, run from the repository root:

```bash
npx --yes mystmd start
```

Then open the URL it prints.

---

## Deployment

GitHub Actions builds the book on every push to `main` and publishes it to GitHub Pages.

---

## Contributing

See the [Submission Instructions](https://cascadiaquakes.github.io/cpal-book/submission/) for how to contribute a compilation.

---

## License

This project is licensed under the BSD 3-Clause License. See [LICENSE](LICENSE).

---

## Contacts

**Software:**
- **Amanda M. Thomas**, University of California, Davis: [amthom@ucdavis.edu](mailto:amthom@ucdavis.edu)
- **William Marfo**, University of California, Davis: [wmarfo@ucdavis.edu](mailto:wmarfo@ucdavis.edu)
- **Loïc Bachelot**, University of Oregon: [lbachelo@uoregon.edu](mailto:lbachelo@uoregon.edu)

**Data:**
- **Tina Dura**, Virginia Tech: [tinadura@vt.edu](mailto:tinadura@vt.edu)
- **Lydia Staisch**, U.S. Geological Survey: [lstaisch@usgs.gov](mailto:lstaisch@usgs.gov)

For corrections or suggestions, please [open an issue](https://github.com/cascadiaquakes/cpal-book/issues).

---

## Acknowledgments

<table>
  <tr>
    <td align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/cascadiaquakes/.github/main/assets/crescent-circle.png" alt="CRESCENT Logo" width="150" />
    </td>
    <td align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/cascadiaquakes/.github/main/assets/nsf-logo.png" alt="NSF Logo" width="450" />
    </td>
  </tr>
</table>

This project is supported by the National Science Foundation through the Cascadia Region Earthquake Science Center (CRESCENT), Cooperative Agreement EAR-2225286.
