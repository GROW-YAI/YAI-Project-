# Cashew Extractor - YAI Project

## Project Overview

The Cashew Extractor is a modern, responsive e-commerce website for an innovative agricultural product - the Cashew Seeds Detaching Machine. This locally designed and manufactured machine is revolutionizing cashew farming by automating the seed extraction process, significantly reducing labor costs and improving efficiency for farmers.

### Key Features

- **Modern React Application**: Built with React 19, Vite, and Tailwind CSS for a fast, responsive user experience
- **Accessibility First**: Integrated with the Boafo Accessibility Widget to ensure the site is accessible to all users, including those with disabilities
- **Interactive UI Components**: Smooth animations powered by Framer Motion for an engaging user experience
- **Multi-page Navigation**: Comprehensive site structure including:
  - Landing page with hero section, about us, and featured products
  - Product details with customization options and features
  - Shop section with bulk orders and payment methods
  - Contact and FAQ pages
  - About the innovator section
- **Newsletter Integration**: Email subscription functionality for customer engagement
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices

### Technologies Used

- **Frontend Framework**: React 19 with JSX
- **Build Tool**: Vite 6
- **Styling**: Tailwind CSS 4
- **Animations**: Framer Motion
- **Routing**: React Router DOM 7
- **Icons**: FontAwesome, Heroicons, Lucide React, React Icons
- **Accessibility**: Boafo Accessibility Widget
- **Form Handling**: React Hook Form

## How to Get Your Boafo API Key

To enable the accessibility features on this site, you'll need to obtain a Boafo API key:

1. Visit [boafo.co](https://boafo.co)
2. Register for an account or log in if you already have one
3. Navigate to your dashboard
4. Generate a new API key for your project
5. Copy the API key - you'll need it for the setup

## How to Integrate the Boafo Widget

For detailed instructions on integrating the Boafo Accessibility Widget into your project, refer to the official integration guide:

📄 **[Boafo Widget Integration Guide](https://drive.google.com/file/d/1tvwK-sBZI2a4uldd6z5LD1iLblSl3WbG/view?usp=sharing)**

This comprehensive guide covers:
- Widget installation and setup
- Configuration options
- Customization features
- Best practices for accessibility

## Setup Instructions

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or pnpm package manager
- Git

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/GROW-YAI/YAI-Project-.git
   cd YAI-Project-
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   pnpm install
   ```

3. **Set up environment variables**
   
   Copy the example environment file:
   ```bash
   cp .env.example .env
   ```
   
   Open the `.env` file and add your Boafo API key:
   ```
   VITE_BOAFO_API_KEY=your_actual_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   # or
   pnpm dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173` (or the URL shown in your terminal)

### Build for Production

To create a production build:
```bash
npm run build
# or
pnpm build
```

The built files will be in the `dist/` directory.

### Preview Production Build

To preview the production build locally:
```bash
npm run preview
# or
pnpm preview
```

## Project Structure

```
YAI-Project-/
├── app/
│   ├── components/
│   │   └── BoafoWidgetInitializer.tsx
│   └── layout.tsx
├── src/
│   ├── assets/
│   │   └── images/
│   ├── components/
│   │   ├── constants/
│   │   ├── footer.jsx
│   │   ├── navbar.jsx
│   │   └── ...
│   ├── pages/
│   │   └── landingPage/
│   │       ├── aboutPage/
│   │       ├── contact/
│   │       ├── product/
│   │       ├── shop/
│   │       └── *.jsx
│   └── types/
│       └── global.d.ts
├── public/
├── .env
├── .env.example
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `VITE_BOAFO_API_KEY` | Your Boafo Accessibility Widget API key | Yes |

See `.env.example` for the complete list of environment variables.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is proprietary. All rights reserved.

## Contact

For questions or support, please contact the YAI Project team.

---

**Built with ❤️ by the YAI Team**