
README for Computer Graded Tutoring Packs

Description:
This dataset contains data related to computer-graded tutoring packs for various electronics topics. Each record represents a question and its corresponding answer, along with other metadata fields.

Data Fields:
1. Module: The module or topic related to the question.
2. StudentId: Identifier for the student. example: student's name is student001
3. Type: Type of tutoring pack.
4. Question: The question asked in the tutoring session.
5. Answer: The student's answer.
6. Key: The correct answer key.
7. Regex: Regular expression used for answer validation.
8. Times: Timestamp of the response.
9. LSAV: Learning State Assessment Value.
10. RegexV: Regex validation result.
11. RateIDs: Rating identifiers for the answer.
12. Unnamed columns: Additional metadata fields.

Usage:
- Training Data: Use the question and answer pairs to train the model on specific electronics-related queries.
- Metadata: The metadata fields provide additional context that can be useful for more nuanced training and evaluation.

File Location:
- JSON file: ComputerGradedTutoringPacksFull.json
