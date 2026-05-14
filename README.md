# 📊 Analytics Dashboard

A modern, tabbed **analytics dashboard** built with **Next.js 15**, **React 19**, and **TypeScript**. Displays key metrics across four sections — User Stats, App Performance, Insights, and User Feedback — using interactive charts powered by Recharts and a polished UI with shadcn/ui.

---

## 🖥️ Dashboard Sections

| Tab                | Description                                      |
|--------------------|--------------------------------------------------|
| **User Stats**     | User activity, growth, and engagement metrics    |
| **App Performance**| Load times, error rates, and performance trends  |
| **Insights**       | Data-driven summaries and key takeaways          |
| **User Feedback**  | Reviews, ratings, and user sentiment analysis    |

---

## 📁 Project Structure

```
analytics-dashboard/
├── app/               # Next.js App Router pages & layouts
├── components/        # UI components
│   ├── user-stats.tsx       # User Stats tab
│   ├── app-performance.tsx  # App Performance tab
│   ├── insights.tsx         # Insights tab
│   └── user-feedback.tsx    # User Feedback tab
├── hooks/             # Custom React hooks
├── lib/               # Utility functions & helpers
├── public/            # Static assets
├── styles/            # Global CSS
├── dashboard.tsx      # Main dashboard with tab layout
├── components.json    # shadcn/ui config
├── next.config.mjs    # Next.js configuration
├── tailwind.config.ts # Tailwind CSS configuration
└── tsconfig.json      # TypeScript configuration
```

---

## 🛠️ Tech Stack

| Category        | Technology                           |
|-----------------|--------------------------------------|
| Framework       | Next.js 15.1.0                       |
| Language        | TypeScript 5                         |
| UI Library      | React 19                             |
| Styling         | Tailwind CSS 3 + tailwindcss-animate |
| Component Kit   | shadcn/ui (Radix UI primitives)      |
| Charts          | Recharts                             |
| Icons           | Lucide React                         |
| Theming         | next-themes (dark / light mode)      |
| Forms           | React Hook Form + Zod                |
| Date Utilities  | date-fns                             |
| Notifications   | Sonner (toast)                       |
| Package Manager | pnpm                                 |

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [pnpm](https://pnpm.io/) — install via `npm install -g pnpm`

### Installation

```bash
# Clone the repository
git clone https://github.com/pranjalisr/analytics-dashboard.git
cd analytics-dashboard

# Install dependencies
pnpm install
```

### Running the Dev Server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📜 Available Scripts

| Command       | Description                           |
|---------------|---------------------------------------|
| `pnpm dev`    | Start the development server          |
| `pnpm build`  | Build the app for production          |
| `pnpm start`  | Start the production server           |
| `pnpm lint`   | Run ESLint across the project         |

---

## ✨ Features

- 📈 **Interactive charts** — powered by Recharts (line, bar, area charts)
- 🗂️ **Tabbed layout** — clean navigation between dashboard sections
- 🌙 **Dark / Light mode** — via `next-themes`
- ♿ **Accessible UI** — built on Radix UI primitives
- 📱 **Fully responsive** — mobile-first layout
- ⚡ **App Router** — Next.js 15 file-based routing
- 🔔 **Toast notifications** — via Sonner

---

## 📦 Key Dependencies

| Package                   | Purpose                        |
|---------------------------|--------------------------------|
| `next`                    | React framework (App Router)   |
| `react` / `react-dom`     | UI rendering                   |
| `tailwindcss`             | Utility-first CSS              |
| `@radix-ui/*`             | Accessible UI primitives       |
| `recharts`                | Data visualization / charts    |
| `lucide-react`            | Icon library                   |
| `next-themes`             | Dark/light theme switching     |
| `react-hook-form` + `zod` | Form handling & validation     |
| `date-fns`                | Date formatting utilities      |
| `sonner`                  | Toast notifications            |
| `clsx` + `tailwind-merge` | Conditional class utilities    |
| `cmdk`                    | Command palette                |
| `vaul`                    | Drawer component               |
| `embla-carousel-react`    | Carousel / slider              |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
