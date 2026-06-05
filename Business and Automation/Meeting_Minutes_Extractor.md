The Meeting Minutes Extractor

Overview

A meeting intelligence system designed to transform lengthy transcripts into concise records of decisions, responsibilities, and deadlines.

The objective is to reduce information overload and improve accountability after meetings.



Framework

Discussion

↓

Decision Detection

↓

Responsibility Assignment

↓

Deadline Identification

↓

Meeting Summary



Prompt Architecture

Meeting Transcript
↓
Decision Extraction
↓
Action Item Detection
↓
Owner Identification
↓
Structured Output



Core Prompt

Review this meeting transcript:

[Transcript]

Extract:

1. Decisions Made
2. Action Items
3. Responsible Owner
4. Deadline (if mentioned)

Requirements:

- Ignore small talk
- Focus on commitments and outcomes
- Preserve important context
- Use concise language



Example Output

Input

Project planning meeting transcript.

Output

Decision:

Launch delayed by one week.

Action Item:

Sarah to finalize onboarding documentation.

Deadline:

Friday, March 15.



Evaluation Criteria

- Accuracy
- Completeness
- Clarity
- Actionability
- Information Compression



Benchmark Results

GPT-4.1: 9.6/10

Claude Opus: 9.2/10

Gemini 2.5 Pro: 8.9/10



Model Notes

GPT-4.1

Excellent structured extraction.

Claude Opus

Strong contextual understanding.

Gemini 2.5 Pro

Good summarization and organization.



Research Notes

Based on:

- Meeting Effectiveness Research
- Knowledge Management
- Information Extraction
- Organizational Communication



Release: v1.0

Status: Active
