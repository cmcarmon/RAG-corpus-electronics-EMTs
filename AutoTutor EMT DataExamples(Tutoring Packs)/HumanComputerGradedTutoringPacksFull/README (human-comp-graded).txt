
README for Human Computer Graded Electronics Tutoring Packs

Description:
This dataset includes data from human-graded electronics tutoring sessions. Each record captures a question, the corresponding student answer, and additional key information for validation.

Data Fields:
1. Question: The question asked in the tutoring session.
2. Answer: The student's answer.
3. Key: The correct answer key.
4. Module: The module or topic related to the question.
5. StudentId: Identifier for the student.
6. Type: Type of tutoring pack.
7. Regex: Regular expression used for answer validation.
8. Times: Timestamp of the response.
9. LSAV: Learning State Assessment Value.
10. RegexV: Regex validation result.
11. RateIDs: Rating identifiers for the answer- 1 = bad/wrong answer, 2 = partial correctness- mostly bad, 3 = partial correctness- with errors, 4 = partial correctness- mostly correct, 5 = ideal/complete answer
12. Unnamed columns: Additional metadata fields.

Usage:
- Training Data: Utilize the question, answer, and key pairs to train the model, focusing on human-graded assessments.
- Metadata: Leverage the metadata for additional insights into the context and validation of responses.

File Location:
- JSON file: HumanComputerGradedTutoringPacksFull.json
