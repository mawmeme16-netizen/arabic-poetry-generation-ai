![Genبيت Project unnamed](genbeit-unnamed.png)
# Genبيت | Arabic Poetry Generation Using AI

## Project Overview

Genبيت is an AI-powered Arabic poetry generation project that adapts Large Language Models to generate classical Arabic poetry while preserving Arabic literary identity, poetic structure, and eloquence.

The project explores the use of fine-tuning techniques to improve Arabic poetry generation and address challenges related to classical Arabic language and poetic form.

## Dataset & Data Preparation

The project started with an original dataset of more than **313,000 Arabic poems**, which was cleaned and structured into approximately **59,000 poems** for model training.

The data preparation process included:

- Collecting and combining Arabic poetry data.
- Handling missing and incomplete records.
- Arabic orthographic normalization.
- Removing duplicate and near-identical verses.
- Structural filtering of fragmented or invalid poetry lines.
- Cleaning non-Arabic symbols, markup, and irregular spaces.
- Formatting the data into instruction-response pairs for Supervised Fine-Tuning (SFT).

## My Contribution

As a member of the project team, my contributions included:

- Collecting Arabic poetry data.
- Cleaning and preprocessing the dataset.
- Preparing structured poetry data for model training.
- Contributing to the model training process.

## Model & Training

- **Base Model:** Qwen2.5 3B
- **Training Method:** Supervised Fine-Tuning (SFT)
- **Fine-Tuning Technique:** QLoRA
- **Optimization:** Parameter-Efficient Fine-Tuning (PEFT)
- **Model Quantization:** 4-bit precision

These techniques were used to reduce GPU memory requirements and support efficient fine-tuning.

## System Architecture

The project consists of the following components:

- **AI Model:** Qwen2.5 with QLoRA fine-tuned weights.
- **Backend:** FastAPI.
- **Frontend:** HTML, CSS, and JavaScript.
- **Database:** Firestore.
- **Media Storage:** Cloudinary.
- **Cloud Hosting:** Vast.ai.

## Technologies Used

Python · Qwen2.5 · QLoRA · SFT · PEFT · FastAPI · HTML · CSS · JavaScript · Firestore · Cloudinary

## Repository Contents

This repository contains selected notebooks demonstrating the data preparation and analysis stages of the project.

The original dataset and trained model files are not included.

## Project Team

Graduation project completed as part of the Data Science and Artificial Intelligence program at Mutah University.


