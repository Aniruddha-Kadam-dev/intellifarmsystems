
### Frontend (`aifarmerUI/`)
- Built with **React**, **TypeScript**, and **Vite** for fast, modern web development.
- Handles user interface, authentication, and interaction with backend APIs.

### Backend (`backend/`)
- Built with **Node.js** and **Express**.
- Provides RESTful APIs for user management, crop data, disease detection, market prices, community forums, and weather information.
- Uses a modular structure with separate route, model, and middleware files.

### Documentation (`docs/`)
- Contains static assets and documentation for the project.

## ⚙️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Backend Setup

```bash
cd backend
npm install
# Configure your database in backend/config/database.js
npm start
```

### Frontend Setup

```bash
cd aifarmerUI
npm install
npm run dev
```

- The frontend will typically run on [http://localhost:5173](http://localhost:5173)
- The backend will typically run on [http://localhost:5000](http://localhost:5000)

## 📦 Features

- **User Authentication**: Secure login and registration for farmers.
- **Crop Management**: Add, view, and manage crop data.
- **Disease Detection**: AI-powered detection and advice for crop diseases.
- **Market Prices**: Real-time market price updates for various crops.
- **Community Forum**: Connect and share knowledge with other farmers.
- **Weather & Schemes**: Access weather forecasts and government schemes.

## 🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## 📄 License

This project is licensed under the MIT License.

---

*Empowering farmers with technology for a smarter tomorrow.*