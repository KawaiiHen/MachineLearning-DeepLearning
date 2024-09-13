# Visual Question Answering Models

This repository contains Visual Question and Answer (VQA) models designed to provide assistance in healthcare and medical image analysis.

## PathVQA Model

The PathVQA model is tailored for medical image analysis using the PathVQA dataset where each question is manually checked to ensure correctness. This dataset includes question-answer pairs related to pathology images. The types of questions covered are both open-ended and binary "yes/no" questions.

### Model Details
- **Model Used:** Blip (Bootstrapping Language-Image Pre-training)
- **Paper Link:** https://arxiv.org/abs/2201.12086
- **Fine-Tuning Process:** Includes preprocessing of images, questions, and answers, as well as adding new vocabulary to the pre-trained list.
