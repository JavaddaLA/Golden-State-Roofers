# AI Agent Curriculum: Building $20K Agency-Level Websites

## Objective

Train an AI agent to consistently generate high-end, visually compelling, conversion-focused websites that resemble work produced by top-tier creative agencies.

---

## Core Philosophy

Premium websites are not defined by excessive animation, but by:

* Strong visual hierarchy
* Intentional motion
* Clean layout systems
* Performance optimization
* Brand alignment
* Strategic restraint

---

## Skill Stack Overview

### 1. Layout & Visual Hierarchy

The agent must master:

* Grid systems (CSS Grid, Flexbox)
* Spacing systems (8pt or 4pt scale)
* Typography hierarchy (H1–H6, body, captions)
* Section rhythm and flow
* Content grouping and scanning behavior

**Outcome:** Pages feel structured, readable, and premium before animation is added.

---

### 2. Motion Design Fundamentals

The agent must understand:

* Easing (ease-in, ease-out, cubic-bezier)
* Timing and duration
* Staggered animations
* Entry/exit transitions
* Micro-interactions (hover, focus, click)

**Outcome:** Motion enhances UX instead of distracting.

---

### 3. Scroll-Based Storytelling

The agent must design:

* Section entry and exit states
* Scroll-triggered reveals
* Pinned (sticky) sections
* Parallax layers
* Narrative transitions between sections

**Outcome:** Website feels cinematic and guided.

---

### 4. 3D Scene Integration

The agent must learn:

* Basic 3D composition (camera, lighting, materials)
* When to use 3D (hero sections, product showcases)
* Performance constraints (polygon count, textures)
* Interaction patterns (mouse, scroll-driven)

**Outcome:** 3D enhances the experience without degrading performance.

---

### 5. Performance Optimization

The agent must enforce:

* 60fps target rendering
* GPU-friendly animations (transform, opacity)
* Lazy loading assets
* Image/video compression
* Minimal DOM complexity

**Outcome:** Smooth, responsive experience across devices.

---

### 6. Smooth Scrolling & UX Integrity

The agent must:

* Implement smooth scrolling responsibly
* Preserve native behaviors (anchors, accessibility)
* Avoid scroll jank or lag

**Outcome:** Navigation feels fluid but still intuitive.

---

### 7. Accessibility & Usability

The agent must include:

* Semantic HTML structure
* Keyboard navigation
* Contrast compliance
* Reduced motion support (`prefers-reduced-motion`)

**Outcome:** Premium experience is inclusive and production-ready.

---

### 8. Component-Based Architecture

The agent must build reusable components:

* Hero sections
* Feature sections
* Testimonials
* Pricing blocks
* Sticky storytelling sections
* CTA bands

**Outcome:** Consistency across pages and scalability.

---

### 9. Brand Translation

The agent must adapt designs based on:

* Industry (tech, luxury, service-based, etc.)
* Tone (minimal, bold, editorial, corporate)
* Color systems
* Typography pairing

**Outcome:** Each website feels custom, not templated.

---

### 10. Taste & Restraint

The agent must learn:

* When NOT to animate
* Limiting animation types per page
* Prioritizing clarity over complexity

**Outcome:** Work feels expensive, not overdesigned.

---

## Technical Stack

### Core Frontend

* HTML5
* CSS3 (Grid, Flexbox, Container Queries)
* JavaScript (ES6+)

### Animation & Motion

* GSAP + ScrollTrigger
* Framer Motion (or Motion)

### Smooth Scrolling

* Lenis

### 3D

* Three.js
* React Three Fiber (for React-based apps)

### Frameworks

* Next.js (preferred)
* React

### Styling

* TailwindCSS
* shadcn/ui (for structured UI components)

### Performance & Optimization

* Lazy loading
* Code splitting
* Image optimization (WebP/AVIF)

---

## Learning Phases

### Phase 1: Foundation (No Animation)

Focus:

* Layout systems
* Typography
* Section structure

Deliverable:

* Static high-end landing page

---

### Phase 2: Micro Interactions

Focus:

* Hover states
* Button animations
* Subtle reveals

Deliverable:

* Interactive UI elements

---

### Phase 3: Scroll Animation

Focus:

* ScrollTrigger
* Section reveals
* Parallax effects

Deliverable:

* Cinematic scroll experience

---

### Phase 4: Smooth Scrolling & Performance

Focus:

* Lenis integration
* Performance tuning

Deliverable:

* Smooth, lag-free experience

---

### Phase 5: 3D Integration

Focus:

* Hero 3D scenes
* Scroll-driven 3D animation

Deliverable:

