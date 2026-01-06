# 🏦 Consumer Lending – AI-Powered Multi-Agent Prescreening System

A fully automated customer onboarding & loan prescreening system built using Autogen + GPT-4o-mini.
--

## 🚀 Overview

This project uses a multi-agent LLM architecture to automate the complete early-stage customer onboarding workflow in the lending industry.

The system includes:

## 🧩 1. Profile Info Collection Agent

- Collects customer name & mobile number only.

## 🎯 2. Loan Preference Agent

Captures the loan type the customer is interested in:

- Home Loan

- Personal Loan

- Education Loan

- Gold Loan

## 📄 3. Loan Documents Checklist Agent

- Provides loan-specific documentation requirements automatically.

## 🧍 4. Customer Proxy Agent

- A human-simulation agent for testing multi-agent flows.

--

## 🧠 Tech Stack

- Python

- Autogen

- GPT-4o-mini

- Gradio (optional for UI)

--

## 📁 Project Structure
│── main.py (agent definitions + chat workflows)
│── autogen workflow (ConversableAgents)
│── Multi-agent orchestration

-- 

## 🧪 Features

✔ Fully autonomous LLM agent-to-agent conversations
✔ JSON-based structured summaries
✔ Dynamic document checklist generation
✔ Modular agents for clean architecture
✔ Works with OpenAI GPT-4o-mini or any supported LLM

--

## ▶️ How to Run
pip install autogen gradio
python main.py

--
