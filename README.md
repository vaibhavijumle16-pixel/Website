# 🏥 AI Hospital Command Center

A real-time, AI-assisted dashboard for monitoring and managing hospital operations — patient flow, bed capacity, staffing, and critical alerts — all in a single, clean command-center view.

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-06B6D4?logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Backend-3ECF8E?logo=supabase&logoColor=white)

---

## ✨ Overview

**AI Hospital Command Center** gives hospital administrators and clinical staff a unified view of what's happening across the facility. It combines live data visualization with AI-driven insights to help teams make faster, better-informed decisions.

## 🚀 Features

- 📊 **Live analytics dashboards** — interactive charts for admissions, occupancy, and throughput
- 🛏️ **Bed & resource management** — track capacity across wards and departments
- 🚨 **Alerts & prioritization** — surface critical events so nothing gets missed
- 🤖 **AI-powered insights** — predictive suggestions to support operational decisions
- ☁️ **Cloud backend** — authentication and data storage powered by Supabase
- ⚡ **Fast & responsive** — built on Vite with a modern, mobile-friendly UI

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | React 18 + TypeScript |
| Build tool | Vite |
| Styling | Tailwind CSS |
| State management | Zustand |
| Charts | Recharts |
| Icons | Lucide React |
| Backend / Database | Supabase |
| Linting | ESLint + typescript-eslint |

## 📦 Getting Started

### Prerequisites

- Node.js 18+
- npm
- A [Supabase](https://supabase.com) project

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

# Install dependencies
npm install
```

### Environment variables

Create a `.env` file in the project root:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Run locally

```bash
npm run dev
```

The app will be available at `http://localhost:5173`.

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run ESLint |
| `npm run typecheck` | Run TypeScript type checking |

## 📁 Project Structure

```
├── src/
│   ├── main.tsx        # App entry point
│   └── ...             # Components, stores, utilities
├── index.html
├── vite.config.ts
├── tailwind.config.js
└── tsconfig.app.json
```

> Tip: imports use the `@/` alias, which maps to `src/`.

## 🗺️ Roadmap

- [ ] Role-based access for doctors, nurses, and admins
- [ ] Predictive patient-surge forecasting
- [ ] Real-time notifications
- [ ] Exportable reports

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License.

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-profile](https://linkedin.com/in/your-profile)

---

⭐ If you found this project useful, consider giving it a star!
