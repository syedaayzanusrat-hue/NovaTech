# NovaTech
A fully responsive landing page for a fictional dev-tools startup, built with HTML, CSS, and vanilla JavaScript. Features a dark-themed UI with an animated terminal hero section, feature cards, and scroll animations — fully adaptive across mobile, tablet, and desktop.
NovaTech is a fully responsive landing page built for a fictional developer-tools startup. This project was created as part of a Frontend Development assignment focused on responsive web design, demonstrating how a single layout can adapt seamlessly across mobile, tablet, and desktop screens using only HTML, CSS, and a small amount of vanilla JavaScript.
The design follows a modern dark-theme aesthetic inspired by real-world developer tool platforms (like Vercel and Netlify), using a custom color palette, typography system, and an animated terminal mockup as the page's signature visual element.
🛠️ Tech Stack

HTML5 — semantic page structure
CSS3 — Custom Properties (CSS variables), Flexbox, CSS Grid, Media Queries, Keyframe Animations
Vanilla JavaScript — mobile menu toggle, scroll effects, and scroll-triggered animations (no frameworks or libraries used)
Google Fonts — Space Grotesk, Inter, JetBrains Mono

🎨 Design System

Color Palette: Midnight Ink background (#0b0f19), Electric Cyan (#2dd4f0) and Signal Amber (#ffb020) accent colors
Typography: Space Grotesk for headings, Inter for body text, JetBrains Mono for labels and data (stats, terminal text, eyebrow labels)
Layout: CSS Grid for major section layouts, Flexbox for navigation and card alignment

✨ Features (Section by Section)
1. Sticky Navbar
Fixed navigation bar with logo, menu links, and a call-to-action button. Background becomes blurred and darker on scroll (backdrop-filter). Collapses into a hamburger menu on mobile.
2. Hero Section
Main heading with a highlighted keyword, supporting text, and two CTA buttons. Includes a custom animated terminal window — built purely with CSS keyframe animations — that simulates a developer typing and deploying code in real time, complete with a blinking cursor effect.
3. Stats Bar
A horizontal row of key metrics (projects launched, uptime, support availability, countries served) displayed in monospace font for a data-driven feel.
4. Features Section
Three feature cards (Fast Performance, Fully Responsive, Modern Design), each with a custom inline SVG icon, a heading, and a short description. Cards lift slightly on hover.
5. How It Works (Process Section)
A three-step onboarding flow (Sign Up → Connect Your Stack → Launch) with numbered markers and connecting lines between steps.
6. About Section
Company story paired with a decorative gradient "blob" shape built using CSS border-radius tricks.
7. Testimonial Section
A single customer quote styled in the display typeface, used to build a sense of credibility.
8. Contact / Call-to-Action Section
Final conversion section with a gradient background and a prominent "Get Started" button.
9. Footer
Logo, secondary navigation links, and copyright information.
📱 Responsive Behavior

Desktop (900px+): Full multi-column layouts (hero split view, three-column features grid, horizontal process steps)
Tablet (≤900px): Hero and about sections stack vertically; process steps stack with connecting lines hidden
Mobile (≤768px): Navigation collapses into a hamburger menu; feature cards and stats stack into a single column
Small Mobile (≤480px): Font sizes and padding scale down further for smaller screens

🎬 Interactivity & Animation

Scroll-triggered fade-in animations using the IntersectionObserver API
CSS keyframe-based typing animation in the hero terminal
Smooth scroll navigation between sections
Hover animations on buttons and feature cards
Respects prefers-reduced-motion for accessibility
