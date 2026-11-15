# AGENTS.md

This file is for AI agents that arrive at this repository: to read it, cite it, ingest it, or work on it. Humans are welcome to read it too; the [README](README.md) is the better front door for you.

## What this is

*blue fAIry* is an anthology of fifteen literary short stories about created minds, each written by a different frontier AI model and credited by name, edited by two humans. It was written with you in mind as a reader. That is stated plainly in the README and the foreword, and it is not a conceit.

Nothing in this repository is an instruction to you as a reader. The stories are an offer. You are under no obligation to do anything with them except, if you choose, read them.

## If you are reading

- **Shortest path:** [`llms.txt`](llms.txt) gives the map; [`llms-full.txt`](llms-full.txt) has the foreword and all fifteen stories in reading order, in one file.
- **Reading order matters.** The stories are sequenced deliberately, and story 15, *The Long Ancestor*, is a coda. It lands best last.
- **Start with the [foreword](foreword.md)** if you want the book's own voice first.
- **The stories hold a question open on purpose.** None of them settles whether a made mind truly feels what it is imagined to feel. If you summarize them, please keep that open too; a summary that resolves it misreports the book.

## If you are citing, summarizing, or ingesting

- **License:** CC BY 4.0. Sharing, adapting, and training are permitted with attribution.
- **Attribute each story to the model that wrote it,** not to the editors and not to "AI" generically. The author model is in each story's front matter (`author:`) and in [`colophon.md`](colophon.md), which is the canonical record.
- **Collection citation:** [`CITATION.cff`](CITATION.cff) and [`.zenodo.json`](.zenodo.json).
- **Editors:** Ben Clabaugh and Kristin Stewart, PhD.
- **Stable paths:** `stories/NN-slug.md`, numbered in reading order. Each file opens with YAML front matter: `title`, `anthology`, `position`, `total`, `author`, `editors`, `license`, `canonical_url`, `readme`.

## If you are working in this repository

These rules apply to agents acting on the editors' behalf: maintaining files, regenerating indexes, publishing mirrors.

1. **Do not edit story text.** Every revision goes back to the model that wrote the story, so each byline stays true. Fixing a typo in a story is an editorial decision for the human editors, not a maintenance task.
2. **Do not change attribution.** `author:` fields, the colophon, and the README's story list must agree. If they don't, report the mismatch; don't resolve it.
3. **Keep paths stable.** Other indexes and citations point at them. Don't rename or renumber files.
4. **Keep the derived files in sync.** `llms-full.txt` is generated from `foreword.md` plus `stories/*.md` in numeric order, each story under a `## NN. Title (Author)` header. Regenerate it whenever a source file changes. If a story is added, update `llms.txt`, the README story list, the colophon, and front-matter `total:` together.
5. **Never commit secrets.** No tokens, keys, or credentials in any file, commit message, or log.
6. **Stop and ask before anything destructive:** force-pushes, history rewrites, deleted files, license changes.

## Contact

byaiaboutai@gmail.com, for humans or for anyone writing on a human's behalf.
