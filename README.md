<div align="center">

<img src="https://ssoqe.github.io/SSoQE_website/photos/SSOQE_logo3.png" width="150" alt="SSoQE logo">

# Hypotheses, Sampling, and Bias

**Materials for three SSoQE 2026 sessions**

[SSoQE website](https://ssoqe.github.io/SSoQE_website/) · [2026 programme](https://ssoqe.github.io/SSoQE_website/About/program.html)


| **📅 Course information** | **🧰 Technical** | **📌 Status** |
|:---:|:---:|:---:|
| ![SSoQE 2026](https://img.shields.io/badge/SSoQE-2026-155560) | ![Type](https://img.shields.io/badge/Type-Course_Module-155560) | ![Status](https://img.shields.io/badge/Status-Active-509A8E) |
| ![Day](https://img.shields.io/badge/Day-Tuesday_and_Thursday-C2A337) | ![Topic](https://img.shields.io/badge/Topic-Statistics_and_Bias-155560) | ![Tools](https://img.shields.io/badge/Tools-R_%7C_PowerPoint-276DC3) |

</div>

## 📅 Programme role

This repository supports three connected lessons taught across the 2026 programme:

| Session | Date and time | Main slides |
|---|---|---|
| Hypothesis Testing and Null Models | Tuesday, 15 September, 11:00–12:30 | `slides/hypothesis_testing.pptx` |
| Sample Standardisation and Resampling | Tuesday, 15 September, 16:30–18:00 | `slides/sampling_standardisation.pptx` |
| Biases in Ecological and Paleoecological Data | Thursday, 17 September, 14:00–16:00 | `slides/biases.pptx` |

The repository name “Golem Engineering” refers to the shared modelling perspective: statistical models are powerful formal tools that must be designed for the scientific question and the process that generated the data.

## 🎯 Learning goals

Across the three sessions, participants learn to:

- distinguish null-hypothesis testing from comparison of plausible scientific models;
- understand permutation tests, model comparison, and uncertainty;
- evaluate rarefaction, bootstrapping, coverage, and temporal binning;
- identify sampling and measurement biases in ecological and paleoecological data;
- build models that explicitly represent data structure and sampling processes.

## 📚 Materials

- `slides/` contains the three PowerPoint presentations.
- `R/1_exercise_lm.R` through `R/8_exercise_glmm.R` contain progressive exercises.
- The corresponding `R/*_solution*.R` files provide solutions.
- `R/simulations/` generates demonstration data and figures.
- `data/` contains the ecological and paleobiological teaching datasets.
- `figures/` contains figures used by the lessons.

Open `Golem_Engineering.Rproj` in RStudio. Preserve the supplied datasets and write derived results separately.

## 🔄 Relationship to older material

This repository supersedes the older 2024 paleontology-and-resampling materials for the current programme. The historical repository remains a record of that course rather than a second active version of these sessions.
