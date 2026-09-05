# Shadow Generator 🎨

A web-based tool for creating and visualizing custom CSS box shadows in real time. Easily customize shadow properties through graphic controls and copy the generated CSS code with a single click.

🌐 **Live Demo:** **[https://draggerbox.vercel.app](https://draggerbox.vercel.app)**

---

## Features

- **Live Preview:** See shadow changes instantly as you adjust the controls[cite: 1, 3].
- **Customizable Controls:**
  - Horizontal & Vertical offsets (`-100px` to `100px`)
  - Blur Radius (`0px` to `100px`)
  - Spread Radius (`-50px` to `50px`)[cite: 3]
  - Shadow Color (Hex picker)[cite: 3]
  - Opacity (`0` to `1`)[cite: 3]
  - Inset Shadow toggle[cite: 3]
- **One-Click Code Copy:** Copy the resulting CSS `box-shadow` property directly to your clipboard[cite: 1, 3].
- **Responsive Interface:** Styled with Bootstrap 5 and custom CSS for smooth performance on desktop and mobile[cite: 2, 3].

---

## File Structure

```text
.
├── index.html          # Main HTML structure[cite: 3]
├── js/
│   └── index.js        # DOM interaction & RGBA conversion logic
├── style/
│   └── style.css       # Page styling, loading animation & layout[cite: 2]
└── Media/
    └── Favicon/        # Site icons & manifest[cite: 3, 5]
