# Repository Guide

## Overview

This repository is a curated personal reading list for computer science. The
root `README.md` links to topic files, and each topic file contains Markdown
checklists grouped under subject headings.


## Entry Format

Use one checklist item per resource:

```markdown
- [ ] 📄 [Paper Title](https://example.com/paper.pdf) (A Author, B Author 2024)
```

- Use `[ ]` for a new unread resource. Use `[x]` only when the user says it has
  been read or completed.
- Preserve the title's published capitalization.
- Write author names as initials followed by the surname, without periods in
  the initials: `SE Robertson`.
- Separate authors with commas. Use `et al` when listing every author would be
  unwieldy.
- Put the publication year last inside the parentheses. Omit metadata that
  cannot be verified instead of guessing.
- Put a familiar nickname after the citation when useful:
  `_"The HNSW paper"_`.

## Resource Icons

Use the icon that describes the resource itself:

- `📄` paper, technical report, or specification
- `📖` book
- `🎥` talk, lecture, or video
- `👨‍🏫` course
- `💬` blog post or article
- `🔗` website, documentation, or reference collection
- `🛠` hands-on tutorial or project

Follow the surrounding file if an established local convention differs. Do not
normalize unrelated older entries as part of a focused change.

## Curation and Ordering

- Bold only particularly important, foundational, or canonical resources:
  `[**Title**](url)`.
- Within a section, place bold resources before regular resources.
- Keep entries alphabetized by displayed title within each group when practical.
- Choose the most specific existing section. Add a new section only when it
  creates a useful distinction and is likely to contain multiple entries.
- Add a new topic file to `README.md` when creating one.

## Links and Research

- Verify the exact title, authors, year, and intended work before adding it.
- Prefer stable primary sources: official proceedings, publisher or DOI pages,
  institutional repositories, author-hosted copies, and arXiv.
- Prefer a public direct PDF when it is stable and authoritative. Use the
  canonical landing page when a direct PDF is unavailable or access-controlled.
- Avoid search-result links, citation aggregators, and unofficial mirrors when
  a reliable primary source exists.

## Editing and Validation

- Keep changes small and editorial. Only modify existing entries when asked.
- Preserve the reader's existing completion state and curation choices.
- Check `git status --short` before editing and preserve unrelated changes.
- Match the nearby Markdown style; avoid broad reformatting or cleanup.
- Review the focused diff after editing.
- Run `git diff --check` before finishing.

Validate that:

- The Markdown is valid
- The diff is clean
- Metadata is correct
- Links work