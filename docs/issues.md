# Issues and the project board

We use GitHub issues to record problems, proposed changes, questions, and analysis tasks. The existing [CoastSatCLI Kanban board](https://github.com/orgs/C-SIDES-Project/projects/1/views/1) shows what is planned, underway, and finished. Use the columns already on that board.

An **issue** holds the task description and discussion. Its **board card** shows progress. Keep the discussion in the issue so it stays with the work.

## 1. Choose the repository

| The issue concerns... | Open it in... |
| --- | --- |
| CoastSatCLI installation, GUI, pipeline, or outputs | [CoastSatCLI Issues](https://github.com/C-SIDES-Project/CoastSatCLI/issues) |
| PlanetScope imagery preparation, extraction, or analysis | [PlanetScopeCoastSat Issues](https://github.com/C-SIDES-Project/PlanetScopeCoastSat/issues) |
| Shared guidance, organization information, or coordination across projects | [.github Issues](https://github.com/C-SIDES-Project/.github/issues) |

Search existing issues, including closed ones, before opening a new one. If the same problem is already recorded, add your details there. For work spanning repositories, open the issue where the main work belongs and link related issues as needed.

## 2. Open the issue

1. Open the repository's **Issues** tab and select **New issue**.
2. Choose the form that fits: **Report a problem**, **Propose a change**, or **Ask a question**. A blank issue is also available for tasks that do not fit a form. If the project has its own templates, use those.
3. Give it a specific title, such as "Pipeline stops during tide correction" or "Explain PlanetScope transect input format".
4. Describe what you were trying to do and what happened, or what change you need and why. Add steps, settings, screenshots, or error text where useful. If the issue is an unexpected scientific result, describe the site, inputs, and what led you to question it.
5. Submit the issue. Mention `@phillipjws` if you need Phillip's input, and say if the issue is blocking an analysis.

Provide the information you have; the team can ask for more in the comments. Leave API keys, credentials, and restricted data out of text, screenshots, and attachments.

## 3. Add it to the existing board

After submitting, check the issue's **Projects** section to see whether it is already on the CoastSatCLI board. If it is not, select **Projects** and choose the existing board. You can also open the board, use **Add item**, and paste the issue's URL.

Put new work in the board's column for work awaiting a start. If project controls are unavailable to you, mention `@phillipjws` in the issue and ask him to add it. You can still create and discuss issues without access to the board.

For tasks in PlanetScopeCoastSat or this hub, keep the issue in its own repository. Ask Phillip to add it to the shared board if it needs team tracking; do not create a duplicate CoastSatCLI issue.

## 4. Agree on the next step

Use issue comments to agree on the scope and who will take it forward. Assign the person doing the work when known. Add a label if an appropriate one already exists; labels and milestones are optional for our current team.

When someone starts, move the card to the board's column for active work. If work is blocked, leave a comment explaining what is needed. Link related changes or analysis outputs in the issue so the team can find them.

For a small code fix or documentation edit, follow the [team change guide](contributing.md).

## 5. Record the outcome and close it

When the task is finished or the question is answered, leave a short comment recording the outcome, then close the issue. Move the board card to its completed column if the board has not done so automatically. If a problem returns or remains unresolved, reopen the issue with the new details.

## Contact

Questions can be directed to Phillip Steeves at [phillip.steeves@nrcan-rncan.gc.ca](mailto:phillip.steeves@nrcan-rncan.gc.ca) or [@phillipjws on GitHub](https://github.com/phillipjws).

For more detail on the interface, see [GitHub's guide to adding issues to projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-items-in-your-project/adding-items-to-your-project).
