# SiteKit

A lightweight, browser-based website template generator inspired by the design and visual identity of 0xfarco.

Create customizable landing pages and sub-pages using the original website's typography, colors, and minimalist design language — without writing HTML or CSS manually.

## Features
- Multiple Page Templates
    - Landing Page
    - usr — About
    - opt — Projects
    - bin — System
    - var — Contact
    - Generic Sub-page
- Flexible Content Editor
    - Add multiple content sections.
    - Choose between text and table content.
    - Customize section headings.
    - Add and remove sections.
    - Automatically renumber sections after deletion.
    - Move sections up and down.
    - Support multiple paragraphs.
- Table Generator
    - Create tables with multiple columns and rows.
    - Customize column headings and cell content.
    - Generate HTML tables automatically.
- Live Preview
    - Preview changes directly in the browser.
    - See generated content before exporting.
- Style Customization
    - Background color
    - Text color
    - Hover color
    - Original typography
- HTML Export
    - Export generated pages as standalone HTML files.
    - Generated pages retain their styling and content.
    - No framework or build process required.

## Design

The generator follows the visual design language of the original 0xfarco website.

| Element          | Value           |
| ---              | ---             |
| Background       | #111111       |
| Text             | #ffffff       |
| Hover            | #ff6600       |
| Table background | #222222       |
| Border           | #333333       |
| Heading font     | Press Start 2P  |
| Body font	       | Share Tech Mono |

Original website: `https://0xfarco.github.io/`

## Getting Started

1. Clone the repository

```bash
git clone https://github.com/0xfarco/sitekit.git
```

2. Open the project

Navigate to the project directory:

```bash
cd sitekit
```
3. Run the generator

Open `index.html` in your preferred web browser.

No installation, dependencies, or build tools are required.

Alternatively, use a local development server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## How to Use
1. Select a Page Template

Choose the type of page you want to generate from the template selector.

2. Customize Page Information

Edit the page identifier, main heading, and description.

3. Add Content Sections

Under 02 / CONTENT, you can:

- Edit the initial section heading and content.
- Add additional sections.
- Choose Text or Table for each additional section.
- Remove unwanted sections.
- Rearrange sections.
- Automatically maintain sequential section numbering.

4. Customize the Appearance

Under 03 / STYLE, customize the background, text, and hover colors.

5. Preview Your Page

Use the live preview to see the generated page.

6. Export HTML

Click Export HTML to download your generated page.

Table Content Format

When creating a table, use the following format:

```text
Project | Description | Status
Portfolio | Personal website | Active
Dashboard | Admin interface | Completed
API | Backend service | In Progress
```

The first line defines the table headings. Every subsequent line represents a table row.
