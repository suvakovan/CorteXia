# CorteXia - Your Life, Understood. Powered by AI.

A unified, AI-powered personal life operating system designed with surgical precision, calms authority, and invisible elegance. CorteXia integrates every dimension of personal life management into one intelligent system.

## Vision

CorteXia is the world's first unified personal life operating system that competes with and surpasses fragmented productivity tools like Notion and Obsidian. It treats your life as a cohesive system, not isolated domains.

### Core Concept

CorteXia integrates ALL aspects of personal life management into ONE intelligent system:

- **Tasks & To-Dos** - Hierarchical task management with priority and time tracking
- **Time Tracking** - Deep analytics on how you spend your hours with focus quality metrics
- **Habit Tracking** - Streak-based habit management with GitHub-style calendar visualization
- **Finance Tracking** - Budget management, spending analytics, and financial insights
- **Study Sessions** - Learning goal tracking with subject breakdown and focus level monitoring
- **Screen Time** - Real-time screen usage analytics with health implications
- **Journal Entries** - Reflective journaling with AI-powered summaries and pattern detection
- **Goal Architecture** - Hierarchical goal system with milestones and progress tracking
- **AI-Powered Insights** - Cross-domain pattern detection, behavioral analysis, and recommendations

## Design Philosophy

- **Surgical Precision** - Every pixel justified, no wasted space
- **Calm Authority** - Like Claude.ai, sophisticated but approachable
- **Invisible Until Needed** - No clutter, information reveals on interaction
- **Truth Over Decoration** - Color only when meaningful; data-driven design
- **Addictive Through Clarity** - Engaging through understanding, not gamification

## Architecture

### Tech Stack

- **Frontend**: Next.js 16, React 19, TypeScript, Tailwind CSS v4
- **UI Components**: shadcn/ui components with custom CorteXia theming
- **Charts**: Recharts for data visualization
- **Icons**: Lucide React
- **State Management**: Client-side React with Zustand-ready architecture
- **Layout**: App Router with modular component structure

### Project Structure

```
CorteXia/
├── /app
│   ├── layout.tsx              # Root layout with metadata
│   ├── globals.css             # Design system & CSS variables
│   ├── page.tsx                # Dashboard home
│   ├── /tasks                  # Task management
│   ├── /habits                 # Habit tracking
│   ├── /time                   # Time analytics
│   ├── /finance                # Finance tracking
│   ├── /study                  # Study session management
│   ├── /goals                  # Goal architecture
│   ├── /journal                # Journaling
│   ├── /insights               # AI insights
│   └── /settings               # Settings & preferences
├── /components
│   ├── /layout                 # Header, Sidebar, AppLayout
│   ├── /dashboard              # Life State Core, Signals, AI Reasoning Strip
│   └── /ui                     # shadcn/ui components
└── /lib
    └── utils.ts                # Utility functions
```

## Key Pages & Features

### Dashboard (Home)
The central hub of CorteXia featuring:
- **Life State Core** - AI-calculated life state (Momentum, On Track, Drifting, Overloaded)
- **Signal Constellation** - 8 signals in orbital layout (Time, Focus, Habits, Goals, Money, Study, Screen, Energy)
- **AI Reasoning Strip** - Fixed bottom panel explaining AI insights and recommendations

### Tasks Page
- Comprehensive task management with priority levels
- Time estimation and completion tracking
- Filter by domain (work, personal, health, learning)
- Quick stats on high-priority and due-today tasks

### Habits Page
- Daily/weekly habit tracking with checkboxes
- Streak visualization with GitHub-style calendar
- Individual streak counters and momentum tracking
- Habit performance analytics

### Time Analytics
- Weekly time distribution charts
- Focus quality analysis (focused/distracted/neutral)
- Category breakdown of time allocation
- Daily productivity metrics

### Finance
- Income vs. expense tracking
- Weekly spending patterns with budget comparison
- Category-based spending breakdown
- Budget progress bars with warning indicators

### Study
- Session-based learning tracking
- Subject breakdown with time allocation
- Learning goal progress tracking
- Focus level metrics per session

### Goals
- Hierarchical goal system with milestones
- Progress bars with deadline tracking
- Sub-goal completion tracking
- Priority-based goal organization

### Journal
- Rich text journaling with mood tracking
- AI-powered entry summaries
- Tag-based organization
- Mood analytics and sentiment tracking

### AI Insights
- Cross-domain pattern detection
- Behavioral analysis and recommendations
- Weekly synthesis of life trends
- Morning briefing generation
- Actionable recommendations with impact estimates

### Settings
- Account and profile management
- Notification preferences
- Privacy and security controls
- Appearance customization
- Data export and management

## Design System

### Color Palette

**Semantic State Colors** (consistent across light/dark):
- Momentum: `#10B981` (Green)
- On Track: `#3B82F6` (Blue)
- Strategic: `#8B5CF6` (Purple)
- Drifting: `#F59E0B` (Amber)
- Overloaded: `#EF4444` (Red)
- Burnout: `#DC2626` (Dark Red)

**Light Mode Neutrals**:
- Background: `#FFFFFF`
- Secondary: `#F8F9FA`
- Tertiary: `#F0F1F3`
- Text Primary: `#0A0B0D`
- Text Secondary: `#4B5563`
- Text Tertiary: `#9CA3AF`

**Dark Mode Neutrals**:
- Background: `#0A0B0D`
- Secondary: `#151618`
- Tertiary: `#1F2023`
- Text Primary: `#F9FAFB`
- Text Secondary: `#D1D5DB`
- Text Tertiary: `#6B7280`

### Typography

- **Primary Font**: Inter Variable
- **Mono Font**: Geist Mono
- **Spacing System**: 8px baseline (8, 16, 24, 32, 48, 64, 80, 120)

### Layout Dimensions

- Header: 64px fixed
- Sidebar: 240px (collapsible to 64px)
- Content Max Width: 1440px
- Content Padding: 32px
- Card Border Radius: 12px
- Minimum Breathing Room: 40% empty space

## Getting Started

1. **Clone/Download** the project
2. **Install dependencies** (automatically detected by v0)
3. **Run development server**: The preview is live in v0
4. **Explore** each page via the sidebar navigation

## Future Integrations

- Supabase PostgreSQL for data persistence
- Gemini 3 AI for advanced insights and reasoning
- Real-time sync across devices
- Mobile app support
- Integration with calendar, email, and productivity tools
- Advanced analytics and visualization dashboards

## Browser Support

- Modern browsers with ES6+ support
- Dark/light mode detection and toggle
- Responsive design (desktop-first, mobile-compatible)

## Performance & Best Practices

- Modular component architecture for code reuse
- Optimized rendering with React best practices
- CSS variables for consistent theming
- Accessible UI with semantic HTML and ARIA labels
- Mobile-responsive with Tailwind CSS utility classes

## License

Built with v0 by Vercel. Designed for personal use and productivity.

---

**CorteXia**: Your life, understood. Powered by AI.
