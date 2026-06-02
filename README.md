# 🤖 n8n AI Agent Portfolio

## 🚀 Overview

Portfolio of **production-ready AI agents** built with n8n, featuring advanced integrations across telecommunications, real estate, content creation, customer service, and financial processing. These agents handle real-time processing and intelligent decision-making.

**Impact**: 95% reduction in manual processing | Zero missed follow-ups | Complete audit trails

---

## 🤖 Featured Agents

### 1️⃣ 📞 AI Voice Conversation Agent
![Conversation Agent](Conversation%20Agent%20(n8n+retell+ytel).jpeg)

**AI-powered voice platform** managing outbound/inbound calls with intelligent disposition tracking across **3 interconnected workflows**.

**Tech Stack**: Ytel • RetellAI • n8n

**Key Features**:
- Automated outbound dialing with AI agents
- Real-time inbound routing with instant TwiML response
- Smart disposition updates (OPTED_OUT, CALLBACK_REQUESTED, CALL_COMPLETED)
- Intelligent call transfer management with retry logic

---

### 2️⃣ 🏠 AI Foreclosure Lead System
![AI Foreclosure Agent](Ai%20Foreclouser%20agent.jpeg)

**Fully automated foreclosure pipeline** from lead capture to CRM qualification with zero manual intervention.

**Tech Stack**: n8n • Skip-Tracing APIs • PropStream • GoHighLevel

**Key Features**:
- Automated lead ingestion from multiple sources
- Skip-tracing for contact enrichment
- Multi-criteria validation engine
- Intelligent lead qualification (Hot/Warm/Cold)
- Automatic CRM distribution and appointment scheduling

**Workflow**: Lead Capture → Validation → Skip Trace → Normalize → CRM Entry → Qualification → Appointment Logic → Logging

---

### 3️⃣ ✍️ Blog Posting Agent
![Blog Posting Agent](Blog%20Posting%20Agent.jpeg)

**Automated content creation and multi-platform publishing**

**Key Features**: AI Content Generation • Smart Scheduling • SEO Optimization

---

### 4️⃣ 📧 Email Reply Agent
![Email Reply Agent](Email%20Reply%20Agent.jpeg)

**Intelligent inbox automation** with context-aware AI responses and smart routing.

**Key Features**: AI-Powered Responses • Multi-Account Support • Intent Recognition

---

### 5️⃣ 💰 Invoice Processing Agent
![Invoice Processing Agent](Invoice%20Processing%20Agent.jpeg)

**ML-powered invoice automation** with OCR extraction and accounting integration.

---

