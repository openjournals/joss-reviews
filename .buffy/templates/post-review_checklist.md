# Post-Review Checklist for Editor and Authors

## Additional Author Tasks After Review is Complete
- [ ] Double check authors and affiliations (including ORCIDs)
- [ ] Make a release of the software with the latest changes from the review and post the version number here. This is the version that will be used in the JOSS paper.  
- [ ] Archive the release on Zenodo/figshare/etc and post the DOI here.
- [ ] Make sure that the title and author list (including ORCIDs) in the archive match those in the JOSS paper.
- [ ] Make sure that the license listed for the archive is the same as the software license.

## Editor Tasks Prior to Acceptance
- [ ] Read the text of the paper and offer comments/corrections (as either a list or a PR)
- [ ] Check the references in the paper for corrections (e.g. capitalization)
- [ ] Check that the archive title, author list, version tag, and the license are correct
- [ ] Set archive DOI with ``@editorialbot set <DOI here> as archive``
- [ ] Set version with ``@editorialbot set <version here> as version``
- [ ] Double check rendering of paper with ``@editorialbot generate pdf``
- [ ] Specifically check the references with ``@editorialbot check references`` and ask author(s) to update as needed
- [ ] Recommend acceptance with ``@editorialbot recommend-accept``
