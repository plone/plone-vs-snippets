Develop and publishing notes
============================

to publish the extension in the Extension Market, follow this steps:

- make sure the CHANGELOG.md is up to date and has a release date set to the top most entry, which is UNRELEASED until then.
- check the version number in the package.json is set to the previous version number, not the new version!
- run this command with the new version number: vsce publish X.X.X