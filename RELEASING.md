Releasing
=========

 1. Update the version in `Segment-Localytics.podspec` to a non-beta version.
 2. Update the `CHANGELOG.md` for the impending release.
 3. `git commit -am "Prepare for release X.Y.Z."` (where X.Y.Z is the new version)
 4. `git tag -a X.Y.Z -m "Version X.Y.Z"` (where X.Y.Z is the new version)
 5. `git push && git push --tags`
 6. `pod trunk push Segment-Localytics.podspec`
 7. Update the version `Segment-Localytics.podspec` to the next beta version.
 8. `git commit -am "Prepare next development version."`
 9. `git push`