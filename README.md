# ACES
Automatic Cohort Extraction System for Event-Stream Datasets

Reproducibility remains a significant challenge in machine learning (ML) for
healthcare. In this field, datasets, model pipelines, and even task/cohort definitions
are often private, leading to a significant barrier in sharing, iterating, and under-
standing ML results on electronic health record (EHR) datasets. In this paper, we
address a significant part of this problem by introducing the Automatic Cohort
Extraction System for Event-Stream Datasets (ACES). This tool is designed to
simultaneously simplify the development of task/cohorts for ML in healthcare
and enable the reproduction of these cohorts, both at an exact level for single
datasets and at a conceptual level across datasets. To accomplish this, ACES pro-
vides (1) a highly intuitive and expressive configuration language for defining both
dataset-specific concepts and dataset-agnostic inclusion/exclusion criteria, and (2)
a pipeline to automatically extract patient records that meet these defined criteria
from real-world data. ACES can be automatically applied to any dataset in either the
Medical Event Data Standard (MEDS) or EventStreamGPT (ESGPT) formats, or to
any dataset for which the necessary task-specific predicates can be extracted in an
event-stream form. ACES has the potential to significantly lower the barrier to entry
for defining ML tasks, redefine the way researchers interact with EHR datasets, and
significantly improve the state of reproducibility for ML studies in this modality.
ACES is available at https://github.com/justin13601/aces.
