<div align="center">

<img src="https://ssoqe.github.io/SSoQE_website/photos/SSOQE_logo3.png" width="150" alt="SSoQE logo">

# Hypothesis Testing and Null Models

**SSoQE 2026 · Tuesday, 15 September · 11:00–12:30**

[SSoQE website](https://ssoqe.github.io/SSoQE_website/) · [2026 programme](https://ssoqe.github.io/SSoQE_website/About/program.html)


| **📅 Course information** | **🧰 Technical** | **📌 Status** |
|:---:|:---:|:---:|
| ![SSoQE 2026](https://img.shields.io/badge/SSoQE-2026-155560) | ![Type](https://img.shields.io/badge/Type-Course_Module-155560) | ![Status](https://img.shields.io/badge/Status-Active-509A8E) |
| ![Day](https://img.shields.io/badge/Day-Tuesday-C2A337) | ![Topic](https://img.shields.io/badge/Topic-Hypothesis_Testing-155560) | ![Tools](https://img.shields.io/badge/Tools-R_%7C_PowerPoint-276DC3) |

</div>

## 🌿 About the lesson

This repository is the active home of the 2026 Hypothesis Testing and Null Models lesson. The lesson connects null-hypothesis testing, permutation, comparison of plausible scientific models, and uncertainty with the design of models for ecological questions.

## 🔄 Split status

The pre-migration repository supported three connected lessons:

| Session | Date and time | Main slides |
|---|---|---|
| Hypothesis Testing and Null Models | Tuesday, 15 September, 11:00–12:30 | `slides/hypothesis_testing.pptx` |
| Sample Standardisation and Resampling | Tuesday, 15 September, 16:30–18:00 | `slides/sampling_standardisation.pptx` |
| Biases in Ecological and Paleoecological Data | Thursday, 17 September, 14:00–16:00 | `slides/biases.pptx` |

Verified copies of the Sample Standardisation and Biases bundles now exist in their new private repositories. Their original files remain here unchanged until the responsible lecturer reviews the copied bundles and explicitly approves removal. The restore tag `20260831-before2026` preserves the complete pre-split state.

## 🎯 Learning goals

For this session, participants learn to:

- distinguish null-hypothesis testing from comparison of plausible scientific models;
- understand permutation tests, model comparison, and uncertainty;
- build models that explicitly represent data structure and sampling processes.

## 📚 Materials

- `slides/hypothesis_testing.pptx` is the active lecture deck.
- `R/1_exercise_lm.R` through `R/3_exercise_aic.R` are the active exercises.
- The corresponding `R/*_solution*.R` files provide solutions.
- `R/simulations/` generates demonstration data and figures.
- `data/` contains the ecological and paleobiological teaching datasets.
- `figures/` contains figures used by the lessons.

Open `SSoQE-Hypothesis_Testing_and_Null_Models.Rproj` in RStudio. Preserve the supplied datasets and write derived results separately.

## 🔄 Relationship to older material

This repository supersedes the older 2024 paleontology-and-resampling materials for the hypothesis-testing session. The historical repository remains a record of that course rather than a second active version.
