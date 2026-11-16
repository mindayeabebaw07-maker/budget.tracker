# My Budget Tracker - PLP Web Development

A simple web app to track daily expenses by description, category, amount, and date. Users can add expenses, view them in a table, and see the total.

## What I Built
- **Page Heading:** Title and tagline for the app.
- **Add Expense Form:** Inputs for Description, Category, Amount (KES), and Date, plus an Add Expense button.
- **Expense Table:** Lists all expenses with columns for Description, Category, Amount, Date, and Delete action.
- **Total:** Shows Total Expenses at the bottom of the table.

## File Structure
- `index.html` - Structure: header, Add Expense form, Expense Table, footer. Includes Google Fonts link.
- `style.css` - All Week 3 visual design: colors, fonts, table, form, and box model.
- `README.md` - This explanation.

## Week 3 - Visual Design

### 1. Intentional Color Palette (25%)
CSS variables in `:root`:
- `--theme: #D231A0` - Main pink for headings, buttons, table header
- `--theme-dark: #9E1E76` - Button hover
- `--cream: #FFF8F2` - Page background
- `--dark: #2B1A22` - Body text
- `--gold: #C68B2E` - Accent for header bottom border
- `--light-grey: #F2E9E4` - Alternating table rows
Same colors are reused consistently everywhere.

### 2. Typography (20%)
- Headings: `Merriweather` (Google Fonts, serif) - bold, easy to scan
- Body: `Inter` (Google Fonts, sans-serif) - clean, modern
- Body `font-size: 18px`, `line-height: 1.35` for readability and clear hierarchy.

### 3. Table and Form Styling (30%)
- Table: Pink header with white text, 1px borders, 14px cell padding, alternating rows with `nth-child(even)`, pink hover.
- Form: Bold labels, full-width inputs with 12px padding, 8px border-radius, pink focus outline.
- Buttons: Same pink as table header, white text, 8px radius, darker pink on hover. Delete buttons are red.

### 4. CSS Box Model (25%)
- Header, Form, and Table are each distinct cards with `margin-bottom: 30px`, `padding: 30px`, `border: 1px solid`, `border-radius: 12px`.
- Header has extra `border-bottom: 6px solid gold`.
- `box-sizing: border-box` is used so padding/border fit inside the width.

## How to View
Open `index.html` in a browser.