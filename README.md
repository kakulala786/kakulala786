## Failing dependency updates, fixed

I'm Syed Shahkar Kakakhail. I fix Dependabot and Renovate pull requests whose CI fails, so they can be merged.

When a new version breaks the build, a test, a lint check or the lockfile, the bot's pull request sits unmerged and
the next updates stack up behind it. I find out why, make the change the update needs, and send it as a pull request
that carries the evidence:

- the failing CI step, replayed before and after the change in a clean sandbox;
- the project's own tests, run on the change;
- an independent review of the fix, with edge-case tests.

The fixes are prepared with AI assistance, and I review each one before it is sent. I never
force-push or merge, and I never advertise in your repository.

**Got a pull request from me?** It's a free fix for your open-source project, with no strings attached. Merge it,
change it or close it, as you see fit.

**Your team's dependency updates keep failing?** I work on JavaScript and TypeScript (npm, pnpm, Yarn), Python, Go
and Rust projects with Linux CI. Your first merged fix is free.
[Open an issue here](https://github.com/kakulala786/kakulala786/issues/new) to get in touch.
