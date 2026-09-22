# Personal Budget Tracker — Week 3 Visual Design

An HTML & CSS budget tracker that has been upgraded with an intentional visual identity. No new features have been added in Week 3 — this week focuses purely on color, typography, table/form styling, and the CSS Box Model.

## What's Inside
- **Expense table** — Displays sample expenses with a teal header, alternating row colors, hover effect, and clean spacing.
- **Add Expense form** — Styled inputs, focus glow, and a rounded primary button.
- **Collapsible info section** — "How to use this tracker" using `<details>` and `<summary>`.
- **Multimedia** — Logo image and embedded YouTube video.

## Design Decisions

### Color Palette
A cohesive teal-and-slate palette gives the tracker a professional, trustworthy feel:
- **Primary teal (#0d9488)** — used for the header gradient, table header, buttons, and focus rings.
- **Slate grey (#1e293b)** — primary text color for readability.
- **Soft slate (#f1f5f9)** — page background so white cards stand out.
- **Amber (#f59e0b)** — accent for the collapsible info card's border and summary text.

### Typography
- **Poppins** for headings, labels, and buttons — geometric and confident.
- **Inter** for body text and inputs — highly legible at small sizes.
- Both loaded from Google Fonts.

### CSS Box Model
Every section (header, info, expenses, form, video, footer) is a "card" with:
- **Padding** inside for breathing room.
- **Margin** between cards for clear separation.
- **Border / border-radius** for a soft, modern look.
- **Box-shadow** for subtle depth.

### Advanced Selectors Used
- Descendant: `.expenses-table thead th`
- Direct child: `#expense-form > label`
- Positional pseudo-class: `tr:nth-child(even)`, `tr:first-child`
- Negation: `input:not([type="submit"])`
- Focus state: `input:focus`, `select:focus`
- Hover: `tbody tr:hover`, `#add-expense-btn:hover`

## How to View
Open `index.html` in any web browser.