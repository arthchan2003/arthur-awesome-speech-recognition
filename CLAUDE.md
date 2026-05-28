# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a pure documentation repository — a curated "awesome list" of speech recognition resources maintained by Arthur Chan. There is no code, build system, or test suite. All content lives in `README.md`.

## Structure of README.md

The README is organized into these top-level sections:

- **Speech Recognizers** — leaderboards to track, wav2vec2 papers, Whisper variants, NeMo, Phi
- **Common Architectures** — CTC, RNN-T, AED, LALM with key papers
- **Speech Datasets** — grouped by language (multilingual, English, Portuguese, Cantonese, Vietnamese) and by hosting platform
- **Conferences & Journals** — Interspeech (ISCA Archive), ICASSP, IEEE/ACM ASLP
- **Not exactly (but cool)** — TTS links, important ML techniques, explainer blog posts, matrix calculus references, RL resources
- **Language Datasets** — Chinese, Cantonese text corpora
- **Large Language Model** — in progress

## Conventions when adding entries

- Each entry follows the pattern: `- [Title](URL) Brief description.` — description on the same line after the link.
- Papers are typically cited as `[Title (Author et al., Year)](arxiv URL)`.
- Related repos/implementations are linked inline near their corresponding paper entry.
- Sections group related items together; add new entries under the most relevant existing section rather than creating new top-level sections unless clearly warranted.
