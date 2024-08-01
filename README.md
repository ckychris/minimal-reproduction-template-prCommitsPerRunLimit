# minimal-reproduction-template

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Renovate still set Commit limit = 3, but it opens unlimited amount of PRs.

## Expected behavior

"prCommitsPerRunLimit" limits the amount of commits each run creates.

When "prCommitsPerRunLimit" is set to 3, it should create maximum 3 commits.

## Link to the Renovate issue or Discussion

Put your link to the Renovate issue or Discussion here.
