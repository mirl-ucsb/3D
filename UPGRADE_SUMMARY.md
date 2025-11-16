---
layout: default
title: Upgrade Summary
---

## Upgrade Summary
- **From:** 0.4.2-beta
- **To:** 0.4.3-beta
- **Date:** 2025-11-16
- **Automated changes:** 4
- **Manual steps:** 1

## Automated Changes Applied

### Other (4 files)

- [x] success
- [x] changes
- [x] warnings
- [x] errors

## Manual Steps Required

Please complete these after merging:

1. Update your GitHub Actions build workflow file: This update adds smart detection so IIIF tiles automatically regenerate when you change _config.yml settings. Without this update, you would need to manually regenerate tiles after config changes. (1) Open this link in a new tab: https://raw.githubusercontent.com/UCSB-AMPLab/telar/main/.github/workflows/build.yml (2) Select all the text (Ctrl+A on Windows/Linux, Cmd+A on Mac) and copy it (Ctrl+C or Cmd+C) (3) Go to your GitHub repository and click on the .github/workflows/build.yml file (4) Click the pencil (Edit) icon in the top-right corner (5) Select all the existing content in the editor and delete it (6) Paste the new content you copied in step 2 (7) Scroll to the bottom and click the green "Commit changes" button to save. Note: GitHub Actions workflow files only take effect once they are committed to your repository, which is why this manual step is necessary. ([guide](https://raw.githubusercontent.com/UCSB-AMPLab/telar/main/.github/workflows/build.yml))

## Resources

- [Full Documentation](https://ampl.clair.ucsb.edu/telar-docs)
- [CHANGELOG](https://github.com/UCSB-AMPLab/telar/blob/main/CHANGELOG.md)
- [Report Issues](https://github.com/UCSB-AMPLab/telar/issues)
