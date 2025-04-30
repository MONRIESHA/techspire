# Green Neya Integrated Agricultural Company Limited Website

A modern, responsive website for Green Neya Integrated Agricultural Company Limited, showcasing their sustainable agriculture initiatives, services, and community impact.

## Features

- Responsive design that works on all devices
- Modern and clean user interface with nature-inspired design
- Interactive sections including testimonials slider and news updates
- Smooth scrolling navigation
- Contact form for inquiries
- Animated content sections
- Mobile-friendly navigation menu

## Project Structure

```
.
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── js/
│   └── main.js         # JavaScript functionality
└── images/             # Website images
```

## Setup Instructions

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Navigate to the project directory:
```bash
cd green-neya-website
```

3. Open the website:
- Double-click the `index.html` file, or
- Use a local development server:
  ```bash
  # Using Python 3
  python -m http.server 8000
  
  # Using Node.js
  npx serve
  ```

4. View the website in your browser:
- If using a local server, visit `http://localhost:8000`

## Dependencies

- Font Awesome 6.0.0 (CDN)
- Modern browser with JavaScript enabled

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Customization

### Colors
The website uses CSS variables for easy color customization. Edit the following variables in `css/styles.css`:

```css
:root {
    --primary-color: #2E7D32;
    --secondary-color: #81C784;
    --accent-color: #4CAF50;
    --text-color: #333;
    --light-text: #666;
    --white: #fff;
}
```

### Content
- Update the content in `index.html`
- Modify testimonials and news items in `js/main.js`
- Replace images in the `images` directory

## Development

### Adding New Sections
1. Create a new section in `index.html`
2. Add corresponding styles in `css/styles.css`
3. Add any necessary JavaScript functionality in `js/main.js`

### Modifying Styles
- All styles are modular and organized by section in `css/styles.css`
- Use the existing CSS variables for consistency
- Follow the BEM naming convention for new classes

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

[Add your license information here]

## Contact

[Add your contact information here] 