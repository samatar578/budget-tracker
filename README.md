# Personal Budget Tracker — Week 2

A simple budget tracker built with HTML and CSS. This is a work in progress — JavaScript functionality is coming in Week 6.

## What's Inside

- **Expense table** — Displays sample expense data with a styled header, borders, padding, and alternating row colors.
- **Add Expense form** — Includes text, number, select (category), and date inputs, all with matching IDs for future JavaScript use.
- **Multimedia** — A logo image in the header and an embedded YouTube video with budgeting tips.
- **Interactive elements** — A collapsible "How to use this tracker" section using `<details>` and `<summary>`, plus hover effects on table rows and the button.

## CSS Techniques Used

- Descendant selectors (e.g., `.expenses-table tbody tr`)
- Direct child selectors (e.g., `#expense-form > label`)
- Positional pseudo-classes (`tr:nth-child(even)`, `tr:first-child`)
- Negation pseudo-class (`input:not([type="submit"])`)
- Focus states (`input:focus`, `select:focus`)
- Hover states on rows and buttons
- `cursor: pointer` on the button

## How to View

Open `index.html` in any web browser.