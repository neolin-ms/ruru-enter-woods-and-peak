# 🌲 Ru山Ru林 | RuRu Enter Woods & Peaks

An all-in-one web platform designed for hiking enthusiasts to explore trails, log hiking tracks, and streamline national park entry permit applications.

## 🚀 Key Features

*   **Trail Discovery:** Search and filter hiking trails by difficulty, location, and elevation.
*   **Route Tracker:** Upload, record, and export GPX/KML routes with interactive 3D map rendering.
*   **Permit Automation:** Simplified, step-by-step wizard for National Park entry and cabin applications.
*   **Community Hub:** Share trail conditions, weather updates, and packing checklists.

## 🛠️ Tech Stack

*   **Frontend:** React.js / Next.js (TypeScript), Tailwind CSS
*   **Backend:** Node.js (Express) / Python (FastAPI)
*   **Database:** PostgreSQL (with PostGIS for geospatial data) / MongoDB
*   **Maps & GIS:** Mapbox GL JS / Leaflet
*   **Authentication:** JWT / OAuth 2.0 (Google & GitHub login)

## 📂 Repository Structure

```text
ru-enter-woods-and-peaks/
├── client/                 # Frontend application
│   ├── src/components/     # UI Components (Maps, Forms, Cards)
│   └── src/pages/          # Trail Search, Dashboard, Permit System
├── server/                 # Backend API
│   ├── controllers/        # Permit submission, User auth logic
│   └── models/             # Database schemas (User, Trail, Route)
├── services/               # Third-party integrations (Weather API, Government Permit API)
└── README.md
```

## 💻 Getting Started

### Prerequisites
*   Node.js (v18+) or Python (3.10+)
*   Docker (Optional, for database setup)

### Installation
1. Clone the repository:
   ```bash
   git clone github.com
   ```
2. Install dependencies:
   ```bash
   cd client && npm install
   cd ../server && npm install
   ```
3. Set up your environment variables (`.env`):
   ```env
   MAPBOX_TOKEN=your_mapbox_token
   DATABASE_URL=your_database_url
   GOV_PERMIT_API_KEY=your_api_key
   ```
4. Run the development servers:
   ```bash
   # In /client
   npm run dev
   # In /server
   npm start
   ```

## 🤝 Contributing
Contributions are welcome! Please read the `CONTRIBUTING.md` file for details on our code of conduct and the process for submitting pull requests.
