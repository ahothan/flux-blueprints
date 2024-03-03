# FLUX LEVEL 2 BLUEPRINTS REPOSITORY

This is an example of level 2 blueprints repository that contains deployment instructions for a small number of blueprints.
This repository is meant to be used by a Level 1 clusters repository where each target cluster is associated to 1 blueprint and a set of configuration variables.

All available blueprints are listed under /blueprints

## podinfo blueprint

This blueprint deploys the podinfo helm chart and allows a number of configuration variables based on Flux substitution variables.
