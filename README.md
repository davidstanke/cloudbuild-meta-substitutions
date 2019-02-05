# cloudbuild-meta-substitutions
Demonstrate behavior of Cloud Build when a built-in substitution is passed to a custom substitution

### To run:
`gcloud builds submit --no-source`

Note that it is possible to [override some substitutions](https://cloud.google.com/cloud-build/docs/configuring-builds/substitute-variable-values#using_default_substitutions) at run time, which may be of use in some cases.