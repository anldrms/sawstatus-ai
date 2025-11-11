# SAWSTATUS

> **Real-time Flight Tracker and Live Air Traffic Information for Istanbul Sabiha Gökçen Airport (LTFJ/SAW)**

![SAWSTATUS](https://img.shields.io/badge/Airport-LTFJ%20%2F%20SAW-blue)
![Status](https://img.shields.io/badge/Status-Operational-success)
![License](https://img.shields.io/badge/License-MIT-green)

## 🛫 Overview

SAWSTATUS is a modern, lightweight, and mobile-friendly web application that provides real-time flight tracking, weather information, and aviation data for Istanbul Sabiha Gökçen International Airport. Built with vanilla JavaScript, HTML5, and CSS3, it offers a fast and responsive user experience.

## ✨ Features

- **🗺️ Live Flight Map**: Real-time aircraft tracking with RadarBox integration
- **🛬 Arrivals & Departures**: Live flight information boards
- **🌤️ Weather Data**: METAR and TAF reports updated hourly
- **🌍 Weather Radar**: Interactive wind and weather conditions via Windy
- **📡 Live ATC**: Ground and Tower radio communications
- **📄 Airport Charts**: Downloadable navigation charts for LTFJ
- **🎫 Flight Search**: Integrated Skyscanner widget for booking
- **⚡ Performance**: Lazy loading, DNS prefetch, and optimized assets
- **📱 Responsive**: Perfect on desktop, tablet, and mobile devices

## 🚀 Quick Start

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/igastatus/sawstatus-ai.git
cd sawstatus-ai
```

2. Open in your browser:
```bash
open index.html
# or
python3 -m http.server 8000
```

3. Visit `http://localhost:8000`

### Deployment

Deploy to any static hosting service:

- **GitHub Pages**: Push to `gh-pages` branch
- **Vercel**: Connect your repository
- **Netlify**: Drag and drop the folder
- **AWS S3**: Upload as static website

## 📂 Project Structure

```
sawstatus/
├── index.html              # Main HTML file
├── css/
│   └── style.css          # Styles with glassmorphism effects
├── js/
│   └── main.js            # JavaScript with lazy loading
├── charts/
│   ├── LTFJCHART2024.pdf  # Latest navigation charts
│   └── LTFJCHART2023.pdf  # Archive charts
├── favicon.ico            # Site favicon
└── README.md              # This file
```

## 🛠️ Technologies

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern design with glassmorphism, animations, and responsive grid
- **Vanilla JavaScript**: No frameworks, pure performance
- **APIs Used**:
  - RadarBox (Flight Tracking)
  - CheckWX (METAR/TAF)
  - Windy (Weather)
  - FlightRadar.Live (Flight Info Boards)
  - LiveATC (Radio Audio)
  - Skyscanner (Flight Search)

## 🎨 Design Philosophy

- **Modern & Clean**: Glassmorphism effects and smooth animations
- **Performance First**: Lazy loading, optimized images, minimal dependencies
- **Mobile Responsive**: Fluid design that works on all screen sizes
- **Accessibility**: Semantic HTML and ARIA labels
- **Aviation-Focused**: Purpose-built for aviation enthusiasts

## 📊 Performance

- **First Contentful Paint**: < 1.5s
- **Time to Interactive**: < 3.0s
- **Lighthouse Score**: 90+ (Performance, Accessibility, Best Practices, SEO)
- **Bundle Size**: < 50KB (excluding external widgets)

## 🔧 Configuration

### Update CheckWX API Key

Edit `index.html` line 43:
```html
<script src="https://api.checkwx.com/widget?key=YOUR_API_KEY&refresh=15"></script>
```

Get your free API key at [CheckWX.com](https://www.checkwx.com/)

### Customize Colors

Edit `css/style.css` lines 14-24 (CSS Variables):
```css
:root {
    --primary-color: #00a9e0;
    --secondary-color: #003d5c;
    --accent-color: #00c389;
    /* ... */
}
```

## 🌐 Browser Support

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ iOS Safari 14+
- ✅ Chrome Android 90+

## 📱 Mobile Features

- Touch-optimized interface
- Responsive images and layouts
- Fast loading on slow connections
- Minimal data usage with lazy loading

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Anıl Baki Durmuş**
- GitHub: [@igastatus](https://github.com/igastatus)
- Website: [sawstatus.com](https://sawstatus.com)

## 💖 Support

If you find this project useful, consider supporting:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-yellow)](https://buymeacoffee.com/anldrms)

## 🙏 Acknowledgments

- Aviation data providers (RadarBox, CheckWX, FlightRadar.Live)
- Weather services (Windy, MeteoBlue)
- Istanbul Sabiha Gökçen Airport
- Open-source community

## 📞 Contact

For questions, suggestions, or issues:
- Open an [Issue](https://github.com/igastatus/sawstatus-ai/issues)
- Visit [sawstatus.com](https://sawstatus.com)

---

**Made with ❤️ for Aviation Enthusiasts**

*Last Updated: November 2025*
# sawstatus-ai
# sawstatus-ai
