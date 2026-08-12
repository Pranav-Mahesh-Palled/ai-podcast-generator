# AI Podcast Generator

## Overview

Creating podcast content manually requires multiple steps including topic research, script writing, voice recording, audio editing, and publishing.

This project automates podcast creation using Artificial Intelligence.

The workflow accepts a podcast topic from the user, generates an engaging podcast script using Google Gemini, converts the script into natural-sounding speech using Murf AI, and automatically provides the generated podcast audio.

This demonstrates how Generative AI and workflow automation can streamline audio content production.

---

# Problem Statement

Producing podcast episodes manually is time-consuming because it requires:

- Topic research
- Script writing
- Voice recording
- Audio production

Many content creators struggle to consistently create podcast episodes.

The goal of this project is to automate podcast generation using Artificial Intelligence.

---

# Solution

This workflow automatically:

1. Receives a podcast topic from the user.
2. Generates a conversational podcast script using Google Gemini.
3. Sends the script to Murf AI.
4. Converts the script into natural speech.
5. Downloads the generated podcast audio.
6. Delivers a ready-to-use podcast episode.

---

# Workflow Architecture

```
User Topic
     │
     ▼
Chat Trigger
     │
     ▼
Google Gemini
(Podcast Script Generation)
     │
     ▼
Murf AI
(Text To Speech)
     │
     ▼
Audio Download
     │
     ▼
Podcast Output
```

---

# Workflow Explanation

## Step 1 — Topic Input

The workflow begins when a user enters a topic.

Example:

```
Artificial Intelligence in Healthcare
```

The topic becomes the input for podcast generation.

---

## Step 2 — Podcast Script Generation

Google Gemini creates a conversational podcast script.

The generated script:

- Uses a friendly tone
- Sounds natural when spoken
- Is designed for approximately 2 minutes of audio
- Focuses on listener engagement

---

## Step 3 — Text-to-Speech Conversion

The generated script is sent to Murf AI.

Murf AI converts the text into a realistic human voice.

Features:

- Natural speech synthesis
- High-quality voice output
- Professional podcast narration

---

## Step 4 — Audio Generation

Murf AI generates the audio file and returns an audio URL.

The workflow automatically processes the response.

---

## Step 5 — Podcast Download

The generated podcast audio is downloaded automatically.

The final output is a ready-to-use podcast recording.

---

# Technologies Used

- n8n
- Google Gemini 2.5 Flash
- Murf AI
- Text-to-Speech (TTS)
- REST APIs
- Prompt Engineering
- Workflow Automation

---

# AI Models Used

## Google Gemini 2.5 Flash

Used for:

- Podcast script generation
- Content structuring
- Topic understanding

---

## Murf AI

Used for:

- Voice synthesis
- Audio generation
- Text-to-Speech conversion

---

# APIs Used

- Google Gemini API
- Murf AI API

---

# Workflow Features

✔ Automated Podcast Script Generation

✔ AI-Powered Content Creation

✔ Text-to-Speech Conversion

✔ Podcast Audio Generation

✔ End-to-End Automation

✔ Beginner Friendly

✔ Scalable Architecture

---

# Repository Structure

```
AI-Podcast-Generator/

│
├── README.md
├── AI Podcast Generator.json
├── Screencast AI-Podcast-Generator.mp4
├── screenshots/
│      ├── workflow.png
│      └── output.png
└── LICENSE (Optional)
```

---

# How to Import the Workflow

## Step 1

Install n8n.

---

## Step 2

Clone the repository.

```bash
git clone <repository-url>
```

---

## Step 3

Open n8n.

---

## Step 4

Select:

Import Workflow

---

## Step 5

Import:

```
AI Podcast Generator.json
```

---

## Step 6

Configure credentials:

- Google Gemini API
- Murf AI API

---

## Step 7

Activate the workflow.

---

# Expected Output

Input:

```
The Future of Artificial Intelligence
```

Output:

- AI-generated podcast script
- Natural-sounding podcast narration
- Downloadable podcast audio

---

# Learning Outcomes

This project helped me gain experience in:

- Generative AI
- Prompt Engineering
- Large Language Models
- Text-to-Speech Systems
- AI Voice Generation
- API Integration
- Workflow Automation
- Audio Content Creation

---

# Future Improvements

Potential enhancements include:

- Multi-speaker podcast generation
- Background music integration
- Podcast publishing automation
- Voice customization
- Multi-language support
- Episode scheduling
- Podcast analytics

---

# Author

**Pranav Mahesh Palled**

Computer Science and Engineering Student

Interested in Artificial Intelligence, Generative AI, Machine Learning, Intelligent Automation, Workflow Orchestration, and Emerging Technologies.

---

⭐ If you found this project useful, consider giving it a star on GitHub.
