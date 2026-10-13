# TheBox — Adaptive & Accessible Layout

A responsive landing page built from a provided design, as part of
IT Academy Sprint 1 (Task S1.03).

## Description

This project reproduces the design of a construction company landing page
("TheBox"), adapted to different screen widths and made accessible to users
with visual impairments. It includes a hero section, a reputation section,
a services grid, a contact form, and a footer with a newsletter and social links.

The goal of the practice is to apply CSS Grid, Flexbox, relative units,
semantic HTML, and a mobile-first approach, without any CSS framework.

## Preview

![Project preview](src/assets/img/preview.png)

## Project Structure

\`\`\`
/
├── index.html          # Main page
├── src/
│   ├── css/
│   │   └── style.css   # CSS styles
│   └── assets/
│       ├── img/        # Project images
│       └── icons/      # Icons
├── .gitignore
└── README.md
\`\`\`

This project uses a feature-branch workflow: each iteration is developed on a
separate branch, and work is split into small feature branches that are merged
back when complete. The branch structure for this project is:

\`\`\`
/
└── main
    └── develop
        └── vanilla-iteration
            ├── feature/navbar
            ├── feature/footer
            ├── feature/form
            ├── feature/desktop-styling
            └── feature/...
\`\`\`

## Technologies Used

- **HTML5** — Semantic structure
- **CSS3** — Styles and responsive design (Grid, Flexbox, custom properties, clamp())
- **Font Awesome** — Icons
- **GitHub Pages** (optional) — Deployment

## Installation and Execution

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- A code editor (recommended: VS Code)
- Git installed (optional but recommended)

### Steps to run the project

1. **Clone the repository** (or download the ZIP):
\`\`\`bash
git clone https://github.com/onisEg/it-sprint1-maquetacio.git
\`\`\`

2. **Navigate to the project folder**:
\`\`\`bash
cd it-sprint1-maquetacio
\`\`\`

3. **Open the HTML file in your browser**:
   - Option 1: Double-click on \`index.html\`
   - Option 2: Use Live Server in VS Code (recommended)

### Using Live Server in VS Code (recommended)

1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension
2. Right-click on \`index.html\`
3. Select "Open with Live Server"

## Usage

Customize the project by editing:
- \`index.html\` — Modify content and structure
- \`src/css/style.css\` — Change styles, colors, and design tokens
- \`src/assets/\` — Add your own images and icons

## Accessibility

- Semantic landmarks (\`header\`, \`nav\`, \`main\`, \`section\`, \`article\`, \`footer\`)
- Visible, associated \`<label>\` elements for every form field
- Empty \`alt\`  for decorative icons and descriptive \`alt\` for meaningful images
- \`aria-label\` on icon-only links (social media)
- Visible keyboard focus styles and logical heading order

## Contributors

- **Anas** — [GitHub](https://github.com/onisEg)


---

If you liked this project, give it a star on GitHub