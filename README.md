# 🚀 Mautomate: Modern Automation for Trade Businesses

[![Site Status](https://img.shields.io/website?url=https%3A%2F%2Fmautomate.netlify.app%2F)](https://mautomate.netlify.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

> **Mautomate** is a high-performance AI automation engine designed to help local trades (Plumbing, HVAC, Electrical) capture leads 24/7. It replaces manual paperwork and missed calls with intelligent, autonomous systems.

---

## 🌐 Live Demo & Services
Check out the live dashboard and automation landing page here:  
👉 **[https://mautomate.netlify.app/](https://mautomate.netlify.app/)**

---

## 🛠 Features

- **24/7 AI Receptionist:** Never miss a lead again. Our AI handles inquiries and bookings while you're on the job.
- **Smart Knowledge Base:** Trained on specific business data (services, pricing, and service areas) using RAG (Retrieval-Augmented Generation).
- **Lead Capture & Notifications:** Instant text or email alerts as soon as a customer shows interest.
- **Zero-Code Integration:** Easy-to-install chat widgets for existing business websites.

## 🏗 System Architecture

Mautomate uses a multi-tenant backend architecture to ensure data security and lightning-fast response times.



- **Frontend:** Responsive HTML5/Tailwind CSS hosted on Netlify.
- **Backend API:** FastAPI (Python) for high-concurrency lead handling.
- **AI Brain:** Qwen 3 (1.7B) & Gemma 3 (270M) served via vLLM for ultra-low latency.
- **Security:** Domain-locked CORS and encrypted Business API keys.

## 🚀 Getting Started

If you are a developer looking to contribute or self-host:

### Prerequisites
- Python 3.9+
- [Ollama](https://ollama.com/) or a vLLM instance.

### Installation
1. Clone the repo:
   ```bash
   git clone [https://github.com/your-username/mautomate.git](https://github.com/your-username/mautomate.git)
   cd mautomate
