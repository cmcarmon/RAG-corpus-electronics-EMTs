
README for RAG-corpus-electronics-EMTs

Description:
This project contains datasets aimed at training a Retrieval Augmented Generation (RAG) model in the domain of electronics. The datasets include both computer-graded and human-graded tutoring packs, each with unique characteristics and structures to support comprehensive model training.

Datasets:

1. Computer Graded Tutoring Packs
   - Location: /mnt/data/ComputerGraded/
   - Description: This dataset consists of tutoring sessions that have been graded by a computer. It includes various questions, answers, and additional metadata fields related to electronics topics.
   - Key Features: 
     - Automatically graded responses
     - Metadata such as timestamps, learning state values, and validation regex
   - Usage: Ideal for training models on structured and consistent grading patterns where automation plays a significant role.

2. Human Computer Graded Electronics Tutoring Packs
   - Location: /mnt/data/HumanComputerGraded/
   - Description: This dataset comprises tutoring sessions that have been graded by humans. It includes detailed records of questions, answers, and key validations for electronics-related tutoring.
   - Key Features:
     - Human-graded responses
     - Detailed keys for answer validation
     - Designed to compare with the computer-graded set for consistency and accuracy
   - Usage: Suitable for training models on nuanced and contextually rich data where human judgment is applied. Also used for comparing human gradings with computer gradings to enhance model accuracy.

Differences Between the Datasets:
- Grading Method:
  - Computer Graded: Responses are automatically evaluated based on predefined rules and regex.
  - Human Graded: Responses are assessed by human graders, providing a richer context and more nuanced evaluation.
  
- Consistency vs. Nuance:
  - Computer Graded: Offers consistency and repeatability in grading, ideal for standardizing training data.
  - Human Graded: Introduces variability and human insight, useful for training models to understand complex and context-dependent scenarios.

File Locations:
- Computer Graded Tutoring Packs:
  - README: README.txt
  - Data: ComputerGradedTutoringPacksFull.json
- Human Computer Graded Electronics Tutoring Packs:
  - README: README.txt
  - Data: HumanComputerGradedTutoringPacksFull.json
