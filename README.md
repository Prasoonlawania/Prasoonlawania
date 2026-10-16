<div align="center">

  <img src="./public/images/prasoon-hero.jpeg" alt="Prasoon Lawania" width="240" />

  # Prasoon Lawania

  **AI/ML Developer · Intelligent Systems · Full-Stack Engineering**

  *Building intelligent systems that solve real-world problems.*

  [![GitHub](https://img.shields.io/badge/GitHub-Prasoonlawania-181717?style=for-the-badge&logo=github)](https://github.com/Prasoonlawania)
  [![EC-AMS Live](https://img.shields.io/badge/Live-EC--AMS-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ec-ams.web.app/)
  [![CSFAQ](https://img.shields.io/badge/Repository-CSFAQ-7C3AED?style=for-the-badge&logo=github)](https://github.com/Prasoonlawania/cs49)

</div>

---

## About this portfolio

This portfolio presents my work across AI/ML, full-stack development, real-time collaboration, and practical software systems. It is designed to make the projects, technical decisions, and engineering work easy to explore.

## Featured projects

### EC-AMS — Engineering College Bharatpur Attendance Management System

An attendance management platform with role-specific experiences for principals, heads of department, teachers, and students.

- Subject-wise attendance calculations and shortage alerts.
- Timetable and laboratory scheduling, leave processing, and notices.
- JWT-based authentication and attendance workflows.
- AI-based face-recognition attendance and QR-based attendance features, as implemented in the project.

**Live portal:** [ec-ams.web.app](https://ec-ams.web.app/)

### Praxa — Real-Time Messaging & AI Collaboration

A real-time communication and collaboration platform featuring:

- Bidirectional messaging with Socket.IO and Cloud Firestore.
- Audio/video calling using WebRTC.
- Voice messaging with a waveform visualizer.
- An integrated Google Gemini AI assistant.

### JAKCURE — Pet Care & Clinic Management SaaS

A clinic-management system built around practical veterinary workflows.

- POS billing with pack-size and fractional-dosage pricing.
- FIFO inventory tracking with manufacturing and expiry dates.
- Stock adjustments when invoices are modified.
- Thermal receipt and A4 invoice PDF generation.

Public screenshots should be sanitized before publishing to protect client and patient information.

### AI-Driven Farmer Query Intelligence System

An agricultural query system that combines text classification and similarity-based retrieval.

- Categorizes queries across weather, pests, nutrients, markets, schemes, and other topics.
- Uses TF-IDF feature extraction and Multinomial Naive Bayes classification.
- Retrieves similar historical resolutions using cosine similarity.

**Repository:** [raksha-ai-agriculture-project](https://github.com/Prasoonlawania/raksha-ai-agriculture-project)

### VINS-Connect — Intern FAQ Dashboard

A collaborative student FAQ platform developed during work with Vicharanashala Lab, IIT Ropar.

- Peer-generated answers and crowd-voted responses.
- Authentication and role-based access.
- A reusable knowledge base for common student questions.

**Repository:** [cs49](https://github.com/Prasoonlawania/cs49)

## Technical toolkit

<div align="center">

  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
  ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
  ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
  ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

## Portfolio website setup

This repository is built with Next.js, React, TypeScript, Tailwind CSS, and Framer Motion.

### Requirements

- Node.js 18 or later
- npm or pnpm

### Run locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

### Optional AI assistant configuration

Create `.env.local` in the project root if you use the corresponding backend integration:

```env
PRAXA_API_BASE_URL=http://localhost:5000
# Or configure a server-side Gemini API key:
GEMINI_API_KEY=your_key_here
```

Keep real API keys out of source control. Do not expose secret credentials in client-side code.

### Production build

```bash
npm run build
npm start
```

## Privacy

- Publish only screenshots that have been reviewed and sanitized.
- Do not commit client or patient names, phone numbers, email addresses, financial details, or other private records.
- Keep API keys and other secrets in environment variables.

---

<div align="center">

  **Curiosity drives the idea. Engineering brings it to life.**

  [GitHub Profile](https://github.com/Prasoonlawania) · [EC-AMS Live Portal](https://ec-ams.web.app/)

</div>
