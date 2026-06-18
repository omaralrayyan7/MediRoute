# What is MediRoute Project

## Overview

**MediRoute JO** is an AI-powered smart medical referral platform designed to solve a critical gap in Jordan's healthcare system: the absence of a digital referral mechanism between primary healthcare centers and specialists. The current system suffers from patient overcrowding, delayed diagnoses, and fragmented medical records due to manual, phone-based coordination. MediRoute JO addresses this end-to-end.

The platform uses a **machine learning model** to analyze patient-reported symptoms and automatically route them to the most suitable available specialist — factoring in medical need, location, and real-time clinic availability. Referrals are delivered instantly to physicians via **real-time notifications**, eliminating paperwork entirely.

On the **cybersecurity front**, MediRoute JO enforces:
- End-to-end encryption of patient records
- Role-based access control (RBAC)
- An anomaly detection layer that flags unauthorized access to sensitive medical data
- Full compliance with healthcare data protection standards

Built for scalability across Jordan's public and private healthcare sectors, with future potential to support refugee health services and integrate with the national Health Information System.

**MediRoute JO is not just a referral tool — it is a step toward a connected, secure, and AI-driven national healthcare infrastructure.**

---

## Tech Stack

| Layer | Technology |
|---|---|
| Mobile / Frontend | Flutter |
| Backend API | ASP.NET Core |
| Database | MySQL |
| Real-time Notifications | SignalR |
| AI / ML | Symptom-to-specialist routing model |
| Security | E2E encryption · RBAC · Anomaly detection |

---

## Key Features

- **AI Symptom Routing** — ML model matches patient symptoms to the right specialist automatically
- **Real-Time Referrals** — SignalR pushes referral notifications to physicians instantly
- **Secure Medical Records** — Encrypted storage with role-based access per user type (patient, GP, specialist, admin)
- **Anomaly Detection** — Flags and logs suspicious access attempts on patient data
- **Clinic Availability Awareness** — Routes referrals based on specialist availability, not just specialty
- **Scalable Architecture** — Designed to expand across Jordan's public and private health sectors

---

## Future Plans

- Integration with Jordan's national Health Information System (HIS)
- Support for refugee healthcare services
- Expanded ML model trained on larger Jordanian patient datasets
- Multi-language support (Arabic / English)
