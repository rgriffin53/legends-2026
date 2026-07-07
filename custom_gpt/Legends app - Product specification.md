```markdown
# Legends App | Product Specification

## Interactive Ball Hockey Playbook
**Version 1.1**

---

# Purpose

A lightweight interactive playbook for ball hockey that replaces a linear PowerPoint/PDF with a simple, fast coaching reference.

Players should be able to review any concept in under two minutes.

This is a coaching tool—not a software product. Every design decision should reduce cognitive load.

---

# Design Principles

The application should always be:

- Simple
- Fast
- Lightweight
- Mobile-friendly
- Visually clean
- Easy to extend
- Consistent

Prefer clarity over cleverness.

---

# Technical Requirements

The application shall:

- Consist of a **single self-contained HTML file**
- Include all HTML, CSS, JavaScript, SVG assets, and branding within that file
- Require no build tools or external libraries
- Run offline once loaded
- Deploy directly to GitHub Pages
- Function well on desktop and mobile

---

# Visual Style

Use a USA Ball Hockey-inspired aesthetic:

- Dark navy primary color
- White content cards
- Restrained red accents
- Clean typography
- Generous spacing
- Coaching whiteboard aesthetic
- Minimal visual clutter

---

# Application Layout

Single-page application.

Persistent elements:

- Header
- Primary navigation

Only the content area changes.

Desktop and mobile should share the same information architecture while allowing different navigation patterns where appropriate.

---

# Header

Contains:

- USA Ball Hockey logo
- Team name
- Subtitle

---

# Primary Navigation

Two top-level sections:

- ⭐ North Star
- 🏒 Systems

North Star is the default view.

The active section should always remain visually distinct against page content.

---

# Mobile UX Principles

Desktop UX should remain the primary design reference.

Mobile may adapt navigation patterns when they improve usability without changing application structure.

Examples include:

- Wrapped navigation instead of horizontal scrolling
- Dropdown selectors instead of long side menus
- Sticky navigation with solid backgrounds
- Different layouts with identical content

---

# North Star

Displays a secondary navigation:

- Who We Are
- How We Win
- Mindset — With the Ball
- Mindset — Without the Ball

Desktop:

- Horizontal navigation.

Mobile:

- Wrapped multi-row navigation (no horizontal scrolling).

Switching between North Star pages should not create noticeable layout jumps.

---

# Mindset Pages

Display a static horizontal coaching whiteboard rink.

The rink should:

- Use realistic ball hockey rink proportions
- Scale to maximize available content space
- Maintain generous margins
- Include subtle rink markings (faceoff circles, goal lines, nets, etc.)
- Maintain consistent orientation (team attacks right)
- Place attack/defend indicators below the rink

Interactive coaching regions should:

- Occupy most of each zone
- Maintain consistent padding from rink boundaries
- Leave ample room for future coaching content

No animation is used.

---

# Systems

Desktop:

- Left navigation
- Content panel

Mobile:

- Compact topic selector
- Content immediately below selector

Desktop navigation should remain independently scrollable while allowing natural page scrolling at the limits.

Navigation should always make it obvious which system is currently selected.

---

# Systems Navigation

Systems:

- D-zone Coverage
- D-zone Break Out
- D-zone Face-Off
- Neutral Zone Forecheck
- Neutral Zone Possession
- Neutral Zone Face-Off
- O-zone Entry
- O-zone Possession
- O-zone Forecheck
- 5-4 Penalty Kill
- 5-3 Penalty Kill
- 5-4 Power Play
- 5-3 Power Play

Reference:

- Communication
- Terminology

Adding new items should require only adding data, not restructuring the application.

---

# System Content Layout

Each system follows the same structure:

- Title
- Coaching Objective
- Interactive Animation (future)
- Coaching Cues
- Optional Common Breakdowns

Until implemented, clearly identify all system content as placeholders.

---

# Animation Philosophy

Animations teach:

- Starting positions
- Movement
- Spacing
- Timing
- Coaching intent

Not game simulation.

Visual conventions remain consistent across every animation.

---

# User Experience Principles

Navigation should always make it obvious:

- Where the player is
- What section is active
- What topic is selected
- How to switch topics

Prioritize:

- Few clicks
- Fast recognition
- Minimal scrolling
- Stable layouts
- Readability on small screens

---

# Extensibility

Future teams should be able to customize:

- Branding
- Philosophy
- Principles
- Systems
- Terminology

without restructuring the application.

---

# Development Process

Each sprint begins with the previous HTML file, which remains the source of truth.

Only requested enhancements should be implemented.

---

# Change Management

Unless explicitly requested:

- Do not modify working functionality.
- Do not redesign completed sections.
- Do not remove existing navigation or interactions.
- Do not refactor solely for style.
- Preserve desktop UX when introducing mobile-specific improvements.
- Explain architectural concerns before changing behavior.

---

# Definition of Done

Each sprint delivers:

- Updated single HTML file
- Concise change summary
- Remaining required assets/information
- Known limitations or suggested future enhancements

---

# Development Philosophy

Prefer:

- Incremental improvement over rewrites
- Consistency over novelty
- Readability over cleverness
- Maintainability over optimization
- Data-driven extensibility over hard-coded structure
```
