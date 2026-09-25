# Intius AI Research

Twenty readable research notes about small models, LoRA training, sparse likelihoods, memory and modular reasoning. Each note keeps its measured result, controls, failure boundaries and source evidence together.

The collection contains **14 distinctive local experiments** and **6 applied case studies using established methods**. This is not a claim of 20 novel algorithms. Global novelty remains unresolved; many successes are narrow or partial.

## Start here

- [Overview and evidence standard](00_START_HERE.txt)
- [Reading map for all 20 findings](01_READING_MAP.txt)
- [Novelty and prior work](02_NOVELTY_AND_PRIOR_WORK.txt)
- [Using this for LLM and LoRA research](03_USING_THIS_FOR_LLMS_AND_LORAS.txt)

## Three findings to explore

1. **[Intervention coordinates](findings/R02_intervention_coordinates.txt):** 99.63% prediction accuracy in six constrained Boolean worlds; 35/36 planning tasks succeeded. Changing key assumptions caused complete abstention.
2. **[Neural interface contracts](findings/R03_neural_interface_contracts.txt):** 99.96% whole-state accuracy after component swaps on held-out combinations under a shared standard. Reordered descriptions and long chains exposed failures.
3. **[Exact sparse language corrections](findings/R01_exact_sparse_language_corrections.txt):** 1.78% lower byte-prediction loss with 45.59% less training time against the tested dense correction. A stronger-prior follow-up reduced the time saving to 6.19%.

For a directly practical adapter experiment, see **[the checked LoRA data mix](applied_results/A01_lora_data_mix.txt)**: Stage 2 scored 35/48 versus Stage 1's 27/48 on a separate frozen question subset, at roughly twice the generation time.

These measurements concern different tasks and are not a common capability ranking.

## Evidence and reuse

- [Source register](08_SOURCE_REGISTER.txt) and [47 bundled report snapshots](evidence/)
- [Caveats and superseded claims](05_CLAIMS_THAT_NEED_THEIR_CAVEATS.txt)
- [Coverage and selection](07_SCOPE_AND_SELECTION.txt)
- [Curation validation](09_VALIDATION.txt) and [SHA-256 manifest](MANIFEST_SHA256.txt)
- [20 compact research Q&A records](04_RESEARCH_QA.txt)
- [Reuse and attribution](10_REUSE_AND_ATTRIBUTION.txt)

This is a research-text release, not a runnable reproduction repository or a model-weight/training-corpus release. The notes were synthesized with AI assistance from local reports. Curation included source and numerical checks, but no independent retraining. Reading or fine-tuning on these descriptions does not implement their architectural mechanisms.

Prepared 25 September 2026. No world-first, AGI or frontier-parity claim is established. No license is assigned by this collection; referenced third-party artifacts retain their own terms.
