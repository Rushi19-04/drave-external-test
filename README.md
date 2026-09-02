# DRAVE External Test Repository

This is a test repository to validate the external customer integration with DRAVE GitHub Action.

## Structure

- `.github/workflows/drave-validation.yml` - GitHub Actions workflow that runs DRAVE detection validation
- `detections/` - Detection rules in YAML format

## Setup

To use this repository with DRAVE Action:

1. Add GitHub Secrets:
   - `DRAVE_API_BASE_URL`: The DRAVE API endpoint (e.g., https://api.drave.example.com)
   - `DRAVE_API_KEY`: Your DRAVE tenant API key

2. Commit and push detection rules to trigger validation

## Detection Rules

Rules in the `detections/` directory are automatically validated and synchronized to the DRAVE platform.
