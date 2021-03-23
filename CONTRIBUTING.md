# Contributing

We love to collaborate! To share ideas, ask interactive questions, or just brainstorm, feel free to reach out to [the maintainers](MAINTAINERS.md) on chat (Teams channel #xyz). For more formal questions and bugs, you might want to [open an issue](./issues). For more ambitious contributions (or if you just have a simple fix to offer), a pull request is probably best.

## PR mechanics

### Simple way (for contributions that aren't code)
1. In github, browse to the doc you want to change.
2. Click the edit icon and make your changes directly in the online editor.
3. Scroll to the bottom of the editor window. Tick the radio button that says "Create a new branch for this commit and start a pull request."
4. Click "Commit Changes."

### Fancy way (for code)
If a PR is substantial, you may want to socialize it ahead of time by [opening an issue](./issues). This will help you get early guidance from the team. It's also a good idea to review [the backlog](link to issues query for backlog), [the roadmap](link to roadmap doc), and our [component documentation](link to other docs) for context. Once you're confident of how to frame your contribution:

1. Clone the repo (forking is disabled; you must make a direct clone).
2. Create a local branch named according to your contribution (e.g., `fixdiagram` or `add-revocation-feature`)
3. Review our [code review checklist](code-review.md). Also, [build and test locally](local-review.md) to confirm that your contribution leaves the repo in a good state.
4. Push and then raise a PR from your branch to `main`. (If you don't have privileges to do this, email a git patch to the [maintainers](MAINTAINERS.md) instead.)

Note [the license](LICENSE.md) on this repo. All contributions need to preserve the essential characteristics of the license. For example, internal code should never depend on open source with a copyleft license -- and documents should not include images that are not reusable.
