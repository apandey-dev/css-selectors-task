# Task 3: CSS Selectors

**Student Name:** Arpit Pandey  
**Course:** HTML & CSS Fundamentals  
**Project Folder:** `03_CSS_Selectors`

---

## 1. Project Title
**Mastering CSS Selectors and Styling Hierarchy**

## 2. Assignment Objective
To demonstrate core CSS selector capabilities including element selectors, class selectors (`.head`), ID selectors (`#bglime`, `#para`), descendant selectors, and structural pseudo-classes (`:first-child`, `:last-child`, `:nth-child()`) without using inline CSS, frameworks, or unnecessary IDs/classes.

## 3. Technologies Used
- **HTML5** (Structured semantic markup)
- **CSS3** (External stylesheet `style.css` focusing on selectors and specificity)

## 4. Features Implemented
- **External Stylesheet Connection:** Clean separation of concerns via `<link rel="stylesheet" href="style.css">`.
- **Heading Styling:** Class `.head` gives dark blue color to all 3 headings.
- **ID Styling on Heading:** `#bglime` adds a vibrant green background and `#bglime span` highlights the word "head" in red.
- **Element Selector on Paragraphs:** All `<p>` elements default to white text.
- **ID Styling on Paragraph:** `#para` styles the second paragraph with vibrant green text, while `p span` renders the word "paragraph" in enlarged bold black text.
- **Pseudo-classes for Links:** The two links inside `<ul>` are styled strictly via `ul li:first-child a` and `ul li:last-child a` (no `id` or `class` on `<a>`).
- **Pseudo-classes for Ordered Lists:** `ol li:nth-child(2)` and `ol li:nth-child(3)` style the 2nd and 3rd list items in blue and red respectively.

## 5. Folder & File Structure
```text
03_CSS_Selectors/
├── index.html
├── style.css
└── README.md
```

## 6. How to Run Locally
1. Navigate to the project directory:
   ```bash
   cd 03_CSS_Selectors
   ```
2. Open `index.html` in your web browser.

## 7. How to Open the HTML File in a Browser
- Double-click `index.html` in your file explorer.
- Or use VS Code Live Server.
- Or run in terminal:
  - Windows: `start index.html`
  - macOS: `open index.html`
  - Linux: `xdg-open index.html`

## 8. Screenshot Reference
- Closely replicates the layout, colors, and selector outputs shown in `03.png`.

## 9. Deployment Information
- **GitHub Repository:** Private repository `css-selectors-task`
- **Deployment Platform:** Vercel
- **Live URL:** To be updated after deployment
