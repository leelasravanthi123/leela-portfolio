# Portfolio – Pathella Leela Sravanthi

Single-page portfolio site for **Pathella Leela Sravanthi**, an Associate Software Engineer (Backend).

The site is a scrollable one-page layout with sections for:

- Hero (name, role, short intro, social links)
- About
- Experience
- Projects
- Skills
- Achievements & Certifications
- Contact

## How to run it locally

1. Open the folder in your file explorer:
   - `c:\Users\LeelaP\Downloads\LeelaP-Portofolio`
2. Double-click `index.html` to open it in your browser (Chrome, Edge, etc.).

That’s it – no build step or framework is required.

## Customizing

- **Profile photo**:
  - Currently, the hero section shows your initials (`LS`) in a gradient circle.
  - If you want a real photo:
    - Create a folder called `assets` next to `index.html`.
    - Put your photo inside it as `profile.jpg`.
    - Optionally, update the CSS in `styles.css` for `.hero-avatar` to use your image as a background.

- **Text content**:
  - All content lives in `index.html`.
  - You can edit:
    - Summary text in the **Hero** and **About** sections.
    - Experience / Projects bullets.
    - Skills, Achievements, Certifications, and Contact details.

- **Colors & theme**:
  - All colors are defined at the top of `styles.css` under the `:root` CSS variables.
  - Change `--accent` and background values to tweak the theme.

## Next steps

- Once you’re happy with the portfolio, you can:
  - Initialize a Git repository.
  - Push it to GitHub as your portfolio repo.

When you’re ready, I can walk you step by step through pushing this folder to GitHub from your machine.
