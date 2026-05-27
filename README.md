# CSS Layout Demos and Responsive Frameworks

This repository houses a series of frontend layout exercises, exploring CSS Flexbox, CSS Grid, and responsive landing page layouts. Each subdirectory illustrates distinct methods for organizing content on the viewport, transitioning from linear flex containers to complex multi-dimensional grids.

---

## Folder Blueprint

```
Layouts/
├── FlexLayout-1/      # Basic linear Flexbox alignment models
├── FlexLayout-2.1/    # Multi-item wrapping and dynamic rows
├── FlexLayout-2.2/    # Advanced flex sizing and justification
├── GridLayout-1/      # Basic CSS Grid templates and track sizing
├── GridLayout-2/      # Complex grid-area alignments and nested slots
└── TravelPage/        # Integrated Travel Landing Page design
```

---

## Layout Breakdown

### 1. Flexbox Layouts
These folders demonstrate how to organize items dynamically along a single axis (either row or column) with automatic spacing, wrapping, and cross-axis alignment.
* FlexLayout-1: Demonstrates standard linear positioning, row/column flow transitions, and main-axis alignments (`justify-content: center / space-between`).
* FlexLayout-2.1: Exercises wrapping properties (`flex-wrap: wrap`) to manage lists of cards dynamically as the viewport size changes.
* FlexLayout-2.2: Focuses on child sizing dynamics (`flex-grow`, `flex-shrink`, `flex-basis`) and custom spacing.

### 2. Grid Layouts
These folders showcase the power of two-dimensional grid layouts, allowing complex tabular column and row sizing without relying on positioning offsets or float hacks.
* GridLayout-1: Introduces grid container structures, fractional sizing (`1fr 2fr`), grid gaps, and basic template definitions (`grid-template-columns`).
* GridLayout-2: Explores complex grid item positioning across tracks, utilizing column/row spans (`grid-column: span 2`, `grid-row: 1 / 3`) to build dashboard interfaces.

### 3. Integrated Projects (TravelPage)
* TravelPage: A complete travel landing page structure integrating Flexbox and Grid components. Features:
  - Header: Responsive navigation menus styled with Flexbox spacing.
  - Hero Section: Main call-to-action block centered with flex parameters.
  - Destination Cards: Grid container organizing vacation cards with text and image overlays.
  - Footer: Multi-column navigation links and clean alignment structures.

---

## Viewing the Layout Demos

All layout assignments are static client-side pages built with HTML and Vanilla CSS. To inspect and test them:

### Method A: Direct Browser Execution
1. Navigate to the desired layout folder.
2. Double-click the `index.html` file to run it directly inside your default web browser (Chrome, Edge, Firefox, Safari).

### Method B: Browser Developer Tools
1. Open the page in your browser.
2. Right-click anywhere and select **Inspect** (or press `F12` / `Ctrl+Shift+I`).
3. Click the **Toggle Device Toolbar** icon to test the layout's responsiveness across various mobile, tablet, and desktop viewports.
