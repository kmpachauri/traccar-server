# Traccar Web Frontend

Modern web application for GPS tracking built with React/Vue.js.

## Features
- Real-time device tracking
- Interactive maps
- Reports and analytics
- Geofence management
- User management
- Mobile responsive

## Development Setup

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation
```bash
npm install
npm start
```

### Build for Production
```bash
npm run build
```

## Docker Deployment
```bash
docker build -t traccar-web .
docker run -p 3000:80 traccar-web
```

## Environment Variables
```bash
REACT_APP_API_URL=https://api.yourdomain.com
REACT_APP_MAP_API_KEY=your_map_api_key
REACT_APP_FIREBASE_CONFIG=your_firebase_config
```

## Configuration
- API endpoint configuration in `.env`
- Map providers in `src/config/maps.js`
- Theme customization in `src/theme/`

## Build Optimization
- Code splitting
- Tree shaking
- Asset optimization
- PWA support
- CDN integration

## Browser Support
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License
Apache License 2.0