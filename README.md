# GRPS Parent University

A family-first hub for Grand Rapids Public Schools families: learning at home, finding help, things to do around Grand Rapids, and enrollment. No account needed, with translation into many languages.

**Live site:** https://melatkins2-ops.github.io/parent-university/

## What's here

- `index.html`: the hub (Home, Learn, Find Help, Around Grand Rapids, About, Enroll)
- `reading-ideas.html`, `math-ideas.html`, `literacy-center.html`: learning at home
- `attendance-guide.html`: attendance guide for families
- `parenting-in-real-life.html`: parenting support
- `favicon.png`

## Good to know

- Logos are embedded directly in `index.html`, so they display whether the page is opened locally or on GitHub Pages.

## Updating the site

Edit the files on a branch and open a pull request. GitHub Pages publishes `main` automatically, usually within a minute or two of a merge.

## Automated site check

Every pull request and every push to `main` runs **Site check** (`.github/workflows/site-check.yml`). It opens the site in a headless browser at desktop (1366px) and phone (390px) widths and fails if the page throws a JavaScript error, a local file or image is missing, or the page scrolls sideways. See the Actions tab for results.

Maintained by GRPS Community & Student Affairs.
