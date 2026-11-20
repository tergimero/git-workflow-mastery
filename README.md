x# Git Workflow and Basic Commands Mastery
A practical project demonstrating Git version control, branching, merging and GitHub collaboration.

## Branching Strategy

The main branch contains stable project code. Feature branches are used to develop changes independently before merging them into main.

Branches created:
- feature/add-greeting
- feature/add-project-info

## Merge Conflict Resolution

A merge conflict occurred in src/app.py when both main and feature/add-greeting modified the same code.

I resolved the conflict manually by removing the conflict markers and combining the main branch welcome message with the new greeting function.

The resolved application was tested successfully using Python.

## GitHub Collaboration

I created and merged Pull Request #1 using the feature/add-project-info branch.

Pull Request:
https://github.com/tergimero/git-workflow-mastery/pull/1

## Version Release


Version v1.0.0 was created using an annotated Git tag and published as a GitHub Release.

Release:
https://github.com/tergimero/git-workflow-mastery/releases/tag/v1.0.0
