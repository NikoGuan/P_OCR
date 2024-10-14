# OCR Correction and Synthetic Data Generation Models

Welcome to the repository for the code implementations behind two cutting-edge papers on post-OCR correction:

1. **Advancing Post-OCR Correction: A Comparative Study of Synthetic Data** (**ACL 2024**).
2. **Effective Synthetic Data and Test-Time Adaptation for OCR Correction** (**EMNLP 2024**).


## Overview 🌟

Post-OCR correction is all about fixing the errors introduced by Optical Character Recognition (OCR) systems when converting scanned images into text. The approaches introduced in these two papers enhance OCR correction through innovative techniques like **synthetic data generation** and **test-time adaptation (TTA)**. 

### Key Contributions:

- **Multi-noise level synthetic data generation** : We generate datasets with different error levels, making models more adaptable to real-world OCR outputs.
- **Weak supervision** : By using weakly labeled data, we improve the model's ability to handle a wide variety of OCR errors.
- **Test-time adaptation (TTA)** : The *Self-Correct-Noise Test-Time Adaptation (SCN-TTA)* method dynamically adapts to test data, ensuring better performance, especially for proper nouns and tricky text segments.
- **Character similarity calculation**  is a crucial part of our method for synthetic data generation. We calculate glyph similarities between characters using computer vision feature detection algorithms like SIFT and ORB, to inject realistic OCR-like errors into the text.

By using these approaches, models like **ByT5** show significant improvements, reducing Character Error Rates (CER) by up to 68.67%! 

## Coming Soon 

The full code will be released before **EMNLP 2024**! Stay tuned for updates!

