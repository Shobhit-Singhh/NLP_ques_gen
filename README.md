# NLP_ques_gen Automated Educational Assessment Tool 

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Solution](#solution)
- [Key Components](#key-components)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Extended Information](#extended-information)
- [Conclusion](#conclusion)

## Introduction

Welcome to the documentation for the Automated Educational Assessment Tool. This project addresses a critical need within the education sector by leveraging AI-driven tools to automate the process of generating various types of assessment questions. The system focuses on Multiple-Choice Questions (MCQ), Multiple-Select Questions (MSQ), True/False, Fill in the Blanks, and Match the Following questions to streamline the assessment creation process.

## Problem Statement

The manual creation of educational assessment questions is a time-consuming task for educators and content creators. Recognizing this challenge, our goal is to develop an NLP (Natural Language Processing) system that automates the generation of diverse types of questions, thereby significantly reducing the time and effort required for manual question framing.

## Solution

To address the problem, we have developed a sophisticated NLP system that utilizes advanced techniques and models. The system is designed to generate MCQ, MSQ, True/False, Fill in the Blanks, and Match the Following questions. This automated approach allows educators to focus more on the quality of educational content rather than spending excessive time on question formulation.

## Key Components

1. **T5's Text-to-Text Framework**: The core of our system is based on T5's text-to-text framework, providing versatility in handling different text generation tasks.

2. **Ward Net's Language Modeling**: Ward Net's language modeling enhances the contextual understanding of the generated questions, ensuring grammatical correctness and contextual relevance.

3. **Sen2Vec's Semantic Analysis**: Sen2Vec's semantic analysis is employed to ensure that the questions generated are not only grammatically correct but also semantically meaningful and coherent.

## Technologies Used

- T5 (Text-To-Text Transfer Transformer)
- Ward Net's Language Modeling
- Sen2Vec's Semantic Analysis
- Spacy, NLTK, AllenNLP, HuggingFace Transformers, etc.

## Results

The implementation of our NLP system has resulted in a substantial reduction of 70-80% in the time required for manual question framing. This efficiency improvement allows educators to allocate their time more effectively, focusing on other critical aspects of the teaching and learning process.

## Extended Information

- **Generate Distractors for MCQ Options:**
  - Utilize several approaches such as Wordnet, ConceptNet, and Sense2vec to generate distractors for MCQ options.

- **Generate True or False Questions:**
  - Implement pre-trained models including sentence BERT, constituency parser, and OpenAI GPT-2.
  - Learn to use the constituency parser from AllenNLP to split any sentence.
  - Use GPT-2 to generate sentences with alternate endings and filter them with Sentence BERT.

- **Generate MCQs from Any Content:**
  - Understand the T5 transformer algorithm.
  - Train a question generation model using the SQUAD dataset with HuggingFace Transformers library and Pytorch Lightning.

- **Generate Fill in the Blanks Questions:**
  - Utilize Python Keyword extraction library to extract keywords.
  - Use the flashtext library for fast keyword matching.
  - Visualize fill-in-the-blanks using HTML ElementTree in Colab.

- **Generate Match the Following Questions:**
  - Extract keywords using the Python Keyword extraction library.
  - Utilize the flashtext library for fast keyword matching.
  - Implement BERT for word sense disambiguation (WSD).

- **Deploy Question Generation Models to Production:**
  - Deploy transformer models like T5 to production in a serverless fashion.
  - Convert models to ONNX format and perform quantization.

## Conclusion

The Automated Educational Assessment Tool represents a significant advancement in the field of educational technology. By harnessing the power of NLP and sophisticated language models, we have successfully addressed the time-consuming nature of manual question framing. This tool empowers educators to create diverse and high-quality assessments efficiently, ultimately enhancing the overall teaching and learning experience.

For detailed information and instructions, please refer to the project's documentation and codebase. Your feedback and contributions are welcome as we continue to refine and improve this valuable educational resource.
