# Sinhala Spell Checker and Grammar Checker

An AI-powered spell checking and grammar correction system for the Sinhala language, utilizing multiple advanced approaches including Retrieval-Augmented Generation (RAG), rule-based systems, and BERT models.

## Features

### Spell Checker
- Advanced spell checking specifically designed for Sinhala text
- Rule-based approach combined with pre-trained language models
- Context-aware error detection and correction
- Intelligent suggestion system for detected errors

### Grammar Checker
The project implements three different approaches for grammar checking:

#### 1. Rule-Based Grammar Checker
- Based on predefined Sinhala grammar rules
- Fast and lightweight processing
- Handles common syntax and morphology errors
- Efficient for basic grammatical mistake detection

#### 2. BERT-Based Grammar Checker
- Powered by fine-tuned BERT model for Sinhala
- Context-aware grammar analysis
- Advanced error detection capabilities
- Handles complex grammatical structures

#### 3. RAG-Based Grammar Checker
- Combines retrieval and generation approaches
- High adaptability to various error types
- Enhanced accuracy through example-based learning
- Flexible handling of complex grammatical constructs

## System Comparison

| Feature | Rule-Based | BERT-Based | RAG-Based |
|---------|------------|------------|-----------|
| Accuracy | Moderate | High | Very High |
| Computational Cost | Low | High | High |
| Complexity | Simple | Moderate | Complex |
| Contextual Error Handling | Limited | High | Very High |
| Flexibility | Low | Moderate | High |
| Complex Sentence Performance | Low | High | Very High |
| Adaptability | Low | Moderate | Very High |

## Technical Requirements
- Node.js v16.x or higher
- NPM v8.x or higher
- Minimum 4GB RAM recommended
- At least 2GB of free disk space
- Modern web browser (Chrome, Firefox, Safari, or Edge)

## Installation
1. Clone the repository
```bash
git clone https://github.com/[your-username]/sinhala-spell-checker.git
cd sinhala-spell-checker
