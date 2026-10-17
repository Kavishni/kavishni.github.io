# kavishni.github.io

This is the Quarto source for Kavishni Nanayakkara's personal website.

## Beginner workflow

The repository uses one permanent source branch, `main`. Website changes are
made on short-lived branches and merged through pull requests. GitHub Actions
builds and publishes the site automatically after a pull request is merged
into `main`.

### Make a change

From the repository folder:

```bash
git switch main
git pull origin main
git switch -c describe-your-change
quarto preview
```

Edit the Quarto, Markdown, or CSS files while the preview is running. Press
`Ctrl+C` in the Terminal when you are finished previewing.

Save and upload the branch:

```bash
git add .
git commit -m "Describe the change"
git push -u origin describe-your-change
```

On GitHub, open a pull request from `describe-your-change` into `main`. Check
the changed files and wait for the `Build website` check to pass. Merge the
pull request when the change is ready to publish. The deployment then appears
under the repository's **Actions** tab.

After the pull request is merged, delete the temporary branch on GitHub. For
your next change, start again from the latest `main`.

### Branch roles

| Branch | Purpose |
| --- | --- |
| `main` | Approved Quarto source and deployment trigger |
| Temporary branches | Individual changes awaiting review |
| `gh-pages` | Legacy generated output; do not edit or publish to it |

The live site is deployed from the `_site/` artifact created by GitHub
Actions. You do not need to run `quarto publish gh-pages`.
