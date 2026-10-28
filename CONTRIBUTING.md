# Contribute a useful skill

Suggest a skill or collection through an issue or pull request. Include its primary repository, current setup instructions, the task it helps with, and a concrete difference from entries already listed.

When adding or removing a selected entry, update both `README.md` and `catalog.json`. Their selected URLs must agree so the nightly table and Pages ItemList cover exactly the visible selection. Run `python3 -B scripts/test_refresh.py` to check the update rules.

Prefer a maintained upstream source with a clear license and a working installation guide. Identify whether it is a single skill, a collection, a plugin bundle or a tool with a bundled skill. Note required software, service access and host compatibility.

Keep descriptions factual and brief. Link to the author rather than copying skill contents into this repository. Do not include credentials, personal records or private project material.

For a correction, link to the upstream change and name the affected row. For a new category, show the distinct task a reader needs to accomplish.

## What to include in a pull request

1. A canonical primary repository and direct installation link.
2. A concrete task, required stack and a useful distinction from the closest listed option.
3. Packaging: single skill, collection, plugin bundle or tool with a skill. Identify any bundled connectors, hooks or agents.
4. The upstream license, current activity and required accounts, paid services or local tools. State whether you reviewed instructions or actually tested an installation.
5. The date you checked the sources. Update the affected README row and the repository catalog if you add or remove an entry.

The [pull request template](.github/PULL_REQUEST_TEMPLATE.md) includes these fields. No placement fee or reciprocal link is required. Maintainers review task fit and factual support; stars do not determine inclusion.

## Featured in badge

If your project is listed, you may add this optional badge to its README after this directory is published:

```markdown
[![Featured in Best Claude Code Skills](https://img.shields.io/badge/Featured_in-Best_Claude_Code_Skills-2563eb)](https://github.com/gbouslov/best-claude-code-skills)
```

You can link the badge directly to the section containing your entry by adding that section's GitHub anchor to the destination. The badge identifies inclusion in this directory; it is not a certification of the project.

## Keeping the list current

Repository metadata and editorial reviews are separate. Automated metadata refreshes can update stars, commit timestamps and archived status. Changes to task descriptions, setup commands or prerequisites need a primary-source review and a new editorial checked date.

Contributions to this list's original text use its MIT license. Linked projects retain their own licenses.
