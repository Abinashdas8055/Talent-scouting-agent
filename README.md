# AI Talent Scouting & Engagement Agent

## What it does
This AI agent helps recruiters save time by automating the candidate screening process end-to-end.

## How it works
1. Recruiter enters a Job Description
2. Agent searches a candidate database and selects TOP 5 most relevant candidates
3. Agent scores each candidate with a Match Score (skills comparison with explainability)
4. Agent simulates a realistic conversation with each candidate to assess Interest Score
5. Agent outputs a fully ranked shortlist the recruiter can act on immediately

## Scoring Logic
- Match Score (0-100): How well candidate skills match the job requirements
- Interest Score (0-100): How interested the candidate is based on simulated conversation
- Final Score = 70% Match Score + 30% Interest Score

## Tech Stack
- Python
- Groq API (LLaMA 3.3 70B model)
- Gradio (UI)
- Google Colab

## How to run
1. Open talent_scouting_agent.ipynb in Google Colab
2. Run Cell 1 to install dependencies
3. Replace YOUR_GROQ_API_KEY_HERE with your free Groq API key
4. Run all cells
5. Enter any Job Description in the UI and click Find Candidates

## Get a free Groq API key
Go to https://console.groq.com and sign up for free

## Live Demo
[Gradio UI - runs when notebook is active]
