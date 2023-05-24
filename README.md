# Reproduction repository for Renovate issue 22389
## Current behavior
In this case, Renovate won't even open MRs for the branches, only the branches itself.

## Expected behavior
Renovate should open an individual MR for each version update while also applying the rules set in the `packageRules` configuration.
