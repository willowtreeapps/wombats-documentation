# 03.13.2017

## Merge into Develop PR
* File the change under enhancement or bugfix under "DEVELOP"
* Submit a PR with CHANGELOG updates
* CHANGELOG updates should include a brief description, a link to your github, and a link to the ticket for the issue.

## Merge into QA PR
* Submit a PR with all feature/bugfix changes from develop into QA
* Push a change to the branch PR including a change to the CHANGELOG
* Move change content from "DEVELOP" to "QA"

## Merge into Master (Prod branch) PR
* Push a change to the branch PR including a change to the CHANGELOG
* Move change content from "QA" to "Master" in log.  
* Submit a PR with all changes in QA to merge into Master.

## Cutting a Release
* Submit a release PR on master with change to the project version number.
* Update CHANGELOG.md to move content under "Master" to a new release section
* Title the release section with `<release number> (date)`.
* Merge into master
* Cut release on github
