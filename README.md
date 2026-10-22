# AnthroScore_ITA

Dataset related to the paper **"Terminologization of Anthropomorphic Metaphors in the Italian Discourse around AI"** (Rossella Resi, Journal of Digital Terminology and Lexicography — JDTL, 2026).

## About

This repository contains the annotated dataset used to investigate whether and how anthropomorphic expressions in Italian AI discourse (e.g. *l'IA impara*, 'AI learns'; *l'IA agisce come assistente*, 'AI acts as an assistant') undergo **terminologization** — the process by which a metaphorical expression becomes conventionalized as a technical term, with a corresponding loss of perceived figurativity.

The dataset was built from a targeted web corpus of 82 Italian texts from 68 sources (2023–2026), constructed through a semi-automated bootstrapping procedure (BootCaT) and an adaptation of the AnthroScore metric for Italian. It contains 162 annotated anthropomorphic expressions, each coded across four levels: semantic category, grammatical level, distancing markers, and source register.

## Files

- `Dataset_AnthroTerm_ITA` — the full annotated dataset used for the analysis reported in the paper.

### Sheets

**`Corpus_esempi`** (162 examples) — the main annotated dataset. Columns:

| Column | Description |
|---|---|
| `ID` | Example identifier (examples split from the same source sentence share a numeric ID with a letter suffix, e.g. `1a`, `1b`) |
| `Fonte` | Name of the source publication/website |
| `Tipologia fonte` | Source type (e.g. giornalismo scientifico, portale istituzionale, blog aziendale) |
| `URL` | Link to the original source |
| `Anno` | Year of publication (2023–2026) |
| `Espressione antropomorfica (breve citazione)` | Short quotation containing the anthropomorphic expression |
| `Termine/entita target` | The AI-related entity to which human traits are attributed |
| `Categoria Inie et al.` | Semantic category, following the eight-category taxonomy of Inie et al. (2026): Cognizer, Products of cognition, Emotion, Communication, Agent, Human role analogy, Names and pronouns, Biological metaphors |
| `Livello (verbale / nominale / discorsivo)` | Grammatical realization of the expression (verbal or nominal) |
| `Negazione (sì/no)` | Whether the anthropomorphic predicate is grammatically negated |
| `Meccanismo di distanziamento presente` | Distancing marker type (Yes/Partial/No; e.g. quotation marks, hedges, explicit simile) |
| `Note` | Annotator notes |

**`Tassonomia_di_riferimento`** — the reference taxonomies used for annotation (Inie et al. 2026; distancing-marker scheme), with category definitions and sources.

## Citation

If you use this dataset, please cite:

> Resi, R. (forthcoming). Terminologization of Anthropomorphic Metaphors in the Italian Discourse around AI. *Journal of Digital Terminology and Lexicography (JDTL)*.

## License

This dataset is shared for research purposes. *(Add here the license you prefer — e.g. CC BY 4.0 is a common choice for linguistic datasets shared alongside a publication.)*

## Contact

Rossella Resi — rossella.resi@unipd.it
