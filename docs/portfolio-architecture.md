# Portfolio Architecture

## Vision
Create a premium, modern personal portfolio for Robel Hagos Mahray that feels like a senior AI software engineer's online presence rather than a student project.

## Goals
- Communicate technical depth, product thinking, and real-world impact
- Present projects, experience, and education clearly
- Feel fast, polished, and memorable across desktop and mobile
- Be easy to maintain and extend for future blog posts, certificates, and case studies

## Core Pages
1. Home / Landing
2. About / My Journey
3. Projects overview
4. Project detail pages
5. Resume
6. Blog / future articles
7. Contact

## Suggested Component Hierarchy
- App
  - Layout
    - Header
    - Main content
    - Footer
  - sections/
    - HeroSection
    - AboutSection
    - SkillsSection
    - ProjectsSection
    - JourneySection
    - CertificationsSection
    - ResumeSection
    - ContactSection
  - projects/
    - ProjectCard
    - ProjectDetail
  - ui/
    - SectionHeading
    - GlassPanel
    - Button
    - StatCard
    - TimelineItem

## Design System
- Color palette: deep charcoal, slate, electric cyan, violet, soft off-white
- Typography: Inter + Space Grotesk or Sora for headings
- Motion: subtle hover, reveal-on-scroll, staggered entrance
- Visual language: glassmorphism, high contrast, generous spacing, premium cards

## Routing Structure
- / -> Home
- /about -> About
- /projects -> Projects index
- /projects/:slug -> Project detail
- /resume -> Resume
- /blog -> Blog placeholder
- /contact -> Contact

## Development Roadmap
1. Set up Vite + React + TypeScript + Tailwind
2. Create global styling, theme tokens, and layout shell
3. Build hero, about, skills, projects, resume, contact sections
4. Add animations and responsive refinement
5. Prepare deployment configuration for Vercel
