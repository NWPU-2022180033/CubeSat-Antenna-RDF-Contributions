# CubeSat Antenna RDF Dataset Contributions

This repository is a community contribution portal for future updates of the CubeSat antenna RDF dataset.

The official dataset, RDF/Turtle file, GUI, and versioned releases are archived on Figshare. This GitHub repository is used only to collect and track new antenna-record suggestions from the community.

Contributors should not edit or submit RDF/Turtle files manually. New records should be submitted through the GitHub issue form using the same metadata fields used in the Excel-to-RDF workflow.

## Contribution workflow

1. A contributor submits a new CubeSat antenna record using the GitHub issue form.
2. The maintainers check the submitted information against the cited source paper.
3. Accepted records are added to the master Excel dataset by the maintainers.
4. The RDF/Turtle file is regenerated using the RDF creation script.
5. The regenerated RDF file is validated before release.
6. Updated dataset versions are archived on Figshare.
7. Update will be done Quarterly basis

## What information should be submitted?

Contributors should provide antenna metadata reported in the source paper, including reference description, frequency, antenna type, CubeSat type, band, polarization, gain, bandwidth, efficiency, radiation pattern, fabrication status, deployment status, and application.

If a value is not reported in the source paper, contributors should write:

`Not Found`

## Important note

This repository is not the official dataset archive. It is only used for community submissions and issue tracking. The official citable dataset versions are maintained on Figshare mentioned in the manuscript.
