# Resume Optimizer - Multi-LLM

## Overview

A multi-model resume optimization workflow. It receives a resume file and job posting URL via webhook, extracts the resume text, fetches the job posting content, runs parallel analyses using multiple AI models, merges the analyses, synthesizes a final optimized version, generates a PDF, and returns the result. This approach uses multiple LLM perspectives to produce a more comprehensive resume optimization.

## How It Works

```
Webhook (resume file + job URL) -> Extract resume text -> Fetch job posting -> Parallel AI analyses (multiple models) -> Merge analyses -> Synthesize final version -> Generate PDF -> Respond
```

## Integrations

- **OpenAI** - Resume analysis and optimization (multiple models)

## Setup

1. Import `Resume_Optimizer_Multi_LLM.json` into your n8n instance.
2. Configure OpenAI credentials.
3. Activate and send POST requests with resume file and job URL.
