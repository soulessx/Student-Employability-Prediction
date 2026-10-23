# Requirements

## Functional requirements (what the system must DO)

1. The system shall allow students to enter the academic, technical skill, and professional experience information required by the selected prediction model.
2. The system shall validate mandatory input fields and display an error message when required information is missing or invalid.
3. The system shall process valid student information using a trained machine learning model to predict the employment-related outcome defined by the selected dataset.
4. The system shall display the predicted outcome and explain that the result is an estimate rather than a guarantee of employment.
5. The system shall analyse recorded student skills against documented assessment criteria to identify potential areas for improvement.

## Non-functional requirements (how the system must PERFORM)

1. The system shall return a prediction within 3 seconds for at least 95% of valid prediction requests under a defined test environment and workload.
2. The system shall deny access to identifiable student records when the requesting user does not have the required permission.
3. At least 4 out of 5 participants in a usability test shall complete the student prediction and results-review workflow without assistance.