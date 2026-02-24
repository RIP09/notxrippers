# ⚡ NOTxRIPPERS (NxR) - Official Organization Portal

![ESTD](https://img.shields.io/badge/ESTD-2026-00D1FF?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active_Deployment-success?style=for-the-badge)
![Tech Stack](https://img.shields.io/badge/Tech-HTML5%20|%20Tailwind%20|%20Supabase-1E1E1E?style=for-the-badge)

Welcome to the official source code repository for **NOTxRIPPERS**, an elite, next-generation esports organization. This portal serves as our central command, handling everything from public relations to secure recruitments and member authentication.

## 🌐 Overview
This project is a single-page application (SPA) architecture built for speed, aesthetic dominance, and seamless user interaction. It features a dark, tactical UI/UX design and integrates securely with decentralized databases and communication protocols.

## ✨ Core Infrastructure & Features

* **[ SECURE ID ] Member Authentication:** Powered by **Supabase**. Allows verified personnel to register, log in, and access their official NxR Identity Cards.
* **[ INTEL ] Live Traffic Analytics:** Integrates `IPAPI` and `CounterAPI` to track live global hits and display the connecting user's origin country in a terminal-style interface.
* **[ RECRUITMENT ] Talent Acquisition:** Embedded seamless Google Forms integration to capture high-tier esports talent applications directly from the digital arena.
* **[ COMMS ] Direct Command Uplink:** Built-in contact module utilizing **FormSubmit** to securely route user queries, WhatsApp numbers, and emails directly to the organization's central inbox (`notxrippers@gmail.com`) without exposing backend server logic.
* **[ UI/UX ] Cyber-Tactical Design:** Fully responsive glass-morphism UI built with **Tailwind CSS**, featuring custom font typographies (`Syncopate` & `Space Grotesk`) and neon-accents (`#00D1FF`).

## 🛠️ Technology Stack

* **Frontend Engine:** HTML5, Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (via CDN for rapid deployment)
* **Backend / Auth:** Supabase (PostgreSQL & GoTrue Auth)
* **API Integrations:** * `FormSubmit` (Mail routing)
  * `ipapi.co` (Geolocation)
  * `counterapi.dev` (Traffic metrics)

## 🚀 Deployment Instructions

This architecture is entirely serverless and relies on CDN-delivered assets. To deploy or test locally:

1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/notxrippers.git](https://github.com/your-username/notxrippers.git)
