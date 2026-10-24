# Problem Statement

## Who is affected?
1. University students and graduates: May need better ways to understand their employment-related strengths and identify skills for further development.

2. Employers: Need graduates whose skills and competencies align with workplace requirements.

3. Universities: Need to prepare students for employment and understand factors associated with graduate employability.


## What exactly is going wrong?

Students may lack a systematic way to review their employment-related strengths and identify skills that need improvement. Without structured analysis, identifying areas for skills development may be challenging. Machine learning may provide a way to analyse relevant data and estimate an employment-related outcome, provided that a suitable dataset is available.


## Why does it matter?

Understanding employability-related factors could help students prioritize career preparation and skills development. It could also provide career services with additional information to support student guidance. However, predictions depend on the quality and representativeness of the data and should not be treated as guarantees of employment or as the sole basis for career decisions.

## Problem statement (3 to 5 sentences)

University students may find it difficult to assess how their academic background, skills, and competencies relate to employment outcomes. Career services may also need structured information to identify common student career-development needs. Previous studies have explored machine learning for employability prediction, including research involving Malaysian community college graduates [1] and student employability data from the Philippines [2, 3]. However, the usefulness of such models depends on the available data and its suitability for the target student population. This project proposes exploring machine learning to estimate a defined employment-related outcome and provide skills analytics to support student career preparation.

## Evidence

Existing research demonstrates that machine learning has been investigated for student and graduate employability prediction:

Mansor and Othman (2024) developed an employability prediction model for Malaysian community college graduates using machine learning algorithms. Their study provides a Malaysian example of applying predictive models to graduate employability [1].

Vo et al. (2023) proposed the OPT-BAG model using a student employability dataset from the Philippines. Their research investigated prediction performance and factors associated with employability, demonstrating a possible approach to this problem [2].

The Kaggle notebook Students’ Employability Prediction Model uses a dataset containing 2,982 mock job-interview observations and nine features. It provides a practical example of a dataset being used for employability prediction, although its Philippine context may limit direct applicability to Malaysian university students [3].

These sources support investigating machine learning for employability prediction. They do not establish that the same models or datasets will be suitable for UiTM students.

## Users and Stakeholders

1. Primary users

University students: Review their predicted employment-related outcome and skills analysis.

University career services staff: Use permitted, aggregated or authorised information to support career-development guidance.

2. Other stakeholders

Universities and academic staff: May use findings to understand student career-development needs.

Employers: Represent the workplace skills and competency expectations relevant to graduate employability.

Project developer and supervisor: Define the project requirements, assess the research approach, and evaluate the project's feasibility.

## Project Scope

In scope

1. Review existing research and identify a suitable dataset for employability prediction.

2. Examine the dataset's features, target variable, quality, and limitations.

3. Explore supervised machine learning methods for predicting a clearly defined employment-related outcome.

4. Propose skills analytics to help students identify potential areas for development, where suitable data and assessment criteria are available.

Out of scope

1. Guaranteeing that a student will obtain employment.

2. Making actual hiring, rejection, or university admission decisions.

3. Claiming that predicted outcomes apply to all Malaysian university students without appropriate validation.

4. Accessing identifiable student records without permission.

## References

[1] Mansor, A., & Othman, Z. (2024). Malaysian community college graduates employability prediction model using machine learning approach. Journal of Telecommunication, Electronic and Computer Engineering (JTEC), 16(3), 1–7. https://doi.org/10.54554/JTEC.2024.16.03.001

[2] Vo, M. T., Nguyen, T., & Le, T. (2023). OPT-BAG model for predicting student employability. Computers, Materials & Continua, 76(2), 1555–1568. https://doi.org/10.32604/CMC.2023.039334

[3] BwandoWando. (n.d.). Students’ employability prediction model [Kaggle notebook]. Kaggle. Retrieved October 21, 2026, from https://www.kaggle.com/code/bwandowando/students-employability-prediction-model
