# CHIMERA - Railway Operations Control Platform

![CHIMERA](https://img.shields.io/badge/CHIMERA-Railway%20Operations-BC6C25)
![Next.js](https://img.shields.io/badge/Next.js-15.5.3-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0.0-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.3.0-38B2AC)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-10.0.0-0055FF)

CHIMERA is a comprehensive command and control platform for railway operations controllers. The system helps controllers manage train movements efficiently, maintain situational awareness, resolve conflicts, handle disruptions, and optimize overall network performance.

## 🚄 Features

### Situational Awareness
- Live map visualization of the railway network
- Gantt chart for train schedules and timeline view
- Real-time KPIs (on-time percentage, average delay, throughput)

### Proactive Conflict Resolution
- Automated conflict detection (headway, platform, dwell time)
- Plan A/B resolution options with ripple effect preview
- One-click approval for quick decision making

### Safety First
- Hard-rule checks on platforms, blocks, and signals
- Validation of all operations to prevent unsafe conditions
- Visual indicators for severity levels

### Scenario Sandbox
- "What-if" scenario planning with KPI comparison
- Ability to test different operational strategies
- Promote winning plans to live environment

## 🛠️ Tech Stack

- **Frontend**: Next.js 15.5.3 with TypeScript
- **Styling**: Tailwind CSS with custom color palette
- **Animations**: Framer Motion
- **UI Components**: Custom glassmorphic components
- **State Management**: React hooks and context

## 🎨 Design System

CHIMERA features a custom design system with:

- **Color Palette**: 
  - Primary: `#BC6C25` (Brand-700)
  - Secondary: `#DDA15E` (Brand-500)
  - Base: `#FEFAE0` (Brand-100)
  - Full 9-step color scale from 100-900

- **Components**:
  - Glass Cards: Frosted glass effect with subtle shadows
  - Action Buttons: Interactive buttons with hover effects
  - KPI Displays: Clean, data-focused information cards
  - Conflict Chips: Severity-coded issue cards

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0.0 or higher
- npm or yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/chimera.git
   cd chimera
   ```

2. Install dependencies:
   ```
   npm install
   # or
   yarn
   ```

3. Run the development server:
   ```
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 📱 Pages

### Landing Page (`/`)
- Interactive hero section with animated railway track
- Feature showcase with glassmorphic cards
- Interactive demo preview
- Expected impact statistics
- Railway operations insights

### Dashboard (`/app`)
- Real-time KPI monitoring
- Active conflict management
- Interactive map and Gantt chart placeholders
- Scenario cards for quick access to key features

## 🧩 Components

### UI Components
- `GlassCard`: Styled component with frosted glass effect
- `ShineButton`: Interactive button with shine animation
- `AnimatedCounter`: Number counter with animation
- `StatCard`: KPI display with trend indicators

### Functional Components
- `ConflictsPanel`: Manages and displays active conflicts
- `KPIBar`: Shows key performance indicators
- `RailwayTrackAnimation`: Interactive train animation

## 🔄 State Management

The application uses React's built-in state management with hooks:
- `useState` for component-level state
- `useEffect` for side effects and data fetching
- `useRef` for DOM references and measurements

## 🎭 Animations

CHIMERA features rich animations powered by Framer Motion:
- Scroll-driven animations
- Entrance animations for elements
- Interactive hover effects
- Custom railway track animation

## 🌐 Accessibility

The application includes accessibility features:
- High contrast mode toggle
- Text size adjustments
- Keyboard navigation support
- ARIA attributes for screen readers

## 📊 Demo Data

The application uses synthetic data for demonstration purposes:
- Simulated train movements
- Generated conflicts with varying severity levels
- Realistic KPI metrics with trends

## 👥 Contributors

- Aditya Bhushan

---

Developed for Smart India Hackathon (SIH) 2025
