# NASA Astronomy Picture of the Day (APOD)

A modern React application that displays NASA's Astronomy Picture of the Day using the official NASA API. This application provides users with daily astronomical images, videos, and educational content directly from NASA's extensive collection.

## 🚀 Features

- **Daily Astronomy Content**: Automatically fetches and displays NASA's Astronomy Picture of the Day
- **Responsive Design**: Optimized for desktop and mobile viewing experiences
- **Caching System**: Implements local storage caching to reduce API calls and improve performance
- **Interactive Modal**: Detailed view with high-resolution images and comprehensive descriptions
- **Real-time Updates**: Fresh content delivered daily from NASA's official API

## 🌐 Live Demo

**Production Site**: [NASA : Astronomy Picture of the Day](https://nasa-apod-blond.vercel.app/)

## 🛠️ Technology Stack

- **Frontend**: React 18.3.1
- **Build Tool**: Vite 5.4.10
- **Styling**: CSS3 with modern responsive design
- **API**: NASA Open Data API
- **Deployment**: Vercel
- **Code Quality**: ESLint with React plugins

## 📋 Prerequisites

Before running this project, ensure you have the following installed:

- Node.js (v14.0.0 or higher)
- npm or yarn package manager
- NASA API Key (free registration at [api.nasa.gov](https://api.nasa.gov/))

## ⚡ Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/MaheshR03/nasa-react-app.git
   cd nasa-react-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```
   VITE_NASA_API_KEY=your_nasa_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 🎯 API Integration

This application integrates with NASA's APOD API endpoint:
- **Base URL**: `https://api.nasa.gov/planetary/apod`
- **Authentication**: API Key required
- **Rate Limits**: 1000 requests per hour (default)
- **Response Format**: JSON with image URLs, descriptions, and metadata

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint code analysis

## 📸 Screenshots

### Main Interface
<img width="1920" height="906" alt="NASA APOD Main Interface" src="https://github.com/user-attachments/assets/9a975c45-78b6-46d3-8277-38a886fd77b3" />

### Detailed View Modal
<img width="1889" height="904" alt="NASA APOD Detailed View" src="https://github.com/user-attachments/assets/e949295c-cbf0-47ff-8417-041a546bc15c" />

## 🏗️ Project Structure

```
nasa-react-app/
├── public/
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── Footer.jsx
│   │   ├── Main.jsx
│   │   └── SideBar.jsx
│   ├── assets/
│   │   └── react.svg
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── package.json
├── vite.config.js
├── eslint.config.js
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [NASA Open Data Portal](https://api.nasa.gov/) for providing free access to space imagery and data
- [React](https://reactjs.org/) for the excellent frontend framework
- [Vite](https://vitejs.dev/) for the fast build tool and development experience
- [Vercel](https://vercel.com/) for seamless deployment and hosting

## 📞 Contact

For questions, suggestions, or collaboration opportunities, please feel free to reach out.

---

**Made with ❤️ and fascination for space exploration**
