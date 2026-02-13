# Genetic Data Analysis Toolbox 
## Content

* [Description](#description)
* [Learning Outcomes](#learning-outcomes)
* [Assignments](#assignments)
* [Contacts](#contacts)
* [Delivery of the Learning Module](#delivery-of-the-learning-module)
* [Schedule](#schedule)
* [Requirements](#requirements)
* [Resources](#resources)
  + [Textbook](#Textbook)
  + [Videos](#videos)
* [Folder Structure](#folder-structure)

## Description


This module provides learners with the knowledge foundations necessary to conduct statistical analysis of genetic association studies data. It features a series of lectures and hands-on coding sessions covering key topics, including fundamental concepts in population genetics, population structure in genetic association studies, quality control in genetic data and genome-wide association studies. The module places strong emphasis on the use of modern computational tools such as PLINK, LocusFocus, and real-world data applications to prepare learners for both academic and applied careers in statistical genetics and genetic epidemiology. 

## Learning Outcomes

By the end of the module, participants will be able to:

* Explain foundational concepts in statistical and population genetics, including genetic variation, allele/genotype frequencies, and Hardy–Weinberg Equilibrium.

* Design and interpret GWAS analyses, selecting appropriate association models (including mixed models) and evaluating results in the presence of linkage disequilibrium and polygenicity.

* Implement and justify standard GWAS workflows, including data quality control, multiple testing considerations, and replication/validation strategies.

* Identify, assess, and correct key confounders, especially population stratification, using approaches such as PCA, genomic control, and mixed models.

* Interpret and communicate post-GWAS analyses, including fine-mapping and colocalization with molecular QTLs (e.g., eQTLs).

## Assignments

Participants should review the [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md) for instructions on how to complete assignments in this module.

There are two assignments.

1. [Assignment 1](./02_activities/assignments/Assignment1.qmd)
1. [Assignment 2](./02_activities/assignments/Assignment2.qmd)

## Contacts

**Questions can be submitted to the #help channel on Slack**

* Technical Facilitator:
  * **Fan Wang** (she/her)  
    [fbaobao926@gmail.com](mailto:fbaobao926@gmail.com)
* Learning Support Staff:


## Delivery of the Learning Module

This module will include live learning sessions and optional, asynchronous work periods. During live learning sessions, the Technical Facilitator will introduce and explain key concepts and demonstrate core skills. Learning is facilitated during this time. Before and after each live learning session, the instructional team will be available for questions related to the core concepts of the module. Optional work periods are to be used to seek help from peers and the Learning Support, and to work through the assignments in the learning module, with access to live help. Content is not facilitated; rather, this time should be driven by participants. We encourage participants to come to these work periods with questions and problems to work through.

Participants are encouraged to engage actively during the learning module. The key to developing the core skills in each learning module is through practice. The more participants engage in coding along with the instructional team and apply the skills in each module, the more likely it is that these skills will solidify.

Each session will consist of slides to introduce topics and live coding for some lectures to reinforce the topics. The technical facilitator will reinforce the concepts through a collaborative live coding session using R and other specialized genetic software. The technical facilitator will upload any live coding files to this repository for participants to revisit under `./04_this_cohort`. 

## Schedule

* Class 1: Introduction to Statistical Genetics (slide 01)
* Class 2: Population Genetics (slide 02)
* Class 3: Aggregation Analysis, Heritability and Segregation Analysis (slide 03)
* Class 4: Association Testing I (slide 04)
* Class 5: Association Testing II (slide 05)
* Class 6: Population Stratification & Genotype Imputation (slide 06)
* Class 7: GWAS Analyses (slide 07)
* Class 8: Post-GWAS Analyses I (slide 08)
* Class 9: Post-GWAS Analyses II (slide 09)

## Requirements

* Basic understanding of R. Learners should be able to:
  * Clean and summarize data
  * Make basic plots
  * Troubleshoot simple errors
  * Run R scripts and import simple datasets
* Learners should be familiar with key concepts in statistical inference, including:
  * Distributions of basic random variables (e.g., binomial, normal)
  * Likelihood-based methods, including estimation and hypothesis testing
  * Basic regression techniques (e.g., linear and logistic regression)
* English language proficiency

## Resources
Feel free to use the following as resources:

### Textbook
- The Fundamentals of Modern Statistical Genetics (Nan Laird & Christoph Lange).

### Videos
- Introductory Genomics Videos: [BigBio YouTube Channel – Genomics Playlists](https://www.youtube.com/c/BigBiovideos/playlists?app=desktop)

## Folder Structure

```markdown
.
├── .github
├── .gitignore
├── 01_materials
├── 02_activities
├── 03_instructional_team
├── 04_this_cohort
├── LICENSE
└── README.md
```

* **.github**: Contains issue templates, pull request templates and workflows for the repository.
* **materials**: Module slides.
* **activities**: Contains graded assignments, and rubrics for evaluating assignments.
* **instructional_team**: Resources for the instructional team.
* **this_cohort**: Additional materials and resources for this cohort.
* **.gitignore**: Files to exclude from this folder, specified by the Technical Facilitator
* **LICENSE**: The license for this repository.
* **README**: This file.

