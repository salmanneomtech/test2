# Neom Techverse

A modern AI automation landing page built with React, TypeScript, Tailwind CSS, and Vite.

## Features

- ✨ Modern, responsive UI with dark theme
- 🎨 Beautiful animations with Framer Motion
- 🚀 Fast development with Vite
- 📦 Pre-built UI components from shadcn/ui
- 🎯 SEO-friendly structure
- 📱 Mobile-first design
- ⚡ Optimized performance

## Tech Stack

- **Framework**: React 18.3.1
- **Build Tool**: Vite 5.4.8
- **Styling**: Tailwind CSS 3.4.13
- **Components**: shadcn/ui (Radix UI)
- **Animations**: Framer Motion 11.0.0
- **Routing**: Wouter 3.3.5
- **State Management**: React Query 5.0.0
- **Icons**: Lucide React 0.400.0
- **Language**: TypeScript

## Getting Started

### Prerequisites

- Node.js 16+ and npm/yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/salmanneomtech/test2.git
cd test2
```

2. Install dependencies
```bash
npm install
```

3. Start development server
```bash
npm run dev
```

The app will open at `http://localhost:3000`

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
src/
├── components/
│   ├── ui/                 # shadcn/ui components
│   ├── Navbar.tsx
│   ├── Hero.tsx
│   ├── Services.tsx
│   ├── FeatureSections.tsx
│   ├── Process.tsx
│   ├── Benefits.tsx
│   ├── Pricing.tsx
│   ├── Testimonials.tsx
│   ├── CaseStudies.tsx
│   ├── FAQ.tsx
│   ├── CTASection.tsx
│   └── Footer.tsx
├── pages/
│   ├── LandingPage.tsx
│   └── not-found.tsx
├── lib/
│   └── utils.ts
├── hooks/
│   └── use-toast.ts
├── App.tsx
└── main.tsx
```

## Key Sections

- **Hero**: Eye-catching header with accordion image carousel
- **Services**: AI service offerings (Agents, LLM Fine-tuning, Computer Vision, etc.)
- **Features**: Three feature sections with alternating layout
- **Process**: 4-step methodology visualization
- **Benefits**: Performance metrics and key benefits
- **Pricing**: Three pricing tiers with feature comparison
- **Testimonials**: Customer reviews with star ratings
- **Case Studies**: Real-world deployment examples
- **FAQ**: Frequently asked questions with accordion
- **CTA**: Call-to-action section

## Configuration Files

- `vite.config.ts` - Vite configuration with path aliases
- `tailwind.config.js` - Tailwind CSS customization
- `tsconfig.json` - TypeScript configuration
- `components.json` - shadcn/ui configuration

## License

MIT
