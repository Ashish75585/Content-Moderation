# Content Moderation System using FastText

## Overview

This project implements a **Content Moderation System** using **FastText** to automatically detect and filter inappropriate or harmful text content. The system is trained to classify text into various categories, including harmful content, and employs efficient **text preprocessing** techniques to improve model accuracy.

## Features

- **Text Classification:** Automatically classifies text as harmful or non-harmful based on a labeled dataset.
- **Content Moderation:** Filters inappropriate language/content from user-generated input in real-time.
- **Efficient Preprocessing:** Includes extensive text preprocessing steps to ensure high model performance.
- **Demo Video:** A video demonstration of the content moderation system in action.

## Technologies Used

- **FastText:** For text classification and model training.
- **Python:** Programming language used for building and running the system.
- **Pandas & NumPy:** For data manipulation.
- **Scikit-learn:** For model evaluation and metrics.

## Preprocessing Steps

The preprocessing pipeline involves the following key steps:

1. **Lowercasing:** Converts all text to lowercase to ensure consistency.
2. **Tokenization:** Splits the text into individual tokens (words).
3. **Removing Special Characters:** Eliminates non-alphanumeric characters (e.g., punctuation marks).
4. **Stop-word Removal:** Filters out common but non-informative words (e.g., "the", "and").
5. **Lemmatization/Stemming:** Normalizes words to their base or root form.
6. **Vectorization:** Converts processed text into numerical format for model training.

## Getting Started

### Prerequisites

- Python 3.x
- FastText (You can install it via `pip install fasttext`).
- Pandas, NumPy, and Scikit-learn (Install them using `pip install pandas numpy scikit-learn`).

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/content-moderation.git
   cd content-moderation
## Demo Video
