# RADAR-base Analytics Catalogue

This is a collection of reusable analytics pipelines for loading, processing and featurizing RADAR-base datasets.

You may add new pipelines 


Most pipelines will consume RADAR-base data directly and this functionality is provided using [RADAR-base pipeline]() use this as the basis for creating new pipelines. Instructions are provided in the README and Wiki of that repository.
 - [RADAR-base Pipeline README](https://github.com/RADAR-base/radarpipeline)
 - [RADAR-base Pipeline Wiki](https://github.com/RADAR-base/radarpipeline/wiki)


# Creating Citable Analytics Pipelines
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
  orcid: ""
title: "Mock Features"
version: 1.0.0
doi: 10.5281/zenodo.7248672
date-released: 2022-10-25
url: "https://github.com/RADAR-base-Analytics/mockfeatures"
```

Zenodo DOI URLs will automatically get created for any analytics repository in this Github Organisation (please email radar-base@kcl.ac.uk for your DOI) or you may manage this with your own Zenodo account.

