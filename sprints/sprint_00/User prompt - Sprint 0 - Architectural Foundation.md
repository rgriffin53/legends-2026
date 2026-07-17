```markdown
# Legends App | Sprint 0: Architectural Foundation

You are implementing **Sprint 0** of the Interactive Ball Hockey Playbook described in the attached Product Specification.

Your objective is **not** to build the full app. Your objective is to create the cleanest possible architectural foundation for future iterative development.

---

# Scope

Create a single self-contained HTML file that establishes:

- Overall app structure
- Persistent header
- Primary navigation framework
- North Star section framework
- Systems section framework
- Placeholder content areas
- Clean CSS architecture
- Clean JavaScript state management

Do **not** implement real hockey content or animations.

Placeholder content should demonstrate the intended layout and interaction patterns, even though final coaching content will be added in future sprints.

---

# Required Structure

## Header

Include:

- USA Ball Hockey logo
- Team title: **2026 USA Women’s Legends**
- Subtitle: **Interactive Team Guide**

---

## Primary Navigation

Two primary sections:

- ⭐ North Star
- 🏒 Systems

North Star should be active by default.

Desktop is the reference experience. Mobile may adapt layouts and navigation to improve usability while preserving the same information architecture and functionality.

---

## North Star Framework

When North Star is active, display secondary navigation with:

- Who We Are
- How We Win
- Mindset — With Ball
- Mindset — Without Ball

Each section should display placeholder content.

The Mindset sections should include placeholder coaching whiteboard-style horizontal rink diagrams.

The rink should:

- Use realistic ball hockey proportions
- Include subtle rink markings (faceoff circles, goal lines, nets, etc.)
- Maximize usable coaching space while maintaining generous margins
- Maintain the standard orientation (team attacks right)

No animation is required.

---

## Systems Framework

When Systems is active, display:

Desktop:

- Left navigation
- Content panel

Mobile:

- Compact topic selector
- Content panel immediately below the selector

Systems navigation should include placeholder items:

- D-zone coverage
- D-zone break out
- D-zone face-off
- Neutral zone forecheck
- Neutral zone possession
- Neutral zone face-off
- O-zone entry
- O-zone possession
- O-zone forecheck
- 5-4 Penalty Kill
- 5-3 Penalty Kill
- 5-4 Power Play
- 5-3 Power Play

Reference items:

- Communication
- Terminology

All items should be clickable and update the placeholder content area.

Clearly indicate that system content and animations are placeholders.

---

# Technical Requirements

- Single self-contained HTML file
- No external frameworks
- No external JavaScript libraries
- No external CSS
- No build tools
- Responsive desktop/mobile layout
- Clear section comments
- Readable class names and IDs
- Simple centralized state management

---

# Design Direction

Use a clean USA Ball Hockey-inspired style:

- Dark navy background
- White content cards
- Restrained red accents
- Clean typography
- Generous spacing
- Professional coaching-tool aesthetic

The interface should feel calm, uncluttered, and easy to navigate.

---

# UX Expectations

Design separately for desktop and mobile.

Optimize each for its primary interaction model (mouse vs. touch) while maintaining the same application architecture.

Navigation should always make it obvious:

- Where the user is
- Which section is active
- Which topic is selected
- How to switch topics

Avoid unnecessary scrolling, layout shifts, or interactions that increase cognitive load.

---

# Change Management

Build this as a stable foundation.

Do not:

- Add animations
- Add real hockey systems
- Add unnecessary features
- Remove or simplify existing interactions while implementing unrelated changes

Existing working functionality should be preserved unless explicitly requested otherwise.

Prioritize clarity, extensibility, maintainability, and ease of future modification.

---

# Final UX Review

Before returning the HTML, review the application from the perspective of:

- Desktop usability
- Mobile usability
- Touch interaction
- Scrolling behavior
- Visual hierarchy
- Navigation discoverability

Resolve any obvious UX issues that fall within the scope of this sprint.

Finally, ask yourself:

> *If I were a first-time player opening this on my phone five minutes before a game, what would confuse or slow me down?*

Address any obvious issues that can be solved without changing completed functionality.

---

# Deliverable

Return:

- One complete, functional `index.html` file
- A concise summary of the architecture
- Any assumptions made
- Any known limitations or logical next steps (without implementing them)
```
