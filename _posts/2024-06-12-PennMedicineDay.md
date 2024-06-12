---
layout: single
title: "Penn Medicine Research Day 2024"
permalink: /presentations/MedicineResearchDay2024/
---

## Our Work on Clinical Text Analysis using GPT-4 at Penn Medicine Research Day!

We are happy to share that our work on leveraging large language models (LLMs) to optimize clinical text analysis for in-hospital cardiac arrest (IHCA) identification was presented by Aarthi Kaviyarasu on 06/12/2024 at the Department of Medicine Research Day in Philadelphia, PA. 🏥✨

### Objective

To determine if using large language models (LLMs) for analysis of electronic health record (EHR) notes will facilitate accurate assertion of the presence of IHCA at the patient-level.

### Methods

- **Population**: Adult (≥ 18 years) inpatient encounters at the Hospital of the University of Pennsylvania from 06/2018 to 03/2022 with a reported clinical emergency.
- **Data Collection**: Patient encounters were identified using a QI database. All discharge summaries associated with the encounters of interest were pulled from the EHR and deidentified using PHIlter. Notes were reviewed by research staff to ascertain true IHCA labels (positive vs. negative). Positive IHCA was defined as the loss of pulses followed by the delivery of CPR.
- **LLM/Environment**: GPT-4 v. 32K-Chat / Penn Medicine Microsoft Azure Databricks.
- **Prompting Methods**: 
  - Zero-shot prompting: Provided the LLM with only the prompt, no examples.
  - Four-shot prompting: Provided the LLM with 2 positive and 2 negative examples.
- **Performance Measures**: F1 Score, accuracy, precision, recall.

### Results

- **Manual Chart Review**: Determined 48% and 52% of cases to be IHCA+ and IHCA-, respectively.
- **Zero-Shot Learning**:
  - Accuracy: 81%
  - Precision: 71%
  - Recall: 100%
  - F1-Score: 83%
- **Four-Shot Learning**:
  - Accuracy: 90%
  - Precision: 83%
  - Recall: 100%
  - F1-Score: 91%

### Discussion

This study demonstrates the potential efficacy of leveraging LLMs to automatically classify IHCA from discharge summaries and improve precision with n-shot learning. These findings suggest that such technologies can be effective in real-world clinical settings, providing a scalable solution to improve patient outcomes and quality improvement efforts.

### Future Directions

- Refinement of model parameters (e.g., temperature, maximum output token size, selection of positive and negative examples).
- Implementation of temporal and strategic sampling of various note types to develop a more informed and clinically relevant model.
- External validation of the model using cases from other Penn Medicine hospitals (i.e., Penn Presbyterian Medical Center, Pennsylvania Hospital, HUP Cedar, Chester County Hospital).

### Collaborators

- Aarthi Kaviyarasu, BS
- Ugurcan Vurgun, MA
- Sy Hwang, MS
- Ana Acevedo, BA
- Danielle L. Mowery, PhD, MS, MS
- Benjamin S. Abella, MD, MPhil
- Oscar J. L. Mitchell, MD, MSCE

Stay tuned for more updates and future publications! 📖🔍