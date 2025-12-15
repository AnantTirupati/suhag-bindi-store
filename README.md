# Suhag Bindi Store - Frontend Prototype

This is a complete, production-ready frontend prototype for **Suhag Bindi Store**, a Varanasi-based wholesale and retail jewelry business. It is built with React, TypeScript, and Tailwind CSS, featuring a modern, responsive design with a traditional Indian aesthetic.

## 🚀 Quick Start

Follow these steps to get the project running on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/) (Version 18 or higher recommended)
- [npm](https://www.npmjs.com/) (Included with Node.js)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd suhag-bindi-store
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

### Running Locally

To start the development server:

```bash
npm run dev:client
```

This will start the Vite development server at `http://localhost:5000`. Open this URL in your browser to view the application.

> **Note:** You can also run `npm run dev` to start the backend proxy server if needed, but for frontend-only development, `npm run dev:client` is faster and sufficient.

### Building for Production

To build the application for deployment:

```bash
npm run build
```

This generates a production-ready build in the `dist/public` directory.

## 🛠️ Tech Stack

*   **Framework:** [React](https://react.dev/) with [Vite](https://vitejs.dev/)
*   **Routing:** [wouter](https://github.com/molefrog/wouter) (Lightweight router for React)
*   **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
*   **UI Components:** [shadcn/ui](https://ui.shadcn.com/) (Radix UI + Tailwind)
*   **Icons:** [Lucide React](https://lucide.dev/)
*   **Fonts:** Poppins (Body) & Playfair Display (Headings) via Google Fonts
*   **Animation:** tailwindcss-animate

## 📂 Project Structure

```
├── client/
│   ├── src/
│   │   ├── components/
│   │   │   ├── layout/       # Navbar, Footer, Layout wrappers
│   │   │   ├── ui/           # Reusable UI components (Buttons, Cards, etc.)
│   │   │   └── ...
│   │   ├── lib/              # Utilities and mock data
│   │   ├── pages/            # Page components (Home, Products, Admin)
│   │   ├── App.tsx           # Main application component & Routing
│   │   └── index.css         # Global styles & Tailwind configuration
│   └── index.html            # Entry HTML file
├── attached_assets/          # Generated images and assets
├── package.json              # Project dependencies and scripts
└── vite.config.ts            # Vite configuration
```

## 🎨 Design System

*   **Primary Color:** Deep Maroon (`#7A1F2B`)
*   **Accent Color:** Gold (`#D4AF37`)
*   **Background:** Warm Off-White (`#FAF7F2`)
*   **Typography:**
    *   *Headings:* Playfair Display (Serif)
    *   *Body:* Poppins (Sans-serif)

## 👤 Admin Access (Mock)

The project includes a mock admin dashboard for demonstration purposes.
*   **Login URL:** `/admin/login`
*   **Credentials:** Pre-filled (Just click "Login")

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
