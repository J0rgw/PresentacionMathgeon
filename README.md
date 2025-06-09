# MathGeon - Interactive Book Presentation

An interactive digital book presentation for the MathGeon project, featuring smooth page transitions, keyboard navigation, and an interactive tech stack display.

## Features

- 📖 **Interactive Book Layout**: Realistic book-like interface with left and right pages
- ⌨️ **Keyboard Navigation**:
  - `→` or `Space`: Move to next page
  - `←`: Move to previous page
  - `f`: Show frontend technologies
  - `b`: Show backend technologies
- 🎨 **Tech Stack Display**:
  - Toggle between frontend and backend technologies
  - Clean, responsive design with hover effects
  - Icons for all technologies used in the project

## Technologies Used

### Frontend
- React
- TypeScript
- CSS3
- Firebase

### Backend
- Rust
- WebAssembly (WASM)
- GitHub
- Docker

## Project Structure

```
.
├── index.html         # Main HTML file with all content
├── main.css           # Main stylesheet
├── README.md          # This file
└── .gitignore         # Git ignore file
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/J0rgw/PresentacionMathgeon.git
   cd PresentacionMathgeon
   ```

2. **Open in Browser**
   - Simply open `index.html` in your preferred web browser
   - No build process or dependencies required

3. **Using the Book**
   - Use the arrow keys or spacebar to navigate between pages
   - Press 'f' to view frontend technologies
   - Press 'b' to view backend technologies

## Deployment

This project is deployed using GitHub Pages. Visit the live site at:
[MathGeon Presentation](https://j0rgw.github.io/PresentacionMathgeon/)

## Development

### Adding New Pages
1. Add a new `.carousel-item` div in `index.html`
2. Follow the existing structure with `page left-page` and `page right-page` divs
3. Add your content inside the appropriate page divs

### Styling
- Main styles are in `main.css`
- Page-specific styles can be added in the style section of `index.html`

## License

This project is open source and available under the [MIT License](LICENSE).

## Authors

- Jorge Arcas Verdejo
- Javier Sanz Valero

---

💡 **Tip**: For the best experience, view this presentation in full-screen mode in your web browser.
