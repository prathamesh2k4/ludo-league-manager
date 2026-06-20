# Ludo League Arena Tracker

A lightweight, real-time gaming ledger and standing engine built for local Ludo tournaments and casual group matches. This app tracks accumulated daily losses, keeps an active player leaderboard, and lets you generate instant settlement alerts directly to WhatsApp.

## Live Demo
Hosted automatically via Netlify: [INSERT YOUR NETLIFY LINK HERE]

---

## Features

* Real-Time Standings: Instantly updates ranks and tracks total aggregated group loss.
* Transaction Audit Stream: Keeps a complete log of every game entered with custom delete controls.
* One-Click WhatsApp Share: Generates a clean, simple message with the player's name, league name, amount owed, and a dynamic UPI QR code link.
* Image Report Export: Download high-resolution PNG copies of your standings table to drop into your group chats.
* Supabase Powered: Secure cloud storage configuration ensures your ledger data is never lost.

---

## Tech Stack

* Frontend: HTML5, Tailwind CSS, Vanilla JavaScript
* Database: Supabase (PostgreSQL)
* Plugins: Html2Canvas (Image Export), Google Fonts, QR Server API

---

## How to Use

1. Open the application link.
2. Enter your group or personal UPI ID in the Payment Destination box on the dashboard.
3. Create a room or league name for your current gaming tournament.
4. Input the player's name and loss amount whenever a match finishes.
5. Click "Share" in the audit stream table to send a quick payment request via WhatsApp.
