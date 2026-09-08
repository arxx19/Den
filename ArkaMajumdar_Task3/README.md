# Task 3 - CSS Selectors Practice

## Description
A static HTML page demonstrating different types of CSS selectors: element, class, id, and structural (nth-child / first-child / last-child) selectors — used without any inline CSS.

## Files
- `index.html` — page structure and content.
- `style.css` — all styling, linked externally.

## Concepts Demonstrated

| Selector type | Example | What it shows |
|---|---|---|
| Class selector | `.head` | Same style (navy, bold) reused across the h1, h2, and h4 |
| ID selector | `#bglime` | Adds a background color to only the h2, and overrides the class where they conflict |
| Element selector | `p` | Styles every `<p>` tag white by default |
| ID overriding element | `#para` | Shows an id selector beating an element selector in specificity |
| Class overriding element | `.reset` | Resets one word back to default styling, beating the `p` element selector |
| Structural selectors (no class/id) | `li:first-child a`, `li:last-child a` | Styles the two links differently without adding a class or id to the `<a>` tags |
| nth-child selector | `ol li:nth-child(2)`, `ol li:nth-child(3)` | Colors only the 2nd and 3rd list items in the ordered list |

## How to Run
1. Keep `index.html` and `style.css` in the same folder.
2. Open `index.html` in any web browser.

## Author
Arka
