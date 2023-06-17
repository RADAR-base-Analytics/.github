# RADAR-base Analytics Catalogue

This is a collection of reusable analytics pipelines for loading, processing and featurising RADAR-base datasets.

You may add new pipelines and publish them here:

# See Documentation in the Main Repo `radarpipeline`
Most pipelines will consume RADAR-base data directly and this functionality is provided using [RADAR-base pipeline]() use as the basis for creating new pipelines. Instructions are provided in the README and Wiki of that repository.
 - [RADAR-base Pipeline README](https://github.com/RADAR-base/radarpipeline)
 - [RADAR-base Pipeline Wiki](https://github.com/RADAR-base/radarpipeline/wiki)


# Creating Citable Analytics Pipelines
A Zenodo community page for analysis pipelines can be found [here](https://zenodo.org/communities/radar-base-analytics/?page=1&size=20) we will aim to curate this community page with repositories added to the RADAR-base Analytics catalogue (this org).

**For more information on getting Zenodo DOIs and your pipelines citable see instructions here: [Creating Citable Piplines](https://github.com/RADAR-base/radarpipeline/wiki/Creating-Citable-Analytics-Pipelines)**

Citable Zenodo DOI URLs will automatically get created for any analytics repository in this Github Organisation whenever you create a new release. When you create a new analytics repo, add a `CITATION.cff` file then create a pull request and tag `@afolarin` and `@Hsankesara` to review (and tag in the PR description `@RADAR-base-Analytics/pipeline-catalog-admins`) and publish it on the Zenodo community. Next, create a release, this will then be picked up by Zenodo and a DOI will be created (e.g. 10.5281/zenodo.7248672), we will then add the DOI URL to the CITATION.tff). Lastly, add any relevant topics to the repository e.g. `data`, `feature-extraction` etc.
