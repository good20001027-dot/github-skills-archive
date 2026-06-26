# Methodology

## Collection Rules

1. Search public GitHub code for `SKILL.md`, `skill.md`, and similar files containing skill frontmatter.
2. Store metadata first: repository, path, URL, detected name, description fragment, and license status.
3. Do not copy full source content unless the repository license clearly permits redistribution.
4. Preserve attribution and source links for every indexed item.
5. Prefer fine-grained GitHub permissions scoped to this archive repository.

## Suggested Permission Model

The token used by Codex should only have write access to this archive repository. Public source repositories can be read through GitHub search/API without granting write access to other repositories.
