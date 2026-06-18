# AI-Powered Job Finder using n8n

An automated job discovery system built using n8n, Groq AI, RSS feeds, and Telegram.

## Features

- Collects jobs from multiple sources
- Merges and filters job listings
- Uses Groq LLM to analyze job relevance
- Sends job alerts via Telegram
- Runs automatically using Schedule Trigger

## Tech Stack

- n8n
- Groq AI
- Telegram Bot API
- RSS Feeds

## Workflow

Schedule Trigger
↓
RSS Sources
↓
Merge
↓
Filter
↓
AI Agent (Groq)
↓
Telegram Alerts
