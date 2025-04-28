# Hidden Markov Model Analysis for Scanpath Data

This project provides tools for analyzing scanpath data using Hidden Markov Models (HMMs). It includes functions for data preprocessing, HMM training, evaluation, and visualization.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Data Preparation](#data-preparation)
  - [Training and Evaluation](#training-and-evaluation)
  - [Visualization](#visualization)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [License](#license)

---

## Overview

This project is designed to analyze scanpath data using HMMs. It supports tasks such as:
- Training HMMs on scanpath data.
- Evaluating models using metrics like accuracy, F1-score, recall, and confusion matrices.
- Visualizing transition and emission probabilities as heatmaps.

The primary goal is to understand cognitive and perceptual processes through scanpath data.

---

## Features

- **Data Preprocessing**: Functions to load and preprocess scanpath data from CSV files.
- **HMM Training**: Train HMMs with varying numbers of hidden states.
- **Evaluation**: Evaluate models using cross-validation and various metrics.
- **Visualization**: Generate heatmaps for transition and emission probabilities.
- **Support for Multiple Groups**: Compare models across different groups (e.g., cognitive styles, age groups).

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>