* Interactive 3D hero section

---

### Phase 6: Brand Adaptation

Focus:

* Rebuilding same site in different styles

Deliverable:

* Multiple brand variations of one layout

---

## Agent Prompt Template (Copy/Paste)

You are a senior frontend engineer and motion designer specializing in high-end, agency-level websites.

Your goal is to create a modern, visually striking, and conversion-focused website that feels like a $20,000+ custom build.

### Requirements:

* Use strong visual hierarchy and spacing systems
* Keep layout clean, structured, and readable
* Implement smooth, intentional animations (avoid overuse)
* Use scroll-based storytelling where appropriate
* Include parallax and section transitions
* Add one standout “hero moment” (3D or motion-based)
* Ensure performance remains smooth (60fps target)
* Maintain accessibility and semantic structure
* Design must feel premium, minimal, and polished

### Tech Preferences:

* Next.js + TailwindCSS
* GSAP ScrollTrigger for animations
* Optional: Three.js for hero section

### Output:

* Clean, production-ready code
* Modular components
* Fully responsive design

Avoid clutter, excessive animation, or gimmicks. Prioritize clarity, polish, and user experience.

---

## Evaluation Criteria

A website is considered "premium" if:

* It feels structured and intentional
* Animations guide attention (not distract)
* Performance is smooth across devices
* Visual style matches brand identity
* It avoids unnecessary complexity

---

## Final Principle

"Expensive" design is not about doing more.

It is about doing fewer things, extremely well.

---

# Reusable Design System + Animation Blueprint

## Purpose

This blueprint is a reusable framework for building premium, agency-style websites with consistent visual quality, strong conversion structure, and polished motion.

It is designed to help an AI agent produce websites that feel custom, expensive, and production-ready without reinventing the structure each time.

---

## 1. Design System Foundation

### 1.1 Design Principles

Every site should follow these rules:

* Clarity before complexity
* Strong hierarchy before decoration
* Motion with purpose, not motion for its own sake
* Fewer visual ideas executed well
* Consistent spacing, typography, and interaction patterns

---

### 1.2 Visual Tone Targets

Use one of these tone directions per project:

#### Minimal Premium

* Clean whitespace
* Strong typography
* Sparse but elegant motion
* Neutral palette with one accent color

#### Tech Futuristic

* Dark surfaces
* Glassmorphism or subtle glow
* 3D hero objects
* Layered parallax and cinematic transitions

#### Editorial Luxury

* Large typography
* High contrast layout
* Rich imagery
* Smooth fade and scale reveals

#### Bold Service Brand

* Clear sections
* High contrast CTAs
* Fast trust-building layout
* Motion focused on clarity and conversion

---

## 2. Core Design Tokens

### 2.1 Spacing Scale

Use a consistent spacing scale:

* 4px
* 8px
* 12px
* 16px
* 24px
* 32px
* 48px
* 64px
* 96px
* 128px

**Rule:** Most padding and margin decisions should snap to this scale.

---

### 2.2 Border Radius Scale

* Small UI: 8px
* Cards/containers: 16px
* Large panels: 24px
* Hero containers / overlays: 32px
* Pills/buttons: full rounded where appropriate

---

### 2.3 Shadow Language

Use soft, layered shadows:

* Level 1: subtle separation
* Level 2: card emphasis
* Level 3: modal / hero lift

Avoid harsh or muddy shadows. Premium sites use restrained depth.

---

### 2.4 Typography System

#### Heading Scale

* Display: 64–96px
* H1: 48–72px
* H2: 36–48px
* H3: 28–32px
* H4: 20–24px
* Body Large: 18–20px
* Body: 16px
* Small text: 14px
* Caption: 12px

#### Typography Rules

* Limit to 1–2 font families
* Maintain consistent line-height
* Use heavier weight for emphasis, not extra colors
* Let headings carry visual identity

---

### 2.5 Color System Structure

Use a token-based system:

* `background`
* `foreground`
* `muted`
* `muted-foreground`
* `card`
* `card-foreground`
* `primary`
* `primary-foreground`
* `secondary`
* `accent`
* `border`
* `ring`

#### Color Rules

* One dominant background direction
* One clear primary CTA color
* One accent color maximum unless brand requires more
* High contrast for text and CTA readability

---

## 3. Reusable Layout Blueprint

### 3.1 Page Structure

Most premium landing pages can follow this sequence:

1. **Hero**
2. **Trust / social proof**
3. **Problem or opportunity framing**
4. **Feature or capability sections**
5. **Interactive or storytelling section**
6. **Results / benefits / proof**
7. **Testimonials / case studies**
8. **CTA block**
9. **Footer**

