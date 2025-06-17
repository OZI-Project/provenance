# OZI Provenance

Provenance workflow for OZI tooled projects.

## Inputs

Expects an artifact with a directory ``dist/`` containing the subjects to attest provenance of.

* release-tag - release tag to upload provenance to (required)

## Permissions

Requires the following:

```yaml
permissions:
  id-token: write  # to authenticate with github
  attestations: write  # to create attestations
  contents: write  # to upload to releases
```
