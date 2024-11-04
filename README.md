# Personal Data Masking Tool

This repository contains a personal data masking tool designed to identify and mask sensitive personal information within unstructured text. Created as part of a **JetBrains internship**, this project showcases advanced text processing capabilities to mask sensitive information like names, dates, contact details, and addresses while maintaining the overall structure and readability of the text.

# Project Overview

Sensitive data masking is crucial for safeguarding privacy in data processing. This tool uses regular expressions and pattern matching techniques to anonymize personal information in various text formats. The application masks all instances of private data efficiently without altering non-sensitive content, which is especially valuable for compliance with data protection standards.

# Features

**Pattern Recognition:** Utilizes regular expressions to detect common patterns of sensitive data, including names, dates, phone numbers, and email addresses.

**Contextual Masking:** Masks words based on context cues such as prepositions and specific keywords (e.g., "by," "at," "to") to ensure all relevant data is anonymized.

**Dynamic Scenarios:** Handles diverse input scenarios, making it adaptable to multiple text contexts (e.g., CVs, invitations, emails, medical records).

**API Integration:** Integrates with an API to enhance accuracy and flexibility in text masking.

# How to Run
Clone the repository.
```bash
git clone https://github.com/yourusername/Personal-Data-Masking-Tool.git
```

Install required dependencies (if any).
Run the tool on sample text or use the provided test cases.

### Acknowledgment
This project was developed as part of an internship application with JetBrains, demonstrating skills in text processing and data anonymization.

