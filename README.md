# Dashboard & Authentication

A modern, highly responsive frontend dashboard created as part of the Elabram assessment. It is built using **Vue 3**, **Vite**, **Vuetify**, and **Chart.js**, demonstrating a robust layout for employee statistics, task, attendance, and leave management.

## 🛠️ Technology Stack & Dependencies

*   **Runtime**: [Node.js](https://nodejs.org/) or [Bun](https://bun.sh)
*   **Frontend Framework**: [Vue 3](https://vuejs.org/) + [Vite](https://vitejs.dev/) - Composition API and fast frontend tooling.
*   **UI Framework**: [Vuetify](https://vuetifyjs.com/) - Material Design component framework.
*   **Routing**: [Vue Router](https://router.vuejs.org/) - Single Page Application routing.
*   **Data Visualization**: [Chart.js](https://www.chartjs.org/) - Used for attendance and task statistics.
*   **Styling**: SCSS/SASS and Vuetify plugins.

## ✨ Features

-   **Authentication Flow**: Login and Registration forms (`Login.vue`, `Register.vue`).
-   **Dashboard Overview**: View attendance summaries, current task progress, and employee profile.
-   **Employee Statistics**: In-depth visualization of employee tasks and attendance across periods.
-   **Data Visualization**: Rich interactive charts (`ChartAttendanceSummary`, `ChartTaskComplete`, etc.).
-   **Leave Management**: Clear tabulation of employee leave recaps (`TableLeaveRecap`).
-   **Responsive Layouts**: Consistent application layout structuring content optimally across various device sizes.

## 🏗️ Architecture

This is a single-page application heavily relying on a **Component-Based Architecture**:
- **Views (`src/views`)**: Contain the primary page structures (Overview, Employee Stats, Login, etc.).
- **Components (`src/components`)**: Modular, reusable UI chunks (Charts, Tables, Lists, Inputs).
- **Layouts (`src/layouts`)**: High-level structural wrappers (e.g., `AppLayout.vue` for the dashboard shell).

### Project Structure

```text
assessment_elabram/
├── public/                 # Static assets
├── src/                    # Source code
│   ├── assets/             # Internal assets (images, global CSS)
│   ├── components/         # Reusable UI components (Charts, Forms, Tables)
│   ├── layouts/            # Application layouts (AppLayout)
│   ├── plugins/            # Setup for Vuetify, Web Fonts
│   ├── router/             # Vue Router configuration
│   ├── styles/             # Global SCSS/CSS
│   ├── views/              # Main page views (Login, Overview, EmployeeStat)
│   ├── App.vue             # Root component
│   └── main.js             # Application entry point
├── package.json            # Dependencies and scripts
└── vite.config.js          # Vite configuration
```

## 🚀 Installation & Quick Start

1.  **Install Dependencies**
    Using npm, yarn, pnpm or bun:
    ```bash
    npm install
    # or
    yarn install
    # or
    bun install
    ```

2.  **Start Development Server**
    ```bash
    npm run dev
    # or
    yarn dev
    # or
    bun run dev
    ```
    The application will be accessible at standard Vite dev port (e.g., `http://localhost:5173` or `http://localhost:3000`).

3.  **Build for Production**
    ```bash
    npm run build
    ```

4.  **Lint & Fix Files**
    ```bash
    npm run lint
    ```

## 📄 License
Private project for technical assessment.
