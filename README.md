# FreightLayer Broker Control Tower

A production-ready desktop logistics operations dashboard with gate-based workflow system, comprehensive load management, carrier settlement, claims processing, and enterprise-grade features.

## 🚀 Overview

FreightLayer Broker Control Tower is an enterprise-grade logistics TMS (Transportation Management System) dashboard designed specifically for freight brokers. It features a sophisticated gate-based workflow system that tracks loads through 7 operational gates, real-time operational health monitoring, and comprehensive financial management.

### Key Features

- **Gate-Based Workflow System** - 7-gate operational flow (Distribution → Dispatch → Booking → Execution → Delivery → Invoice → Settlement)
- **Real-Time Load Management** - Track 500+ active loads with live status updates
- **Operational Health Monitoring** - Visual indicators for gate bottlenecks and blockers
- **Carrier Settlement** - Automated payment processing and settlement tracking
- **Claims Management** - Full claims lifecycle from filing to resolution
- **Document Management** - Upload, track, and manage BOL, POD, Rate Cons, invoices
- **Booking Request System** - Public-facing forms for customer and carrier booking requests
- **KPI Dashboard** - Real-time metrics with customizable thresholds
- **Advanced Filtering** - Multi-dimensional filtering with saved views
- **Notifications System** - Real-time alerts for SLA breaches, document requirements, status changes

## 🎨 Design System

- **Frame Width:** 1440px
- **Background:** Midnight black (#0A0A0F)
- **Font:** Inter
- **Spacing Grid:** 8px base unit
- **Sidebar:** 280px (expanded) / 64px (collapsed)
- **Drawer Width:** 280px (standardized)
- **No shadows, gradients, or improvised styling**

## 🏗️ Architecture

### Tech Stack

- **Frontend:** React 18 + TypeScript
- **Routing:** React Router v7 (Data mode)
- **Styling:** Tailwind CSS v4
- **UI Components:** Radix UI + shadcn/ui
- **Maps:** Google Maps API
- **Charts:** Recharts
- **Icons:** Lucide React + Material UI Icons
- **State Management:** React hooks + Context
- **Build Tool:** Vite 6

### Project Structure

```
src/
├── app/
│   ├── components/          # Reusable UI components
│   │   ├── ui/             # Base UI components (shadcn)
│   │   ├── modals/         # Modal components
│   │   └── figma/          # Figma-specific components
│   ├── pages/              # Page components (routes)
│   ├── api/                # API client and services
│   │   ├── services/       # API service layers
│   │   ├── adapters/       # Data adapters
│   │   └── types.ts        # API type definitions
│   ├── data/               # Mock data
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # Utility libraries
│   ├── state/              # State management
│   ├── types/              # TypeScript type definitions
│   ├── utils/              # Utility functions
│   ├── routes.tsx          # React Router configuration
│   └── App.tsx             # Root component
├── styles/                 # Global styles
│   ├── theme.css          # Design tokens
│   ├── fonts.css          # Font imports
│   └── index.css          # Global CSS
└── imports/                # Imported assets
```

## 🔧 Installation

### Prerequisites

- Node.js 18+ 
- npm, pnpm, or yarn

### Setup

1. Clone the repository:
```bash
git clone https://github.com/Yom-MR/freightlayer-broker-control-tower.git
cd freightlayer-broker-control-tower
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
# or
yarn install
```

3. Set up Google Maps API (optional for map features):
   - Get API key from Google Cloud Console
   - See `GOOGLE_MAPS_SETUP.md` for detailed instructions

4. Start development server:
```bash
npm run build
# Then open in browser or deploy
```

## 📚 Full Documentation

Complete source code and documentation files will be added in subsequent commits.

See the full blueprint document `freightlayer-build-integration-blueprint.md` (included in source) for:
- 28 screens and routes
- 40+ reusable components
- 25+ data entities
- 15+ critical user flows
- 50+ API endpoints
- Complete feature specifications

---

**Built with ❤️ for freight brokers**

**Tech Stack:** React 18 · TypeScript · Tailwind CSS v4 · React Router v7 · Radix UI · Google Maps API · Recharts