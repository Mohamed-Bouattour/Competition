# Design System: ÉpiCare - Sensibilisation & Soutien
**Project ID:** ÉpiCare

## 1. Visual Theme & Atmosphere
The design evokes a sense of **professionalism, calm, and accessibility**. It balances medical authority with a supportive, human-centric "vibe."
*   **Mood:** Reassuring, clear, optimistic.
*   **Aesthetic:** Modern, clean, using soft pastels to avoid clinical coldness, utilizing ample whitespace ("Airy").
*   **Imagery:** Abstract, peaceful medical connections (neurons), avoiding distressing imagery.

## 2. Color Palette & Roles

### Primary Colors
*   **Medical Blue (#427cf0)**: Used for primary actions (buttons), key branding elements (logos), and emphasized text. Represents trust and clarity.
*   **Soft Sky Blue (#e0eafc)**: Used for backgrounds, header backgrounds, and soft accents. Provides a calming foundation.

### Secondary Colors
*   **Healing Mint (#eafaf1)**: Used for success states, definition containers, and highlighting health-related context. Adds a sense of growth and safety.

### Neutrals
*   **Clinical Off-White (#f6f6f8)**: Main page background. Reduces glare compared to pure white.
*   **Deep Navy/Charcoal (#101622)**: Dark mode background and primary text contrast.
*   **Slate Grey (#475569)**: Body text (`text-slate-600`), providing softer readability than pure black.

## 3. Typography Rules
*   **Font Family:** `Inter` (Sans-serif). Choose for its high legibility and modern geometric feel.
*   **Headings:** Bold to Extra-Bold (`font-display font-extrabold`).
    *   H1: `5xl` to `7xl`.
    *   H2: `4xl` to `5xl`.
*   **Body:** Medium weight (`font-medium`), sized `lg` to `2xl` for accessibility.
*   **Character:** Clean, non-intrusive, optimized for screen reading.

## 4. Component Stylings

### Buttons & Interactivity
*   **Primary Action:** `rounded-xl`, `bg-primary` (#427cf0), `text-white`. Includes `shadow-lg` and lifts on hover (`hover:shadow-xl`).
*   **Navigation Items:** Large touch targets (`p-4`), `rounded-xl`. Hover state uses a translucent white or slate overlay (`hover:bg-white/60`).
*   **Icons:** "Material Icons Round" style. Large sizing (4xl+) for immediate visual recognition.

### Cards & Containers
*   **Content Cards:** `rounded-2xl` with a subtle border (`border-slate-100`).
*   **Highlight Boxes:** `rounded-3xl` (e.g., Definition section), using `bg-secondary-soft` for distinct separation.
*   **Glassmorphism:** Used in tags (`backdrop-blur-sm`, `bg-primary/10`).

### Visual Details
*   **Corners:** Generously rounded (`rounded-xl` to `rounded-3xl`) creating a friendly, organic feel.
*   **Shadows:** Soft and diffused (`shadow-lg`, `drop-shadow-sm`), creating depth without harsh lines.

## 5. Layout Principles
*   **Container**: Centralized content (`container mx-auto`) with consistent horizontal padding (`px-6`).
*   **Whitespace**: Heavy use of vertical spacing (`py-20`, `gap-8`) to separate concepts clearly.
*   **Grids**: Responsive grids (`md:grid-cols-2`) for comparison or list items (like "Causes").
