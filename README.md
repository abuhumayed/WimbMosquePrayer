Wimbledon Mosque Prayer Times PWA
A Progressive Web Application providing accurate prayer times and Jumuah schedules for Wimbledon Mosque community members.

🌐 Live Application
🔗 https://wimbledon-mosque-times.vercel.app/

Try it now - works on all devices and can be installed to your home screen!

🕌 Overview
This PWA delivers real-time prayer times for the Wimbledon Mosque, featuring a responsive design optimized for mobile devices with offline capabilities and home screen installation.

✨ Features
Real-time Prayer Times: Accurate daily prayer schedules (Fajr, Zuhr, Asr, Maghrib, Isha)
Jumuah Schedule: Special Friday prayer timings with English talk schedule
Progressive Web App: Installable on mobile devices for native app-like experience
Responsive Design: Optimized for all screen sizes and devices
Dark/Light Mode: Automatic theme switching with user preference persistence
Offline Support: Service worker implementation for offline functionality
Date Navigation: Browse prayer times for any date
Live Clock: Real-time display with automatic updates
📱 Quick Start
Visit: wimbledon-mosque-times.vercel.app
Install: Tap "Add to Home Screen" for app-like experience
Use: Access prayer times instantly from your home screen
🛠️ Technical Stack
Framework: Next.js 15 with App Router
Language: TypeScript
Styling: Tailwind CSS
Icons: Lucide React
PWA: Custom service worker implementation
Deployment: Vercel
Performance: Optimized with React 19 features
📱 PWA Features
Installable: Add to home screen on iOS/Android
Offline Capable: Works without internet connection
App-like Experience: Standalone display mode
Fast Loading: Optimized performance and caching
Responsive Icons: Custom mosque-themed app icons
🏗️ Architecture
src/
├── app/                    # Next.js App Router
│   ├── api/               # API routes
│   ├── globals.css        # Global styles
│   └── page.tsx          # Main application
├── components/            # React components
│   ├── date-navigation.tsx
│   ├── mosque-logo.tsx
│   ├── theme-toggle.tsx
│   └── install-prompt.tsx
├── lib/                   # Utilities and data
│   ├── prayer-calendar.ts # Prayer times data
│   └── performance.ts     # Performance monitoring
└── public/               # Static assets
    ├── manifest.json     # PWA manifest
    └── sw.js            # Service worker
🎨 Design Features
Custom Mosque Logo: SVG-based scalable branding
Islamic Color Palette: Green and gold theme reflecting Islamic aesthetics
Accessibility: WCAG compliant with proper ARIA labels
Typography: System fonts for optimal performance
Animations: Smooth transitions and micro-interactions
📊 Performance
Lighthouse Score: 95+ across all metrics
First Contentful Paint: < 1.5s
Time to Interactive: < 2.5s
Bundle Size: Optimized with tree-shaking
Caching Strategy: Efficient service worker implementation
🔧 Installation & Development
# Clone repository
git clone https://github.com/yourusername/wimbledon-mosque-prayer-times.git

# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
📅 Data Management
Prayer times are managed through a comprehensive calendar system covering the entire year with:

Accurate prayer time calculations
Seasonal adjustments (Summer/Winter time)
Special Jumuah scheduling
Jamat time specifications
🌐 Browser Support
Chrome/Edge: Full PWA support with install prompts
Safari: iOS home screen installation
Firefox: Basic PWA functionality
Mobile Browsers: Optimized responsive experience
🚀 Deployment
Deployed on Vercel with:

Automatic deployments from main branch
Edge runtime optimization
Global CDN distribution
Custom domain configuration
📈 Future Enhancements
 Push notification system for prayer reminders
 Qibla direction compass
 Islamic calendar integration
 Multi-language support
 Prayer time calculation API
🤝 Contributing
Contributions welcome! Please read our contributing guidelines and submit pull requests for any improvements.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

📞 Contact
For questions or support regarding this application, please contact the Wimbledon Mosque community.

Built with ❤️ for the Wimbledon Mosque community

🔗 Live Demo: wimbledon-mosque-times.vercel.app

