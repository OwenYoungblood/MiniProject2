# Reflection: skuschel_postpic

**Project facts:** 1,229 commits, 21 authors, 2013-12 to 2025-03 (WoC). Pattern: declining. Longest gap: 2022-11 to 2023-08 (10 months). Gaps of 3+ months: 7. Status: Active (last GitHub commit 2026-06-08).

## Inactivity patterns
Postpic peaked in 2017 (526 commits), then dropped to 112 in 2018 and 137 in 2019, and has been at about 10 to 50 commits a year since 2020. Seven gaps of three months or more show how thin the activity is. Most work comes from one maintainer, so the timeline follows his available time.

## Was the longest gap easy or hard to interpret?
Fairly easy. GitHub showed PR #268 in Oct 2022 and then nothing until PRs #269 to #272 in Sep to Dec 2023, so the project was fully idle in between. After the gap the commits are a maintenance sweep: switching from nose to nose2, a `parse_version` bugfix, a CHANGELOG update and a versioneer update.

## Likely reasons for inactivity or recovery
My hypothesis is that the maintainer had other commitments and returned when dependencies broke, which is the kind of work the post-gap commits show. Recovery was by the same person (Stephan Kuschel). A new contributor did add features in Mar 2025 (an HDF5 export), so the project is not dependent on one person alone. This is an inference from the commit messages and PR dates, not something the maintainer said.
