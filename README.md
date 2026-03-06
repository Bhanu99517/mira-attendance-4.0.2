# Mira Attendance 4.0.2

An AI-powered attendance management application built with React, TypeScript, and Google Gemini. Mira Attendance streamlines tracking and managing attendance records with an intelligent assistant at its core.

🔗 **Live Demo:** [mira-attendance-4-0-2.vercel.app](https://mira-attendance-4-0-2.vercel.app)

---

## Features

- 📋 **Attendance Tracking** — Mark, view, and manage attendance records in an intuitive interface
- 🤖 **AI Integration** — Powered by Google Gemini for intelligent assistance and automation
- ⚡ **Fast & Responsive** — Built with Vite for lightning-fast dev and production builds
- 🧩 **Modular Architecture** — Clean separation of components, services, and types

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 18 |
| Language | TypeScript |
| Bundler | Vite |
| AI Client | Google Gemini API |
| Deployment | Vercel |

---

## Project Structure

```
mira-attendance-4.0.2/
├── components/          # Reusable UI components
├── App.tsx              # Root application component
├── components.tsx       # Shared component definitions
├── constants.tsx        # App-wide constants
├── geminiClient.ts      # Google Gemini API client setup
├── services.ts          # Business logic and data services
├── types.ts             # TypeScript type definitions
├── index.tsx            # Application entry point
├── index.html           # HTML template
├── vite.config.ts       # Vite configuration
└── tsconfig.json        # TypeScript configuration
```

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- A [Google Gemini API key](https://aistudio.google.com/app/apikey)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Bhanu99517/mira-attendance-4.0.2.git
   cd mira-attendance-4.0.2
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory:
   ```env
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

   The app will be available at `http://localhost:5173`.

### Build for Production

```bash
npm run build
```

The production-ready output will be in the `dist/` folder.

---

## Deployment

This project is deployed on **Vercel**. To deploy your own instance:

1. Push the repository to GitHub.
2. Import the project into [Vercel](https://vercel.com).
3. Add your `VITE_GEMINI_API_KEY` as an environment variable in the Vercel project settings.
4. Deploy — Vercel handles the rest automatically.

---

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## License

This project is open source. See the repository for license details.

