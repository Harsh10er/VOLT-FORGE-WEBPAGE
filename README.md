# 🔥 VoltForge - PC Gaming Performance Tracker

A modern web application for tracking and analyzing PC gaming performance metrics. Built with React, Tailwind CSS, and Vite.

![VoltForge Dashboard](https://img.shields.io/badge/Status-Live-brightgreen)
![React](https://img.shields.io/badge/React-19.1.1-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-4.1.12-38B2AC)
![Vite](https://img.shields.io/badge/Vite-7.1.2-646CFF)

## 🎯 What is VoltForge?

VoltForge is a PC gaming performance tracker that lets gamers log, analyze, and visualize key system performance metrics during their gaming sessions. Track FPS, CPU/GPU usage, RAM usage, power consumption, and hardware frequencies across different games and sessions.

## ✨ Features

### 📊 Dashboard
- Overview of gaming statistics and recent sessions
- Performance metrics cards with visual indicators
- Quick access to recent gaming sessions

### ⚡ Live Monitor
- Real-time performance monitoring
- Animated progress bars for FPS, power, temperature
- CPU and GPU usage tracking
- Live status indicators

### 📝 Session Logging
- Record detailed gaming sessions
- Track game name, duration, FPS, and power consumption
- Add custom notes for each session
- Form validation and data persistence

### 📈 Session History
- View and analyze past gaming sessions
- Filter sessions by game name
- Calculate power consumption (kWh)
- Detailed session information with notes

### 🖥️ My Rig
- Manage your gaming setup configuration
- Edit hardware specifications
- Track CPU, GPU, RAM, storage, PSU, and monitor details
- Inline editing with save/cancel functionality

## 🚀 Tech Stack

- **Frontend**: React 19.1.1 with modern hooks
- **Styling**: Tailwind CSS 4.1.12 with custom components
- **Routing**: React Router DOM for navigation
- **Build Tool**: Vite 7.1.2 for fast development
- **Icons**: Emoji-based icons for modern UI

## 🛠️ Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/voltforge.git
   cd voltforge
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the port shown in terminal)

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📁 Project Structure

```
voltforge/
├── src/
│   ├── components/
│   │   └── ui/           # Reusable UI components
│   ├── entities/         # Data models
│   ├── layout/           # Layout components
│   ├── pages/            # Page components
│   ├── utils/            # Utility functions
│   ├── App.jsx           # Main app component
│   ├── main.jsx          # App entry point
│   └── index.css         # Global styles
├── public/               # Static assets
├── vite.config.js        # Vite configuration
└── package.json          # Dependencies and scripts
```

## 🎨 UI Components

### Layout
- **Responsive sidebar navigation** with collapsible menu
- **Professional header** with toggle functionality
- **Main content area** with proper spacing and overflow handling

### Cards & Buttons
- **Custom card components** with shadows and borders
- **Primary and secondary buttons** with hover effects
- **Form inputs** with focus states and validation

### Navigation
- **Sidebar navigation** with active state indicators
- **Icon-based menu items** with smooth transitions
- **Responsive design** that works on all screen sizes

## 🔧 Configuration

### Tailwind CSS
The project uses Tailwind CSS v4 with custom configuration:
- Custom color palette for VoltForge branding
- Responsive design utilities
- Custom component classes

### Vite Configuration
- React plugin for JSX support
- Tailwind CSS Vite plugin for styling
- PostCSS disabled to avoid conflicts

## 🎮 Usage

1. **Dashboard**: View your overall gaming statistics and recent sessions
2. **Live Monitor**: Monitor real-time performance metrics (simulated data)
3. **Log Session**: Record new gaming sessions with detailed metrics
4. **History**: Browse and filter your past gaming sessions
5. **My Rig**: Manage your hardware configuration

## 🚀 Future Enhancements

- [ ] Real hardware monitoring integration
- [ ] Data persistence with local storage or database
- [ ] Performance charts and graphs
- [ ] Export functionality for session data
- [ ] User authentication and cloud sync
- [ ] Mobile responsive improvements
- [ ] Dark mode theme
- [ ] Performance benchmarking tools

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with ❤️ for the PC gaming community
- Inspired by the need for better gaming performance tracking
- Thanks to the React and Tailwind CSS communities

---

**VoltForge** - Track. Analyze. Optimize. 🎮⚡