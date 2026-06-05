The Messy Data Sanitizer

Overview

A data extraction system designed to convert unstructured customer feedback into clean, machine-readable JSON.

The framework focuses on identifying entities, complaints, and emotional sentiment while maintaining consistent output formatting.



Framework

Raw Feedback

↓

Entity Detection

↓

Complaint Extraction

↓

Sentiment Analysis

↓

Structured JSON



Prompt Architecture

Messy Input
↓
Name Extraction
↓
Complaint Detection
↓
Sentiment Classification
↓
JSON Generation



Core Prompt

Analyze the following text:

[Insert Messy Text/Feedback]

Requirements:

- Extract all customer names
- Extract product complaints
- Identify emotional sentiment
- Return valid JSON only
- Do not include explanations
- Preserve data accuracy

Output Schema:

{
  "name": "",
  "complaint": "",
  "sentiment": ""
}



Example Output

Input

John emailed us because the app crashes every time he opens it. He sounded frustrated and said he may cancel.

Output

{
  "name": "John",
  "complaint": "App crashes on launch",
  "sentiment": "Negative"
}



Evaluation Criteria

- Extraction Accuracy
- JSON Validity
- Data Consistency
- Sentiment Accuracy
- Automation Readiness



Benchmark Results

GPT-4.1: 9.5/10

Claude Opus: 9.1/10

Gemini 2.5 Pro: 8.7/10



Model Notes

GPT-4.1

Strong structured data extraction and formatting.

Claude Opus

Excellent contextual interpretation.

Gemini 2.5 Pro

Good entity recognition with occasional formatting inconsistencies.



Research Notes

Inspired by:

- Information Extraction
- Natural Language Processing
- Data Normalization
- Structured Output Engineering



Release: v1.0

Status: Active
