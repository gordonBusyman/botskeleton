# Contributing
This document contains essential information on how to contribute work to this repository.

## Which Branch?
Pull requests should always be done against the `master` branch.

## Scope of the work
Do not mix work. Sometimes it may be tempting to do a bunch of tickets in just one branch or go in a code cleaning spree, but please don't.

Instead, create a branch for each ticket you are working on and work on them separately.

## Always be ahead of master, not behind
Make sure the branch you're working on is up-to-date with `master`.

Create the habit to `git pull` the latest work from `master` and `git merge master` into the branch you're working on, before pushing to `origin`.

## Committing to git
### Commit messages
Each commit **MUST** have a proper message describing the work that has been done.
This is called [Semantic Commit Messages](https://seesparkbox.com/foundry/semantic_commit_messages).

Here's what a commit message should look like:

```txt
fix(ValidHexColour): make sure validation doesn't break when passing an empty value
^-^ ^------------^   ^------------------------------------------------------------^
|   |                |
|   |                +-> Description of the work.
|   |
|   +------------------> Scope of the work.
|
+----------------------> Type: chore, docs, feat, fix, hack, refactor, style, or test.
```

### Commit often
Commits don't pay taxes, so they can be done often. Avoid doing large commits, specially if there's different work involved.

Instead, break your work in small commits, please avoid having unrelated features/fixes on the same commit).

## Branching strategy
We will be using a **branch-per-issue** workflow.

This means, that for each open issue, we'll create a corresponding **git** branch.


## Pull requests
When creating a pull request, add a proper description of the work being submitted for code review.

Use a list of checkboxes so that code reviewers can tell what has been finished and what is still in progress.

Add any other relevant information the reviewers might need in order to test your code, should they want to.

To make it easy, a [pull request template](.github/PULL_REQUEST_TEMPLATE.md) is provided in this repository.
