# FinalProject

Group workspace for the CSCI-490 NLP final project: reproducing the MemSum
human-evaluation workflow from ReproNLP 2026.

## Repo Layout

- `notebooks/`
  Colab notebooks used for the four annotator copies of the MemSum evaluation.
- `data/human_eval/`
  Human-evaluation JSONL files used by the notebooks.
- `docs/instructions/`
  ReproNLP evaluator and team instructions plus the notebook assignment sheet.
- `docs/reference/`
  Paper, interface reference image, notes from the public materials, and the
  shared report outline.
- `external/memsum_demo/`
  Extracted MemSum demo code and lightweight reference files from the public
  software package.

## Working Notes

- The four notebooks are annotator-specific copies of the same evaluation
  workflow, not four different reproduction tasks.
- The notebook named `Copy of MemSum_Human_Evaluation_1.ipynb` is kept because
  the evaluation code derives the annotator ID from the notebook filename.
- Large local-only assets are intentionally not tracked in git. That includes
  `wiki_unigrams.bin`, archive dumps, the exact Drive snapshot, and large model
  or dataset artifacts pulled from the public software bundle.

## Getting Missing Files

- `wiki_unigrams.bin` still needs to be shared outside git because it is about
  5 GB and GitHub will not accept it.
- If you need the original upstream MemSum repo, clone
  `https://github.com/nianlonggu/MemSum.git` into `external/MemSum/`.
- If you need the full Drive-style folder dump or large archive copies, use the
  shared course Drive rather than this repo.
