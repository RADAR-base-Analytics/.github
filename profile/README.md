# RADAR-base Analytics Catalogue

This is a collection of reusable analytics pipelines for loading, processing and featurizing RADAR-base datasets.

You may add new pipelines 


Most pipelines will consume RADAR-base data directly and this functionality is provided using [RADAR-base pipeline]() use this as the basis for creating new pipelines. Instructions are provided in the README and Wiki of that repository.
 - [RADAR-base Pipeline README](https://github.com/RADAR-base/radarpipeline)
 - [RADAR-base Pipeline Wiki](https://github.com/RADAR-base/radarpipeline/wiki)


# Creating Citable Analytics Pipelines
A Zenodo community page for analysis pipelines can be found [here](https://zenodo.org/communities/radar-base-analytics/?page=1&size=20) we will aim to curate this community page with repositories added to the RADAR-base Analytics catalogue (this org).

You may add citations to the RADAR-base pipeline using either or both the GitHub CITATIONS.cff file and the [Zenodo](https://zenodo.org/) badge.
 - [GitHub CFF File](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files )
 - [CFF website](https://citation-file-format.github.io/)
 - [CFF schema](https://github.com/citation-file-format/citation-file-format/blob/main/schema-guide.md)

You can add a CITATION.cff file to the root of a repository to let others know how you would like them to cite your work. The citation file format is plain text with human- and machine-readable citation information.

Example CITATION.cff file:

```cff
cff-version: 1.2.0
message: "If you use this software, please cite it as below."
authors:
- family-names: "Sankesara"
  given-names: "Heet"
  orcid: "https://orcid.org/0000-0002-9126-5615"
- family-names: "Patel"
  given-names: "Pushkar"
  orcid: "https://orcid.org/0000-0003-3410-8856"
title: "Mock Features"
version: 1.0.0
doi: 10.5281/zenodo.7248672
date-released: 2022-10-25
url: "https://github.com/RADAR-base-Analytics/mockfeatures"
```

Citable Zenodo DOI URLs will automatically get created for any analytics repository in this Github Organisation whenever you create a new release. When you create a new analytics repo, add a `CITATION.cff` file then create a pull request and tag `@afolarin` and `@Hsankesara` to review (and tag in the PR description `@RADAR-base-Analytics/pipeline-catalog-admins`) and publish it on the Zenodo community. Next create a release, this will then be picked up by Zenodo and a DOI will be created (e.g. 10.5281/zenodo.7248672), we will then add the DOI URL to the CITATION.tff). Lastly, add any relevant topics to the repository e.g. `data`, `feature-extraction` etc.
