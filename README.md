# AI Email Assistant

A simple n8n workflow that automatically summarizes Gmail emails using a local AI model and saves the results to Google Sheets.

## Features

* Automatically detects new Gmail emails
* Cleans HTML email content
* Summarizes emails with Llama 3.2 3B
* Extracts required actions
* Extracts important dates and times
* Saves results to Google Sheets

## Workflow

```text
Gmail
  ↓
Get Email
  ↓
Clean Email
  ↓
Llama 3.2 3B
  ↓
Parse Result
  ↓
Google Sheets
```

## Built With

* n8n
* Ollama
* Llama 3.2 3B
* Gmail
* Google Sheets
* JavaScript

## Output

Each email is saved with:

* Sender
* Subject
* Received date
* Summary
* Action Required
* Important Date
