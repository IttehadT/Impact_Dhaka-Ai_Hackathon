🚀 **Live Demo:** [https://ittehadt.github.io/nagorikhub-mvp/index.html](https://ittehadt.github.io/nagorikhub-mvp/index.html)

---

# NagorikHub 🏙️
**AI Rental & Living Intelligence Platform for Bangladesh**

*“We use AI to turn fragmented housing data into trusted, actionable living intelligence.”*

## ⚠️ The Problem
Every year, millions of Bangladeshis relocate for work, education, and family. Currently, making one of the biggest financial decisions of their lives relies on almost no reliable data. 

Current rental platforms only show you photos and a price. They lack:
* **Verified Utility Data:** No transparency on gas types (pipeline vs. cylinder), electricity load-shedding frequency, or water sources.
* **Safety Insights:** No way to gauge if a neighborhood is safe for a tutor visiting at 9 PM or a professional returning from a late shift.
* **Real Sentiment:** No community-driven reviews or data-backed risk analysis.

**The Result:** Poor decisions, hidden costs, and compromised safety.

## 💡 The Solution
**NagorikHub** transforms traditional rental listings into a full decision intelligence system. Instead of just showing properties, the platform acts as a community intelligence layer that provides verified utility insights, safety and livability scoring, and AI-generated area intelligence. 

Renting a home shouldn't be a leap of faith. NagorikHub ensures it is an informed decision backed by data.

## ✨ Key Features (MVP)
* **Listing Intelligence:** Property cards featuring not just rent, but verified utility badges (Gas type, Water source, Electricity Uptime).
* **Livability Score (Free):** A composite score dynamically generated using safety metrics, utility reliability, amenities, transport, and community reviews.
* **Tutor Confidence Score (Free):** A unique metric designed specifically for tutors and home-visit workers, factoring in day/night safety, transport access, and area sentiment.
* **Deep Report (Premium - ৳49):** Detailed risk breakdowns, 6-month rent predictions, and full historical utility data.
* **AI Chatbot (RAG):** Context-aware AI assistant. Users can ask questions like *"Is this area safe for tutoring at night?"* and the system retrieves real review context and data to answer.

## 👥 Target Users
* **Primary:** Tenants (Students, young professionals, families) relocating within or to Dhaka.
* **Secondary:** Tutors, freelancers, and shift workers who need hyper-specific safety and transport data.
* **Tertiary:** Verified Landlords and Brokers seeking to attract tenants by providing transparent data.

## 🛠️ Tech Stack (Current MVP Prototype)
This repository contains the functional, high-fidelity frontend MVP designed for rapid iteration and demonstration.
* **Frontend:** HTML5, CSS3 (Vanilla / Custom variables), JavaScript (Vanilla)
* **Design System:** Custom CSS Grid & Flexbox layouts, Google Fonts (Syne, DM Sans)
* **Deployment:** GitHub Pages

*Note: The platform is designed to scale into a Next.js + Supabase + Python (FastAPI) microservice architecture for production, handling the RAG vector database and LLM integrations.*

## 🚀 How to Run Locally
Since this MVP is built with pure HTML/CSS/JS, no complex build steps or node modules are required!

1. Clone the repository:
   ```bash
   git clone [https://github.com/ittehadt/nagorikhub-mvp.git](https://github.com/ittehadt/nagorikhub-mvp.git)
