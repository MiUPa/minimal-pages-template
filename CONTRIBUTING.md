# Contributing

Thanks for improving the template.

## Choose the right workflow

- Want your own homepage: use `Use this template`
- Want to improve the template: use `Fork` and open a pull request

Repositories created from `Use this template` are independent repositories. They are good for personal sites, but they are not the right place to prepare pull requests back to this template.

## Contribution flow

1. Fork this repository
2. Create a branch for your change
3. Keep the change focused
4. Validate the edited files
5. Open a pull request to `main`

## What fits this project

- Improvements to layout, responsiveness, typography, and accessibility
- Better documentation for GitHub Pages or template usage
- Small structural additions that keep the project dependency-free

## What to avoid

- Adding a framework or build step unless there is a strong reason
- Turning the template into a large portfolio boilerplate
- Mixing unrelated design changes and documentation rewrites in one pull request

## Local checks

Run the checks that make sense for your change.

```bash
python3 -m http.server 8000
git diff --check
```

If you changed HTML structure, also make sure links are still relative so the template works on both user pages and project pages.

## Pull request notes

Include:

- What changed
- Why it improves the template
- Any visual or behavior changes people should review

If the idea came from a site repository that was created from this template, re-apply the minimal change in a fork of this repository before opening the pull request.
