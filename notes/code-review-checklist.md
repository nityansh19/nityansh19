# Code Review Checklist

A short checklist for reviewing changes before they are merged or deployed.

## Correctness

- Does the change solve the intended problem?
- Are edge cases and failure states handled?
- Could this change break an existing flow?

## Readability

- Are names clear and consistent?
- Is duplicated logic avoidable?
- Are comments explaining decisions rather than obvious syntax?

## Frontend

- Check loading, empty, error, and success states.
- Check keyboard navigation and visible focus.
- Test responsive behavior on narrow and wide screens.

## Backend

- Validate incoming data.
- Return useful errors without exposing sensitive details.
- Keep secrets and credentials outside source control.

## Before merge

- Run relevant lint, tests, type checks, and builds.
- Remove temporary debug output.
- Review the final diff once without editing it.