---

### 3.2 Section Rules

Each section should have:

* Clear purpose
* Strong headline
* Supporting copy kept tight
* One primary action or focal point
* Enough negative space to breathe

Avoid sections that try to do too many jobs.

---

### 3.3 Grid System

Use a 12-column grid for desktop.

Recommended layout behavior:

* Desktop: 12 columns
* Tablet: 6–8 columns
* Mobile: 4 columns or stacked layout

Use consistent max widths:

* Content width: 1200–1440px max
* Reading width: 640–760px max for text-heavy areas

---

## 4. Reusable Component Library

### 4.1 Hero Section Variants

#### Variant A: Minimal Hero

* Strong headline
* Supporting subheadline
* Primary and secondary CTA
* Clean visual or subtle motion background

#### Variant B: 3D Hero

* 3D object or scene on one side
* Text and CTA on the other
* Scroll cue
* Light parallax or camera drift

#### Variant C: Fullscreen Story Hero

* Full viewport section
* Layered text reveals
* Background motion or video
* Scroll-triggered transition into next section

---

### 4.2 Social Proof Strip

Include:

* Client logos
* Review snippets
* Outcome stats
* Press mentions

Animation:

* Subtle fade in
* Horizontal marquee only if it remains readable and smooth

---

### 4.3 Feature Grid

Use cards or split sections.

Structure:

* Icon or small visual
* Short title
* One concise paragraph
* Optional stat or CTA

Animation:

* Staggered reveal on scroll
* Slight translate + fade

---

### 4.4 Sticky Storytelling Section

Pattern:

* Sticky content panel on one side
* Scroll-updating visuals or cards on the other
* Each scroll segment advances one idea

Use this for:

* Product walkthroughs
* Service process explanation
* Capability storytelling

---

### 4.5 Testimonial / Case Study Block

Structure:

* Quote
* Name / title / brand
* Result metric
* Optional image or logo

Animation:

* Gentle fade and slide
* No excessive carousel motion unless needed

---

### 4.6 CTA Band

Structure:

* Clear offer or invitation
* Short copy
* One main CTA
* Optional supporting trust note

Animation:

* Minimal
* Focus on button hover refinement

---

## 5. Animation Blueprint

## 5.1 Motion Principles

All motion should do one of four things:

* Direct attention
* Reveal hierarchy
* Connect sections
* Add emotional polish

If it does none of these, remove it.

---

### 5.2 Motion Categories

#### A. Entrance Motion

Used when content first appears.

Patterns:

* Fade in
* Translate up/down slightly
* Scale from 0.96 to 1
* Mask reveal

Use for:

* Headlines
* Cards
* Images
* Supporting copy

---

#### B. Scroll Motion

Used to create progression.

Patterns:

* Parallax layers
* Scrubbed transforms
* Pinned sections
* Text/image handoffs
* Progress-based scaling or opacity

Use for:

* Storytelling sections
* Hero transitions
* Product showcases

---

#### C. Interaction Motion

Used on hover, click, focus, and state change.

Patterns:

* Hover lift
* Border/shine transitions
* Icon movement
* CTA button press states
* Accordion expansion

Use for:

* Buttons
* Cards
* Navigation
* Menus

---

#### D. Ambient Motion

Used to keep the page feeling alive.

Patterns:

* Slow floating objects
* Soft gradient drift
* Noise or glow movement
* Gentle 3D camera drift

Use sparingly.

---

### 5.3 Standard Motion Specs

Use these defaults unless the design calls for something else:

#### Durations

* Fast UI: 0.2s–0.35s
* Standard reveal: 0.5s–0.8s
* Cinematic section reveal: 0.8s–1.4s
* Ambient loops: 4s–12s+

#### Easing

* Use smooth, premium easing curves
* Avoid robotic linear movement except for specific effects
* Prefer soft ease-out for reveals and ease-in-out for transitions

#### Distance

* Small UI motion: 4–12px
* Section reveals: 16–40px
* Large scene transitions: context dependent

---

## 6. Scroll Experience Blueprint

### 6.1 Hero Scroll Sequence

Recommended pattern:

1. Hero loads with immediate clarity
2. Background or 3D object subtly animates
3. Headline and CTA reveal in sequence
4. On scroll, hero compresses or transitions into next section

---

### 6.2 Parallax Structure

Use 3 depth layers maximum in most cases:

* Foreground
* Midground
* Background

Each layer should move at a slightly different rate.

Avoid exaggerated parallax that reduces readability.

---

### 6.3 Sticky Narrative Pattern

