# CCC4 corpus acquisition and first-pass analysis

Date: 2026-09-21

## Scope

This is the first corpus pass for CCC5. The uploaded source is the CCC4 submission playlist supplied for this project. Its URL is recorded in the project source register. Because the playlist itself is not currently exposed as a searchable text corpus, this pass uses the official CCC4 final showcase as a secondary index and explicitly distinguishes observed facts from inference.

The official final showcase describes its contents as the top 30 highest-voted CCC4 conlangs, presented in random order, and provides timestamps for each entry. It therefore gives us a reproducible 30-entry index, but it does **not** by itself constitute the full set of valid CCC4 submissions or a transcript corpus.

## Indexed top-30 entries

The 30 titles are stored in `ccc5/corpus/ccc4-submissions.csv`. Their order there is the order of appearance in the official timestamp list, not a ranking.

## What is actually established so far

1. CCC4's final showcase contains 30 entries and labels them as the top 30 highest-voted submissions.
2. The showcase is organised into five presentation days, with entries grouped beneath Day One through Day Five.
3. The titles themselves show a broad range of apparent gimmick surfaces: time, safety, regional/secret languages, unnamed language, wakefulness, named-language parody, emotion, ghosts, mathematics, factorisation, colour, gods, frogs, sampling, sound, science, birds, criticism, and deliberately opaque naming.
4. At least two entries have independently accessible external artefacts in the current research pass:
   - **Epic Avian** has a submission PDF hosted by flirora.xyz. The PDF identifies it as a language of the birds and as a CCC4 submission.
   - **Wattslang++** is documented independently on Esolangs as a programming language evolved from the Wattslang conlang submitted to CCC4. Its documentation describes a language/programming system involving Conway's Game of Life, ASCII-derived behaviour, a program tape, a memory tape, and user responses.
5. The name **Hyadesian Factorlang** is confirmed in the official final-showcase index and is therefore retained as a priority corpus target because of its obvious relevance to the previous CCC4 project and the user's existing mathematical-conlang work. No technical claims about its grammar are made here until its actual presentation or supporting materials are retrieved.

## First-pass gimmick taxonomy

These are **hypothesis buckets derived from titles**, not claims about the actual mechanisms of the languages:

| Bucket | Candidate entries | Evidence level |
|---|---|---|
| Mathematical / formal system | 9,133,162 (MATHLANG), Hyadesian Factorlang | Title-level only |
| Phonological / acoustic / musical | La Langue Sonorisée, Samplese, Chromatish | Title-level only |
| Biological / animal | Epic Avian, Frogsong | Epic Avian externally confirmed; Frogsong title only |
| Sociocultural / identity | The Secret Language of New England, The Language of the Gods, Not Our Language | Title-level only |
| Psychological / experiential | Emotian, Wakey-Wakey, Voidgloom | Title-level only |
| Genre / parody / referential | Polterguese, Scientologese, Medjedic | Title-level only |
| Structural / meta-linguistic | The Language Without a Name, Two Colons, Co Critic | Title-level only |
| Safety / constraint | Safetylang | Title-level only |
| Time / temporal | Colloquial Time Bee | Title-level only |

The buckets are deliberately provisional. A title is not evidence of a grammatical mechanism. Humanity has suffered enough from judging books by covers; we do not need to repeat the experiment with conlangs.

## What this means for CCC5

No CCC5 gimmick should be selected from this first pass. The useful output is a map of the search space and a list of mechanisms that need primary-source inspection.

The next research phase should therefore:

1. acquire presentation transcripts/captions for the 30 indexed entries where available;
2. acquire linked documents, repositories, or project pages for entries with external artefacts;
3. extract the actual cursed mechanism for each accessible entry;
4. code each mechanism across a common taxonomy:
   - what is being made strange;
   - where the strangeness lives (phonology, morphology, syntax, semantics, pragmatics, lexicon, writing, culture, medium);
   - whether the gimmick is mechanically productive;
   - whether it scales to a complete language;
   - whether it produces a strong visual/auditory presentation hook;
   - whether the gimmick has obvious failure modes;
5. only after that generate candidate CCC5 concepts.

## Evidence discipline

Use three labels in subsequent notes:

- **OBSERVED** — directly present in a submission, transcript, document, or official source.
- **INFERRED** — interpretation supported by observed evidence but not explicitly stated by the creator.
- **UNKNOWN** — not established yet.

This prevents the design process from quietly turning guesses about other people's languages into fake facts.

## Immediate priority

**Hyadesian Factorlang** is the first deep-dive target. The current evidence establishes its presence in the official top-30 showcase, but not its internal design. The deep dive should recover the presentation transcript/visuals or an external submission document before drawing any conclusions about its mechanism.

