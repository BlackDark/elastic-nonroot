# Elastic images fully nonroot

This repository just rebuilds existing elastic images and remove the `GID` requirement of `0`.
Default `UID` and `GID` is `1000`.

You can see which images and version will be released here: [Workflow](./.github/workflows/release.yml)
