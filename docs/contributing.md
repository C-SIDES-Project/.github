# Small code and documentation changes

This guide covers routine changes within our team: fixing a bug, adjusting an existing workflow, or updating instructions. Keep each change focused so it is easy to check and review.

For a bug or workflow adjustment, use the [issue and board workflow](issues.md) to record what needs changing. A typo or broken link can go straight to a pull request.

## 1. Make a branch

A branch keeps your edits separate from the shared version until they have been reviewed. Run these commands from the repository you are changing, after saving any existing work. Use `git status` to check for uncommitted changes first.

```sh
git status
git checkout main
git pull --ff-only origin main
git checkout -b fix/short-description
```

Choose a name that describes the change, such as `fix/tide-file-path` or `docs/clarify-settings`. Make your commits on this branch rather than directly on `main`.

For a small documentation edit, you can also use the pencil icon on GitHub. When saving, choose to create a new branch and open a pull request.

## 2. Edit and check

Make the change and check the affected step. For code, run the relevant test or a small example analysis and inspect the result. For documentation, check the instructions and links. Update the instructions if the change affects how someone runs the workflow.

Review your edits in your editor and stage the intended files. Replace the example filename below with the file you changed; add more filenames if needed.

```sh
git add path/to/changed-file
git commit -m "Fix tide input file path"
git push -u origin fix/short-description
```

Keep API keys, credentials, local data, and generated analysis outputs out of the commit. The repository's `.gitignore` lists files and folders Git should leave out, such as `.env`, caches, and generated outputs. Check it before adding files, and add any missing entries relevant to your work. Ignore rules only apply to files that Git is not already tracking.

## 3. Open a pull request

A pull request lets another team member review your branch before it is merged into `main`.

1. On GitHub, open a pull request from your branch into `main`.
2. Briefly describe what changed, why, and how you checked it. Link the issue if there is one, and mention anything you could not check.
3. Request review from `@phillipjws` or the team member responsible for the affected code.
4. Make any requested edits on the same branch and push them; the pull request updates automatically.
5. After approval and any required checks pass, merge the pull request. **Squash and merge** is preferred. Delete the branch after merging.

Record the outcome in the related issue and update its board card. If Git reports a conflict or the change starts affecting more of the analysis than expected, discuss it with Phillip before continuing.

Questions can be directed to Phillip Steeves at [phillip.steeves@nrcan-rncan.gc.ca](mailto:phillip.steeves@nrcan-rncan.gc.ca) or [@phillipjws on GitHub](https://github.com/phillipjws).
