# CRESCENT Paleoseismology Repository and Viewer

The <a href="https://cascadiaquakes.org">Cascadia Region Earthquake Science Center (CRESCENT)</a>  <a href="https://cascadiaquakes.github.io/cpal-book/">**Paleoseismology Repository**</a> and <a href="https://cpal.cascadiaquakes.org">**CPAL Viewer**</a> is a community resource for the collection, documentation, and dissemination of peer-reviewed paleoseismology data compilations within the Cascadia Subduction Zone and surrounding regions. The repository is designed to support reproducible earthquake science by providing standardized access to curated records of past earthquake activity captured in coastal, marine, and terrestrial deposits.

This effort is part of the broader mission of CRESCENT to advance understanding of earthquake science in the Pacific Northwest through open science, community data curation, and shared cyberinfrastructure.

## Motivation

Paleoseismology data underpin our understanding of the timing, size, and recurrence of past great earthquakes and tsunamis along the Cascadia Subduction Zone. Coastal deformation records, marine turbidites, terrestrial evidence of shaking, and tsunami deposits together constrain the long-term behavior of the subduction zone at time scales far beyond the historic seismic record.

However, these data are often:
- Distributed across individual publications, agency reports, and archived spreadsheets,
- Produced using heterogeneous formats, conventions, and metadata,
- Difficult to discover, compare, or reuse across studies.

The CRESCENT CPAL Repository addresses these challenges by providing:
- A centralized, openly accessible collection of peer-reviewed paleoseismology compilations,
- Consistent documentation describing how each compilation was assembled and which uncertainties are captured,
- A visualization tool that permits comparison across compilations in map view, download in standardized formats, and inspection of the underlying records.

## Scope

We welcome paleoseismology data compilations describing evidence of past earthquakes and tsunamis in the Cascadia region. Four broad categories are currently in scope:

- **Coastal Deformation** records (e.g. buried soils, marsh subsidence, uplifted terraces),
- **Marine Shaking** records (e.g. turbidites in continental slope basins, seismically-triggered submarine landslides),
- **Terrestrial Shaking** records (e.g. liquefaction features, disturbed lake sediments, tree-ring evidence),
- **Tsunami** records (e.g. tsunami sand sheets, run-up elevations, distal tsunami deposits).

The only requirements are that any compilation submitted for inclusion into the repository:
- Is primarily located within the **CRESCENT geographic footprint** (Cascadia), and
- Draws from **peer-reviewed publications** with associated DOIs.

## Repository Structure

Each compilation included in the repository consists of:
1. A downloadable data file in a standardized format (GeoJSON, plus source Excel and JSON manifests), and
2. A corresponding **Markdown description page** (rendered into this JupyterBook) covering the underlying publications, methodology, geographic extent, and known caveats.

Description pages follow a standardized Markdown template to ensure clarity and consistency while allowing contributors to highlight the unique aspects of their compilation.

## Visualization

Compilations hosted in this repository are integrated into the <a href="https://cpal.cascadiaquakes.org" style="color:#6fa8dc; font-weight:bold;">**CRESCENT CPAL Viewer**</a>, enabling interactive exploration of paleoseismic records in map view with filtering by record type, time period, and source study. The viewer supports download of the underlying data and is intended as a discovery and comparison tool that complements citation of the original peer-reviewed publications.

## Metadata

For a description of the record fields and other metadata please review the {ref}`compilation-metadata` section.

## Project Contacts

The CRESCENT Paleoseismology Repository is developed and maintained by the CRESCENT cyberinfrastructure team in collaboration with the broader Cascadia paleoseismology community. Individual compilations remain the intellectual property of their original authors.

**Amanda M. Thomas**  
amthom@ucdavis.edu  
Department of Earth and Planetary Sciences, University of California, Davis  

**William Marfo**  
wmarfo@ucdavis.edu  
Cascadia Region Earthquake Science Center    
Department of Earth and Planetary Sciences, University of California, Davis

**Loïc Bachelot**  
lbachelo@uoregon.edu  
Cascadia Region Earthquake Science Center  
Department of Earth Sciences, University of Oregon


## Acknowledgments

This project is supported by the **National Science Foundation** through the Cascadia Region Earthquake Science Center (CRESCENT).
