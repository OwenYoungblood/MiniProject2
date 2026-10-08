# Reflection: druid-io_pydruid

**Project facts:** 891 commits, 200 authors, 2013-08 to 2025-10. Pattern: steady. Longest gap: 2014-10 to 2015-02 (5 months). Gaps of 3+ months: 4. Status: Active.

## Inactivity patterns
Activity is low but continuous: about 40 to 140 commits a year since 2013, with a bump in 2018 to 2020 (129, 137, 118) and a low of 22 in 2025. The four gaps of 3+ months are spread through the early years, so the project alternates between short bursts and quiet periods without ever stopping. One caveat is that the author count (200) is inflated by automated pull-request merge commits ("Merge <sha> into <sha>"), which are credited to each PR author. That also explains why the most recent commits are all merges.

## Was the longest gap easy or hard to interpret?
Moderately easy. GitHub showed no issues or pull requests during the gap at all: issues #11 and #16 were opened in Aug to Sep 2014 and the next item, PR #17, appeared in Mar 2015. So the project was completely idle, not just short of commits. What the data cannot show is why.

## Likely reasons for inactivity or recovery
My hypothesis is that the early maintainers considered the client good enough after the Sep 2014 burst of PRs (HyperUnique, having clauses, new query types) and nobody else was contributing. Recovery came from outside contributors: none of the 7 post-gap authors had committed before. They added context properties (PR #17), Python 3 support (May 2015) and limitSpec support (Jun 2015). This is a hypothesis from commit messages and issue/PR dates, not something the maintainers stated.
