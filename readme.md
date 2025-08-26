# Edufy - Educational Platform

A modern, responsive educational dashboard built with React, Material-UI, and Tailwind CSS. Edufy provides an intuitive interface for managing educational content, analytics, and user interactions.

## 🚀 Features

- **Modern Dashboard Interface**: Clean and responsive design using Material-UI components
- **Tailwind CSS Styling**: Utility-first CSS framework for rapid UI development
- **Interactive Charts**: Data visualization with ApexCharts and Charts.css
- **PDF Generation**: Built-in PDF rendering capabilities with React-PDF
- **State Management**: Redux Toolkit for efficient state management
- **Responsive Design**: Mobile-first approach with responsive breakpoints
- **Firebase Hosting**: Ready for deployment on Firebase

## 🛠️ Tech Stack

### Frontend
- **React 18** - Modern React with hooks and functional components
- **Vite** - Fast build tool and development server
- **Material-UI (MUI)** - React component library
- **Tailwind CSS** - Utility-first CSS framework
- **Redux Toolkit** - State management solution
- **React Router DOM** - Client-side routing

### UI Components & Libraries
- **@material-tailwind/react** - Material Design components with Tailwind
- **@headlessui/react** - Unstyled, accessible UI components
- **@heroicons/react** - Beautiful hand-crafted SVG icons
- **Flowbite React** - UI component library built on Tailwind CSS
- **Styled Components** - CSS-in-JS styling solution

### Development Tools
- **PostCSS** - CSS processing
- **Prettier** - Code formatting
- **ESLint** - Code linting and quality

## 📁 Project Structure

```
Edufy_project-SIP/
├── frontend/                 # React application
│   ├── dist/                # Build output
│   ├── src/                 # Source code
│   ├── public/              # Static assets
│   ├── package.json         # Dependencies and scripts
│   ├── vite.config.js       # Vite configuration
│   ├── tailwind.config.cjs  # Tailwind CSS configuration
│   ├── firebase.json        # Firebase hosting configuration
│   └── .firebaserc          # Firebase project configuration
├── ngrok.yml                # Ngrok configuration for tunneling
└── README.md                # This file
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** (version 16 or higher)
- **npm** or **yarn** package manager
- **Firebase CLI** (for deployment)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Edufy_project-SIP/frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## 🎨 Customization

### Tailwind CSS
The project uses Tailwind CSS for styling. You can customize the design system by modifying:
- `tailwind.config.cjs` - Tailwind configuration
- `src/index.css` - Global styles and Tailwind directives

### Material-UI Theme
Customize the Material-UI theme in your main component or theme provider to match your brand colors and design preferences.

## 🚀 Deployment

### Firebase Hosting

1. **Install Firebase CLI** (if not already installed)
   ```bash
   npm install -g firebase-tools
   ```

2. **Login to Firebase**
   ```bash
   firebase login
   ```

3. **Build the project**
   ```bash
   npm run build
   ```

4. **Deploy to Firebase**
   ```bash
   firebase deploy
   ```

The project is already configured for Firebase hosting with the project ID `edufy-50353`.

### Environment Variables

Create a `.env` file in the frontend directory for any environment-specific configurations:

```env
VITE_API_URL=your_api_url_here
VITE_FIREBASE_CONFIG=your_firebase_config
```

## 📱 Responsive Design

The application is built with a mobile-first approach and includes responsive breakpoints for:
- Mobile devices (320px+)
- Tablets (768px+)
- Desktop (1024px+)
- Large screens (1280px+)

## 🔧 Development

### Code Formatting
The project uses Prettier for consistent code formatting. Run:
```bash
npx prettier --write .
```

### Linting
Ensure code quality by running the linter:
```bash
npx eslint src/
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

If you encounter any issues or have questions:
- Check the existing issues in the repository
- Create a new issue with detailed information
- Contact the development team

## 🔮 Future Enhancements

- [ ] User authentication and authorization
- [ ] Real-time notifications
- [ ] Advanced analytics dashboard
- [ ] Mobile app development
- [ ] API integration for educational content
- [ ] Multi-language support

---

**Built with ❤️ using React, Material-UI, and Tailwind CSS**
