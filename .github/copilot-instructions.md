# Repository instructions

## Issue hierarchy

This repository uses parent issues and sub-issues.

- A parent issue defines a feature, outcome, or larger body of work.
- A sub-issue defines an independently implementable work item.
- Detailed implementation work should normally be performed from a sub-issue.
- Do not attempt to implement an entire parent issue unless explicitly instructed.
- One sub-issue should normally result in one focused pull request.

## Before starting work

When assigned an issue:

1. Read the complete issue, including its requirements and acceptance criteria.
2. Determine whether the issue is a parent issue or a sub-issue.
3. If it is a sub-issue, read the linked parent issue for overall context.
4. Treat the assigned sub-issue as the implementation scope.
5. Review related sub-issues for dependencies, but do not implement them unless explicitly requested.
6. Identify any blocking dependencies before making changes.
7. Follow the existing repository structure, coding conventions, and implementation patterns.

## Working on a parent issue

When assigned a parent issue:

1. Review its expected outcomes, scope, and linked sub-issues.
2. Do not implement all sub-issues in a single change unless explicitly instructed.
3. Identify missing, duplicated, or incorrectly scoped sub-issues.
4. Use the parent issue to coordinate overall progress.
5. Do not mark the parent complete until all required sub-issues and feature-level validation are complete.
6. Do not close the parent issue solely because one sub-issue has been completed.

## Working on a sub-issue

When implementing a sub-issue:

1. Use its requirements and acceptance criteria as the source of implementation scope.
2. Use the parent issue for context, not as permission to expand the scope.
3. Do not make unrelated changes.
4. Do not implement sibling sub-issues unless explicitly requested.
5. Verify each acceptance criterion before marking it complete.
6. Update completed acceptance criteria from `- [ ]` to `- [x]`.
7. Do not mark a criterion complete if it has not been verified.
8. Run all applicable tests, builds, linting, and validation checks.
9. Document any criterion that cannot be completed or verified.
10. Create a focused pull request linked to the sub-issue.

## Pull requests

For each pull request:

1. Link the pull request to the sub-issue it implements.
2. Reference the parent issue for context where appropriate.
3. Summarise the implementation.
4. List the tests and validation checks performed.
5. Record assumptions, limitations, and follow-up work.
6. Identify any effect on sibling sub-issues.
7. Avoid including unrelated changes.
8. Do not claim that the parent feature is complete unless its full completion criteria have been verified.

## Development expectations

- Follow the existing repository structure and coding conventions.
- Prefer established implementation patterns already present in the repository.
- Do not introduce credentials, secrets, or environment-specific values.
- Add or update tests for changed behaviour.
- Keep changes focused on the assigned sub-issue.
- Record assumptions, limitations, and follow-up work in the pull request.