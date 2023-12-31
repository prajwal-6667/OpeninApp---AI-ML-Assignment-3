# OpeninApp---AI-ML-Assignment-3
AI ML Assignment 3 - Translation Assignment
Here's a README file for Hinglish translation model:

---

# Hinglish Translation Model

## Overview

This repository contains a Hinglish (a blend of Hindi and English) translation model that can translate English text to Hinglish. The model uses the Google Translate API and a predefined mapping to transliterate Hindi words into Hinglish. This README provides instructions on how to run the model and how to evaluate its performance.

## Prerequisites

Before running the model, make sure you have the following prerequisites installed:

- Python 3.x
- Required Python libraries: `googletrans==4.0.0-rc1` (for translation)

You can install the required libraries using pip:

```bash
pip install googletrans==4.0.0-rc1
```

## Usage

Follow these steps to use the Hinglish translation model:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/prajwal-6667/OpeninApp---AI-ML-Assignment-3.git
```

2. Navigate to the project directory:

```bash
cd OpeninApp---AI-ML-Assignment-3
```

3. Run the translation script:

```bash
python translate_to_hinglish.py
```

4. Enter the English text you want to translate when prompted(Demonstration of the give three sentences including the example is shown in the notebook).

5. The translated Hinglish text will be displayed as the output.

## Performance Evaluation

The model's performance is primarily dependent on the quality of translation provided by the Google Translate API. The predefined mapping (`transliteration_map`) helps convert Hindi words into Hinglish, but the overall quality of translation may vary.

To evaluate the model's performance, you can:

1. Compare the Hinglish output with your expectations for translation accuracy.

2. Experiment with different sentences and texts to assess how well the model handles various inputs.

3. Consider using a larger dataset for the `transliteration_map` to improve the quality of Hinglish translations.

## Contribution

If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request. Contributions are welcome!

