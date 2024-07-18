# DREAM-FLUTE Model for Commonsense Reasoning and Figurative Language Understanding

The DREAM-FLUTE project extends the capabilities of the DREAM model by integrating it with T5-BASE and BERT models, aiming to enhance performance on the Commonsense QA task. This repository contains the implementation code and related materials for the DREAM-FLUTE method which includes fine-tuning BERT on the CoS-E dataset and utilizing the DREAM model to generate detailed elaborations that improve the prediction precision of T5-BASE.

## Project Overview
The DREAM-FLUTE project focuses on extending the capabilities of the DREAM model to address the significant challenge of enhancing commonsense reasoning and figurative language understanding in NLP. This repository contains all the necessary implementation code, datasets, and documentation for reproducing our findings and further research.
- Objective: Enhance commonsense reasoning and figurative language understanding in NLP models.
- Methods: Integration of DREAM with T5-BASE and BERT for better performance on the Commonsense QA task.
- Dataset: Uses the CoS-E dataset with comprehensive annotations for training and evaluation.

## Model Architecture
**DREAM-FLUTE System 1**
- Model Selection: Uses the BERT model for its robust performance in natural language understanding tasks.
- Data Preparation: The CoS-E dataset is tokenized and encoded to fit the input requirements of BERT.
- Fine-tuning Process: BERT is fine-tuned to predict answers from multiple-choice questions based on the given context, enhancing its base capabilities on Commonsense QA tasks.

**DREAM-FLUTE System 2**
- Model Selection: Employs T5-BASE for its versatility in text-to-text tasks.
- Elaboration Generation: Uses the DREAM model to generate detailed contextual elaborations for each question.
- Integration and Fine-Tuning: These elaborations are integrated with T5-BASE to enhance the model’s understanding and accuracy in predictions.

## Experiments and Results
We conducted our experiments using the CoS-E dataset which involves a series of contexts, questions, and multiple-choice answers, each accompanied by a detailed explanation. Our experimental results demonstrate that the additional context provided by DREAM elaborations significantly improves the accuracy of the T5 model, while the improvements on BERT are less pronounced.

## How to Contribute
We welcome contributions from the community. Here are ways you can contribute:

- Issues: Report bugs or suggest new features.
- Pull Requests: Submit improvements to the codebase or documentation. Please ensure your code adheres to the existing style to maintain project coherence.

## Contact
For questions or support, feel free to reach out via email at sina.hamedani@studenti.polito.it.