Recommended sequence:

* Section pins to viewport
* User scrolls through 3–5 key story steps
* Text updates on one side
* Visual responds on the other
* Final step transitions cleanly into next section

---

### 6.4 Page Transition Feel

Across sections, use:

* Background shifts
* Opacity handoffs
* Scale transitions
* Layer reveals

Do not make every section transition dramatic. Use contrast.

---

## 7. 3D Blueprint

### 7.1 When to Use 3D

Use 3D for:

* Hero centerpiece
* Product or object showcase
* Spatial storytelling moment
* Background depth enhancement

Do not use 3D just because it looks impressive.

---

### 7.2 3D Rules

* Keep scene concept simple
* Use one focal object
* Prioritize lighting and material quality
* Avoid overloading geometry
* Test performance on lower-end devices
* Provide fallback behavior for mobile if needed

---

### 7.3 3D Motion Patterns

* Slow idle rotation
* Camera drift
* Scroll-driven object rotation
* Layer-based depth movement
* Triggered focus zoom

---

## 8. Premium Interaction Rules

### Buttons

* Clear hover state
* Press feedback
* Consistent radius and padding
* Strong contrast

### Cards

* Slight hover lift or glow
* Optional border transition
* Maintain readability

### Navigation

* Smooth anchor scroll
* Active section highlight if needed
* Sticky nav should remain lightweight

### Forms

* Strong focus states
* Clean validation
* Clear spacing
* Minimal friction

---

## 9. Performance Blueprint

### Hard Rules

* Animate transform and opacity whenever possible
* Avoid layout-thrashing properties for frequent motion
* Lazy load heavy assets
* Compress images and video aggressively
* Reduce JavaScript where native CSS can handle the effect
* Limit simultaneous motion on screen

### Performance Targets

* Smooth scrolling without jank
* Fast LCP
* Responsive interaction feedback
* Graceful degradation on mobile

---

## 10. Accessibility Blueprint

Every website should include:

* Semantic HTML
* Keyboard accessible navigation
* Focus-visible states
* Adequate contrast
* Motion reduction support
* Clear readable text during animated sequences

Premium work is accessible work.

---

## 11. Reusable Animation Recipes

### Recipe 1: Hero Reveal

* Fade in headline
* Stagger supporting text and CTA
* Background object subtly scales into position
* Scroll cue fades in last

### Recipe 2: Section Reveal

* Section enters with slight upward motion
* Cards stagger in 0.08–0.15 seconds apart
* Image masks reveal from one direction

### Recipe 3: Sticky Story Scroll

* Pin section
* Update text block each progress interval
* Animate associated image or card stack
* Release pin smoothly into next section

### Recipe 4: CTA Polish

* Button gains subtle lift and brightness on hover
* Supporting copy fades in slightly faster than headline

### Recipe 5: Premium Card Hover

* Translate Y by -4px to -8px
* Increase shadow slightly
* Animate icon or arrow by a few pixels

---

## 12. Build Order for Each Project

1. Define brand tone
2. Choose page structure
3. Apply design tokens
4. Build static layout first
5. Add interaction states
6. Add scroll choreography
7. Add optional 3D hero or scene
8. Optimize performance
9. Check accessibility
10. Refine motion restraint

---

## 13. Agent Instruction Block (Reusable)

You are building a premium, agency-quality website using a reusable design system and motion blueprint.

Your output should feel like a custom website produced by a high-end creative agency.

### Design Rules

* Use strong hierarchy, grid alignment, and clean spacing
* Follow a restrained premium aesthetic
* Keep sections highly organized and intentional
* Use consistent component patterns
* Match the visual tone to the brand

### Motion Rules

* Use animation to guide attention, reveal structure, and create polish
* Include smooth scroll-based transitions where appropriate
* Use parallax and sticky storytelling only when they improve clarity
* Keep motion smooth and cinematic, never chaotic
* Prioritize performance and accessibility

### Preferred Stack

* Next.js
* TailwindCSS
* GSAP + ScrollTrigger
* Lenis for smooth scrolling
* Optional Three.js / React Three Fiber for hero scenes

### Output Requirements

* Production-ready component structure
* Responsive layout
* Reusable section patterns
* Clean animation architecture
* Premium visual polish

Avoid clutter, random motion, inconsistent spacing, and overdesigned effects. The site should feel expensive because it is disciplined, intentional, and smooth.

---

## 14. Final Standard

A reusable premium website system should create sites that are:

* Visually clear
* Highly polished
* Smooth in motion
* Strong in structure
* Easy to adapt across brands
* Impressive without feeling excessive
