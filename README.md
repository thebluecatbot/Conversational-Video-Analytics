# Conversational Video Analytics

A Streamlit-based system that converts long YouTube videos into concise, decision-ready summaries using Gemini 1.5 Flash.

---

## Overview

Users paste a YouTube link, and Smart-Read:
- Extracts the transcript
- Sends it to Gemini
- Produces structured summaries

The system is cloud-deployed and multi-user.

---

## Architecture

- Streamlit UI
- Gemini 1.5 Flash for summarization
- YouTube Transcript API
- Secure API key handling via environment variables

---

## Deployment

Deployed on Streamlit Community Cloud:
- Public URL
- Stateless execution
- Multi-user
- No authentication
- No database

---

## Repository Structure

