# 🖥️ Enhanced Device Info App

[![Next.js](https://img.shields.io/badge/Next.js-15.1.2-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.0.0-blue?style=flat-square&logo=react)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.1-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![TypeScript Ready](https://img.shields.io/badge/TypeScript-Ready-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

A comprehensive, real-time device information and performance monitoring application built with modern web technologies. Get detailed insights about your device, monitor system performance, and export data securely.

🌐 **Live Demo**: [https://your-info.sahinur.dev/](https://your-info.sahinur.dev/)

---

## ✨ Features

### 📊 **Real-time Performance Monitoring**
- **Live System Metrics**: CPU usage, memory consumption, frame rate tracking
- **Interactive Charts**: Real-time visualization of performance data
- **Network Analytics**: Connection speed, latency monitoring
- **Storage Insights**: Disk usage and quota information
- **GPU Information**: Graphics card details and WebGL capabilities

### 🔧 **Comprehensive Device Detection**
- **Hardware Details**: CPU cores, device memory, touch capabilities
- **Display Specifications**: Screen resolution, color depth, pixel ratio
- **Browser Intelligence**: Engine details, feature support, compatibility
- **Network Information**: Connection type, speed, data saving mode
- **Advanced APIs**: WebGL, WebAssembly, Sensor APIs, Service Workers
- **60+ Data Points**: Extensive device and browser information

### 🎨 **Modern User Experience**
- **Dark/Light Theme**: Seamless theme switching with system preference detection
- **Responsive Design**: Optimized for all screen sizes and devices
- **Collapsible Sections**: Organized content with smooth animations
- **Real-time Search**: Instant filtering across all device information
- **Professional UI**: Glass morphism effects, hover animations, modern typography

### 🔒 **Security & Privacy**
- **Security Dashboard**: Real-time security assessment and scoring
- **Privacy Controls**: Data anonymization and encryption utilities
- **Local Processing**: All data processing happens in your browser
- **No External Transmission**: Your data never leaves your device
- **Security Recommendations**: Personalized security improvement suggestions

### 📁 **Advanced Export Options**
- **Multiple Formats**: JSON, PDF, CSV, TXT export capabilities
- **Professional Reports**: Formatted PDF with charts and tables
- **Structured Data**: Clean CSV for spreadsheet analysis
- **Comprehensive JSON**: Full data export with metadata

### ♿ **Accessibility Features**
- **Keyboard Navigation**: Full keyboard support for all interactions
- **Screen Reader**: ARIA labels and semantic HTML structure
- **Font Size Control**: Adjustable text sizes for better readability
- **High Contrast**: Dark mode support for visual accessibility
- **Focus Management**: Clear focus indicators and logical tab order

### 📱 **Progressive Web App (PWA)**
- **Offline Functionality**: Works without internet connection
- **Installable**: Add to home screen on any device
- **Service Worker**: Advanced caching and background sync
- **Auto Updates**: Seamless app updates with notifications
- **Network Awareness**: Smart performance based on connection quality
- **Cross-Platform**: Native app experience on desktop and mobile

---

## 🚀 Demo

![Enhanced Device Info App](https://i.ibb.co.com/W4cmZVC9/page.png)

### Key Highlights:
- 🔴 **Real-time monitoring** with live performance charts
- 🌙 **Dark/Light mode** with smooth transitions
- 📱 **PWA Ready** - Install as native app, works offline
- 🔍 **Instant search** across all device data
- 📊 **Security scoring** and privacy analysis
- 💾 **Multi-format exports** (JSON, PDF, CSV, TXT)
- ⚡ **Service Worker** - Advanced caching and auto-updates

---

## 🛠️ Technologies Used

### **Frontend Framework**
- **Next.js 15.1.2**: React framework with App Router and Turbopack support
- **React 19.0.0**: Latest React with concurrent features
- **TypeScript Ready**: Full TypeScript support for type safety

### **Styling & UI**
- **Tailwind CSS 3.4.1**: Utility-first CSS framework
- **Custom CSS Variables**: Dynamic theming system
- **Heroicons**: Beautiful SVG icon library
- **Google Fonts**: Inter font family for modern typography

### **Data & Analytics**
- **Bowser**: Advanced browser detection library
- **Performance APIs**: Native browser performance monitoring
- **Web APIs**: Geolocation, Battery, Clipboard, WebGL, and more

### **Export & Utilities**
- **jsPDF 3.0.1**: Client-side PDF generation
- **jspdf-autotable 5.0.2**: Advanced table generation for PDFs
- **Custom Security Utils**: Data encryption and anonymization
- **CSV Generation**: Custom CSV export functionality

### **Development Tools**
- **ESLint**: Code linting and quality assurance
- **PostCSS**: CSS processing and optimization
- **Git Hooks**: Automated code quality checks

---

## 🚀 Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- **Node.js 18+**: Download from [nodejs.org](https://nodejs.org/)
- **npm/yarn/pnpm**: Package manager (npm comes with Node.js)
- **Git**: Version control system

### 📦 Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/SahinurDEV/Enhanced-Device-Info-App.git
   cd Enhanced-Device-Info-App
   ```

2. **Install Dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run Development Server**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open in Browser**

   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

### 🛠️ Available Scripts

```bash
npm run dev          # Start development server
npm run dev:turbo    # Start development server with Turbopack
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint for code quality
```

### 🔧 Configuration

The app works out of the box, but you can customize:

- **Theme Colors**: Edit CSS variables in `app/globals.css`
- **Font Settings**: Modify font imports in `app/layout.js`
- **Performance Intervals**: Adjust monitoring frequency in hooks
- **Export Settings**: Customize PDF/CSV generation in components

---

## 📱 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Full Support |
| Firefox | 88+ | ✅ Full Support |
| Safari | 14+ | ✅ Full Support |
| Edge | 90+ | ✅ Full Support |
| Opera | 76+ | ✅ Full Support |
| Mobile Safari | 14+ | ✅ Full Support |
| Chrome Mobile | 90+ | ✅ Full Support |

### Feature Support

- **Basic Device Info**: All modern browsers
- **Performance Monitoring**: Chrome 90+, Firefox 88+, Safari 14+
- **Real-time Charts**: All supported browsers
- **Export Functions**: All supported browsers
- **Dark Mode**: All supported browsers
- **Accessibility**: All supported browsers

---

## 🏗️ Project Structure

```
device-info-app/
├── app/
│   ├── globals.css          # Global styles and theme variables
│   ├── layout.js           # Root layout with theme provider
│   └── page.js             # Main page component
├── components/
│   ├── CollapsibleSection.js    # Expandable content sections
│   ├── DownloadManager.js       # Multi-format export system
│   ├── EnhancedDeviceInfo.js    # Main device info component
│   ├── InfoTable.js             # Data display table
│   ├── PerformanceChart.js      # Real-time chart component
│   ├── PerformanceMonitor.js    # System monitoring dashboard
│   ├── SecurityDashboard.js     # Security analysis component
│   └── ThemeToggle.js           # Dark/light mode toggle
├── contexts/
│   └── ThemeContext.js          # Theme state management
├── hooks/
│   ├── useEnhancedDeviceInfo.js # Device data collection
│   └── usePerformanceMonitor.js # Performance monitoring
├── utils/
│   └── security.js              # Security and encryption utilities
└── TROUBLESHOOTING.md           # Common issues and solutions
```

---

## 🎯 Usage Examples

### Basic Device Information
```javascript
import { useEnhancedDeviceInfo } from '@/hooks/useEnhancedDeviceInfo';

function MyComponent() {
  const { deviceInfo, realtimeUpdates, toggleRealtimeUpdates } = useEnhancedDeviceInfo();
  
  return (
    <div>
      <h2>Browser: {deviceInfo?.['Browser Name']}</h2>
      <button onClick={toggleRealtimeUpdates}>
        {realtimeUpdates ? 'Stop' : 'Start'} Real-time Updates
      </button>
    </div>
  );
}
```

### Performance Monitoring
```javascript
import { usePerformanceMonitor } from '@/hooks/usePerformanceMonitor';

function PerformanceDisplay() {
  const { performanceData } = usePerformanceMonitor();
  
  return (
    <div>
      <p>CPU Usage: {performanceData.cpuUsage}%</p>
      <p>Memory: {performanceData.memoryUsage?.percentage}%</p>
      <p>Frame Rate: {performanceData.frameRate} FPS</p>
    </div>
  );
}
```

### Theme Integration
```javascript
import { useTheme } from '@/contexts/ThemeContext';

function ThemedComponent() {
  const { theme, toggleTheme } = useTheme();
  
  return (
    <div className={`${theme === 'dark' ? 'bg-gray-900' : 'bg-white'}`}>
      <button onClick={toggleTheme}>
        Switch to {theme === 'light' ? 'dark' : 'light'} mode
      </button>
    </div>
  );
}
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Workflow

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Code Style

- Follow the existing code style
- Use meaningful commit messages
- Add comments for complex logic
- Ensure responsive design
- Test accessibility features

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Sahinur**
- GitHub: [@devSahinur](https://github.com/SahinurDEV)
- Website: [sahinur.dev](https://sahinur.dev)
- Email: infosahinur@gmail.com

---

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) for the amazing React framework
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Heroicons](https://heroicons.com/) for beautiful icons
- [jsPDF](https://github.com/parallax/jsPDF) for client-side PDF generation
- [Bowser](https://github.com/lancedikson/bowser) for browser detection
- The open-source community for inspiration and support

---

## 🔮 Roadmap

- [x] **PWA Support**: Service worker and offline functionality ✅ **COMPLETED**
- [ ] **Data Persistence**: Local storage for settings and history
- [ ] **Advanced Analytics**: Historical performance tracking
- [ ] **Customizable Dashboard**: Drag-and-drop interface
- [ ] **API Integration**: External device database lookup
- [ ] **Notification System**: Performance alerts and warnings
- [ ] **Multi-language Support**: Internationalization (i18n)
- [ ] **Plugin System**: Extensible architecture for custom features

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

**Built with ❤️ by [Sahinur](https://github.com/SahinurDEV)**

</div>