### 6️⃣ 💼 LinkedIn Posting Agent
![LinkedIn Posting Agent](Linkedin%20Posting%20Agent.PNG)
![Automated Linkdein Post](https://github.com/user-attachments/assets/001fbe99-c3b2-4417-9ddd-30c396423042)

**Automated LinkedIn strategy** with engagement optimization and network growth.

**Tech Stack**: 
- Hugging Face FLUX-1 Model **(free)** for image generation
- Gemini API
- Google sheets
- Linkedin

**Key Features**: Content Scheduler • AI Post Generation • Hashtag Optimization

---

### 7️⃣ 🎥 YouTube Posting Agent
![YouTube Posting Agent](Youtube%20Posting%20Agent.jpeg)

**Youtube video link**
https://youtube.com/shorts/sZ0tXZ_cm9s?si=S0vV_8fja0qf-2kV
https://youtube.com/shorts/1NmPa_umv-0?si=Hj20NphHCZct5cvz

**End-to-end YouTube pipeline** from upload to optimization with analytics-driven strategy.

**Tech Stack**
- Decart.ai **(FREE)** for video generatoin
- Google sheets
- Gemini
- Youtube


---
### 8️⃣ 📧 AI Email Marketing Automation Agent
<img width="1266" height="602" alt="image" src="https://github.com/user-attachments/assets/f7866546-5f13-47ad-90bb-c2cee00498f9" />


**Automated real estate email engine** built in n8n for structured lifecycle driven outreach and engagement tracking.

**Tech Stack:** n8n • Apollo • HubSpot • Google Sheets • Webhooks

**Key Features:**

• Automated property sync with smart rotation
• Lead sourcing and enrichment via Apollo
• CRM lifecycle mapping and deduplication
• Daily personalized outreach automation
• Real time engagement tracking and lead scoring
• Automatic MQL promotion and notifications
• Structured follow up cadence control

**Workflow:** Property Sync → Lead Enrichment → CRM Sync → Daily Outreach → Engagement Tracking → Qualification → Follow Up Logic

**📈 Impact:**

• Scalable outreach system
• Controlled sending with zero spam risk
• Automated qualification and sales readiness

---

### 9️⃣ 🔐 NMC PIN Verification Bot

![Status](https://img.shields.io/badge/Status-Production-brightgreen) ![Python](https://img.shields.io/badge/Python-Automation-blue)

**Fully automated healthcare registration verification system** that handles bulk candidate PIN checks, manages CAPTCHA flow, classifies results, and updates live CRM records.

**Tech Stack**: Python • Automation • Speech-to-Text • CRM Integration • Excel Reporting

**Key Features**:
- Audio CAPTCHA bypass using speech-to-text transcription
- Five-state outcome polling with smart terminal state handling
- Dual storage with local database and Excel reporting
- Live CRM integration for real-time candidate record updates
- Atomic file writes to prevent OS-level locking errors

**Workflow**: Candidate List → Portal Login → CAPTCHA Bypass → PIN Submission → Status Polling → Result Classification → CRM Sync

**📈 Impact:**

• Eliminated manual registration checking  
• Handles bulk candidate lists overnight  
• Full audit trail for every verification result  

---

### 🔟 🖥️ Compliance Document Automation Bot

![Status](https://img.shields.io/badge/Status-Production-brightgreen) ![Desktop Automation](https://img.shields.io/badge/Desktop-Automation-orange)

**Desktop automation bot** that operates a staffing CRM to download compliance documents for candidates without manual interaction.

**Tech Stack**: Python • Desktop Automation • OCR • CRM Automation • PDF Processing

**Key Features**:
- UI automation based CRM navigation
- OCR-driven candidate search and status detection
- Multiple compliance document types handled and classified
- Intelligent attachment detection through visual scanning
- Optimized API payload handling for large document batches

**Workflow**: Candidate List → CRM Login → Candidate Search → Compliance Tab → Document Type Detection → PDF Download → Storage

**📈 Impact:**

• Full compliance document pipeline with zero manual CRM interaction  
• Scales across unlimited candidates per run  
• Consistent document classification for downstream processing  

---

### 1️⃣1️⃣ 📄 AI CV Preparation Pipeline

![Status](https://img.shields.io/badge/Status-Production-brightgreen) ![n8n](https://img.shields.io/badge/n8n-Workflow-red) ![GPT-4.1](https://img.shields.io/badge/GPT--4.1-Powered-purple)

**End-to-end AI-powered CV rewriting and generation pipeline** that converts raw candidate data into polished, formatted CVs ready for submission across multiple healthcare staffing clients.

**Tech Stack**: n8n • GPT-4.1 • Google Docs • CRM Integration • Webhooks

**Key Features**:
- GPT-4.1 duty generation with conditional branching logic per role type
- Code-side employment gap detection with month-precision
- Template-based document generation using anchor placeholders
- Styled employment tables with enforced formatting
- Automatic gap declaration highlighting for compliance visibility
- Call transcription data support where applicable
- Auto-upload to CRM with correct record routing per client

**Workflow**: Webhook Trigger → Call Transcription → AI CV Rewrite → Gap Detection → Doc Template Population → PDF Export → CRM Upload

**📈 Impact:**

• CV prep time reduced from 30-45 minutes to under 3 minutes  
• Production-deployed across multiple clients  
• Consistent formatting with zero manual document editing  
• Gap detection fully automated and reliable  

---

### 1️⃣2️⃣ 🗂️ Timesheet Processing Web App

![Status](https://img.shields.io/badge/Status-Production-brightgreen) ![Web App](https://img.shields.io/badge/Web-App-teal)

**Web-based timesheet submission and processing application** for staffing operations, replacing manual paper and email-based timesheet handling with a structured digital workflow.

**Tech Stack**: Web App • Database • Automation • Validation Logic • CRM / Payroll Ready

**Key Features**:
- Clean web UI accessible without local installation
- Database-backed persistence that survives session resets
- Full submission history per worker
- Structured validation before processing
- Designed for downstream payroll and CRM integration

**Workflow**: Timesheet Submission → Data Validation → Persistent Storage → Submission History → Payroll / CRM Integration

**📈 Impact:**

• Replaced manual email and paper timesheet flow  
• Persistent history for full audit tracking  
• Scalable across multiple clients and worker pools  

---

## 💡 Core Capabilities

**🔄 Multi-System Integration** • **🤖 AI-Powered Automation** • **📊 Real-Time Processing** • **📈 Scalable Architecture** • **⚡ Event-Driven Workflows**

---

## 🛠️ Technologies

**Platform**: n8n • Node.js  
**AI/ML**: OpenAI GPT • RetellAI  
**Databases**: PostgreSQL • Google Sheets  
**APIs**: REST • Webhooks • GraphQL  
**Telecom**: Ytel • Twilio  
**CRM**: Salesforce • HubSpot • GoHighLevel  
**Content**: WordPress • Medium • Ghost  
**Social**: LinkedIn • YouTube  

---

## 📈 Results & Impact

✅ **95%** reduction in manual processing time  
✅ **Zero** missed follow-ups or forgotten tasks  
✅ **Real-time** synchronization across all systems  
✅ **Scalable** framework supporting unlimited workflows  

---

## 👨‍💻 About

**Sheraz Bin Tahir** | Automation Engineer | AI Systems Builder

This portfolio showcases production-grade automation systems with proven business impact. Each agent demonstrates advanced workflow orchestration, AI integration, and multi-system connectivity.

---

**Built with ❤️ and n8n.**
