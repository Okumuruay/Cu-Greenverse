# CU GreenVerse

> Gamifying campus sustainability at Chulalongkorn University by turning eco-commutes and green habits into verifiable impact and rewards.

---

## Overview

**CU GreenVerse** is a Progressive Web App (PWA) designed to incentivize eco-friendly living across Chulalongkorn University. By gamifying daily campus transit and sustainable activities, the platform converts green choices into redeemable local rewards, real-time carbon offset metrics, and friendly community competition.

---

## Key Features

*   **Eco-Transit Integration:** Native QR scanning for CU POP BUS rides and tracking integration for Anywheel bike sharing.
*   **Activity Logging & Carbon Analytics:** Interactive user dashboards featuring visual trend charts to log daily actions, track carbon offset, and store submission histories.
*   **Gamification & Rewards Engine:** Dynamic eco-point calculations powering campus-wide leaderboards and an integrated partner marketplace for local reward redemption.
*   **Dual-Role Dashboards:** Personal portals for students and staff alongside administrative controls for activity verification, vendor management, and campus impact metrics.
*   **Mobile-First PWA:** Lightweight Progressive Web App architecture built for instant mobile deployment and multi-language support (i18n).

---

## Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend Framework** | Next.js (App Router), React 19, TypeScript |
| **Styling & UI** | Tailwind CSS, Lucide React, Custom Theme Provider |
| **Backend & Auth** | Supabase (PostgreSQL Database, Auth, RLS) |
| **Features & Visuals** | Next PWA Service Workers, Recharts (Analytics), Sonner |

---

## My Key Contributions

*   **UI/UX & Handcrafted Aesthetic:** Redesigned core user flows (Lobby, Login, Rewards, Profile, and updated Statistics view) using a softer, handcrafted visual design tailored for mobile surfaces.
*   **Theme Infrastructure & Light Mode Fixes:** Configured the application to default to light mode, resolved theme initialization issues in `ThemeProvider.tsx`, and cleared dark-mode artifact fragments across mobile screens.
*   **Mobile Leaderboard Optimization:** Replaced overflowing tables in `LeaderboardTable.tsx` with a responsive, stacked card layout to allow seamless browsing of faculty rankings on mobile devices without horizontal scrolling.
*   **Profile Suite & Green Passport Feature:** Restored and enhanced the profile page layout, implemented the new **Green Passport** tab, added React `Suspense` loading fallbacks (`loading.tsx`), and resolved routing conflicts.
*   **Mock Data & Preview Resilience:** Restored activity flows and established mock data fallbacks in `mockActivities.ts` to ensure consistent UI rendering and offline-friendly local development.
*   **Build Validation & Version Control:** Debugged TypeScript compilation issues, resolved git rebase conflicts on `main`, validated production builds via `npm run build`, and managed clean deployments.

---

## 🚀 Getting Started

### Prerequisites

*   Node.js 18+ 
*   npm, yarn, or pnpm
*   A Supabase project instance

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/cu-greenverse.git](https://github.com/your-username/cu-greenverse.git)
   cd cu-greenverse
