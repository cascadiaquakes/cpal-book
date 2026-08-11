# Compilation Contribution Instructions

## Requirements

To contribute your paleoseismology data compilation to the CRESCENT CPAL Viewer, please first make sure your compilation meets the following requirements:

- **Study Area Requirement**: The majority of the records must fall within the CRESCENT geographic footprint (latitude: 39° to 52°, longitude: -130° to -116°) or be completely contained within it. If your compilation covers a larger region, you are welcome to submit a subset that falls within this range.
- **Peer-reviewed**: All records must be drawn from peer-reviewed publications with associated DOIs. Please include a bibliography linking each record to its source publication.
- **Geographic Data**: Each record must include at minimum a latitude/longitude, a record type (coastal deformation / marine shaking / terrestrial shaking / tsunami), and a source citation.

If your compilation meets the requirements above, please follow the steps in the sections below.

(compilation-metadata)=
## Compilation Metadata

Each compilation included in the CRESCENT CPAL Repository is described by a standard set of metadata fields that make it discoverable and comparable in the viewer.

### Required Fields (per record)

- **RECORD TYPE:** One of `coastal_deformation`, `marine_shaking`, `terrestrial_shaking`, `tsunami`.
- **LATITUDE / LONGITUDE:** Record location in decimal degrees, WGS84.
- **AGE / DATE:** Age estimate (calibrated years BP or calendar year), with reported uncertainty where available.
- **SOURCE PUBLICATION:** Full citation and DOI for the peer-reviewed study the record is drawn from.

### Optional Fields (per record)

- **SITE NAME:** Local place name or study-defined site identifier.
- **DATING METHOD:** Radiocarbon, luminescence, tree-ring, historical, etc.
- **UNCERTAINTY:** Formal age uncertainty (±years, 2-sigma) if reported by the source.
- **INTERPRETED EVENT:** If the record has been attributed to a specific paleoearthquake or paleotsunami, its identifier (e.g. "T1", "1700 CE Cascadia").
- **NOTES:** Any additional context relevant to record users.

:::{admonition} Data format guidance
:class: tip
Records should be submitted as GeoJSON `FeatureCollection` files with one feature per record. Each feature's `properties` object should carry the fields above (case-sensitive keys). Source Excel and JSON manifest files may be included alongside the GeoJSON for archival purposes.
:::

## Step 1: Prepare your compilation

Your compilation should be submitted in **GeoJSON** format with one feature per record. If your original data lives in a spreadsheet, please export it to GeoJSON preserving the field names above; the source Excel file may be included alongside as an archival copy.

## Step 2: Prepare a Markdown file describing your compilation

Each compilation included in the CRESCENT CPAL Repository has a corresponding page describing the compilation in this JupyterBook. Use the template below to structure yours.

::::{admonition} Compilation Markdown Template
:class: dropdown

````markdown
# {Compilation Name}

## {One-line description of the compilation}

{Author list of the compilation, or "Compilation curated by ..."}

[![DOI](https://img.shields.io/badge/DOI-{DOI_URL_ENCODED}-blue)](https://doi.org/{DOI})

In the DOI badge URL, replace `/` with `%2F` (URL encoding).

:::{figure} ./{figure_filename}.jpg
:label: fig:{short_label}

{Figure caption describing the compilation, region, time span, and record types included.}
:::

## Abstract

{Overview describing the compilation, the paleoseismic evidence it captures, and its scientific context.}

## Compilation Information

- **RECORD TYPES:** {coastal_deformation, marine_shaking, terrestrial_shaking, tsunami}
- **REGION:** {Region spanned by the compilation}
- **TIME SPAN:** {YYYY BP to YYYY BP or YYYY CE to YYYY CE}
- **NUMBER OF RECORDS:** {integer}
- **DATING METHOD(S):** {radiocarbon, luminescence, tree-ring, historical, etc.}
- **UNCERTAINTY REPORTING:** {how ages and locations are qualified}
- **SOURCE STUDIES:** {number of underlying peer-reviewed studies}
- **NOTES:** {optional}
````

::::

## Step 3: Submit your compilation to the repository

- **Submission Request**: Visit the <a href="https://github.com/cascadiaquakes/CRESCENT-CPAL/issues" target="_blank">CRESCENT-CPAL GitHub Issue Page</a> and create a submission request.
  - Your request must include a **publicly accessible download link** to your compilation file (GeoJSON). **Do not attach data files directly** to the issue.
  - Your request must include a download link to your Markdown file containing the compilation description.
  - Your request must include your contact information so we can get in touch if we have questions and notify you once your compilation is included in the viewer.
