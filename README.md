# QRisk

A minimal, privacy-focused website to educate users about the risks of scanning unknown QR codes. This project aims to raise awareness about QR code-based security threats through an interactive and engaging user experience.

## About

QRisk is a static website that demonstrates how malicious QR codes could lead users to potentially harmful websites. When users land on the page, they're presented with a sequence of educational messages about QR code security, followed by specific risks and safety tips.

### Key Features

- Privacy-focused design (no external dependencies or tracking)
- Fully responsive layout
- System font stack for improved privacy
- Smooth animations and transitions
- Dark theme with high contrast for accessibility
- Mobile-first approach

## Project Structure

```
qrisk/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet with animations
├── nullNEU.png     # Project logo
└── README.md       # This documentation
```

## Technical Details

### Privacy Features

- No external fonts (uses system font stack)
- No JavaScript
- No analytics or tracking
- No external dependencies
- Self-contained CSS animations

### Browser Support

- Modern browsers (Brave, Chrome, Firefox, Safari)
- Mobile browsers
- Graceful degradation for older browsers

## Security Tips Covered

The website educates users about several QR code-related risks:
- Malicious website redirects
- Automatic malware downloads
- Payment scam techniques
- General QR code safety practices


### Customization

The project uses CSS variables for easy theming. Main colors can be modified in `styles.css`:
```css
:root {
    --primary-red: #cc0000;
    --dark-bg: #111111;
    --text-light: #ffffff;
    --accent-gray: #333333;
}
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.
