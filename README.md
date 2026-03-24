# मंत्री मित्र — Mantri Mitra AI v2.0

AI-Powered Constituency Management System for Indian MLAs/MPs/Public Officials

## 🆕 What's New in v2.0

### ✅ Fixes & Core Improvements
- **localStorage Persistence** — All data (issues, meetings, speeches, documents, calendar, settings, voter DB, RTIs) now survives page refresh via `usePersist()` hook
- **Mobile-first Redesign** — Dedicated bottom navigation bar on mobile, larger 44px touch targets, smooth page transitions, iOS safe-area insets

### 🚀 New Features
- **👥 Voter / Contact Database** — Store and manage constituency contacts with ward, category, tag (Supporter/Neutral/Volunteer etc.), pending issues, and direct Call/SMS/WhatsApp actions
- **⚖️ RTI Tracker** — File and track Right to Information requests with department, deadlines, overdue alerts, status updates (Pending → First Appeal → CIC Filed)
- **🔔 Notification Center** — Bell icon in header shows unread count; auto-alerts for critical issues and overdue RTIs; tap to mark read/dismiss
- **💬 WhatsApp / SMS Share** — Share speeches and document summaries via WhatsApp, SMS, or copy-to-clipboard; available on all speech and document cards

### 📱 Mobile UX
- Bottom tab navigation (Dashboard, Issues, Speeches, Voters, More)
- Quick-action horizontal scroll row on Dashboard
- Clickable stat cards navigate directly to their pages
- All pages have proper bottom padding to avoid bottom nav overlap
- Settings > Data > Quick Navigation grid for accessing all 9 sections

## Setup
```bash
npm install
# Add VITE_OPENROUTER_KEY to .env
npm run dev
```

## Deploy
Push to GitHub and connect to Vercel. Add `VITE_OPENROUTER_KEY` in Vercel environment variables.

---
© 2026 Team Daksha · Built with React + Vite
