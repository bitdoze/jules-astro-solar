# SolarCo - Modern Solar Panel Company Website

This project is a modern, responsive website for "SolarCo", a fictional solar panel company. It's built using Astro, TailwindCSS, and vanilla JavaScript (implicitly, as Astro can use it). The website showcases the company's services, projects, and provides information about them, aiming for a clean, professional, and engaging user experience.

## Features

*   **Homepage:** Engaging hero section, services overview, client testimonials, recent projects, and a clear call to action.
*   **About Page:** Information about the company's mission, vision, and team.
*   **Services Page:** Detailed descriptions of services offered (Residential, Commercial, Battery Storage, Maintenance).
*   **Contact Page:** Contact form and detailed contact information.
*   **Responsive Design:** Adapts to various screen sizes from mobile to desktop.
*   **Modern Styling:** Utilizes TailwindCSS for a utility-first styling approach.
*   **SVG Icons:** Custom SVG icons for branding and visual elements.
*   **Subtle Animations & Transitions:** Smooth hover effects and transitions to enhance UX.

## Technologies Used

*   **[Astro](https://astro.build/):** The web framework for building fast, content-focused websites.
*   **[TailwindCSS](https://tailwindcss.com/):** A utility-first CSS framework for rapid UI development.
*   **SVG:** For icons and graphical elements.
*   **Node.js & npm:** For project management and dependencies.

## Project Structure

The main source code is located in the `src/` directory:

*   `src/assets/`: Contains static assets like SVG icons (`icons/`) and images (`images/`).
*   `src/components/`: Reusable Astro components used across various pages (e.g., `Header.astro`, `Footer.astro`, `Hero.astro`).
*   `src/layouts/`: Main layout structure for pages (e.g., `MainLayout.astro`).
*   `src/pages/`: Individual pages of the website (e.g., `index.astro`, `about.astro`).
*   `src/styles/`: Global styles, primarily for TailwindCSS setup (`global.css`).

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   [Node.js](https://nodejs.org/) (LTS version recommended)
*   [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1.  **Clone the repository (or download the source code):**
    ```bash
    # If you were using git, it would be:
    # git clone <repository-url>
    # cd <repository-name>
    ```
    (For this environment, assume files are already present)

2.  **Navigate to the project directory:**
    (This is usually the root where `package.json` is located)

3.  **Install NPM packages:**
    ```bash
    npm install
    ```

### Running the Development Server

Once the dependencies are installed, you can start the Astro development server:

```bash
npm run dev
```

This will typically start the server on `http://localhost:4321`. Open this URL in your web browser to see the website. The server will automatically reload when you make changes to the files.

### Building for Production

To create a production build of the website:

```bash
npm run build
```

The optimized static files will be generated in the `dist/` directory. You can preview the production build locally using:

```bash
npm run preview
```

## Design Notes

*   **Colors:** The primary color scheme revolves around greens (eco-friendly, growth), blues (technology, reliability), and yellows (energy, optimism), with grays for neutrality and text.
*   **Icons:** Custom SVGs are used to provide a unique visual identity. Ensure any new SVGs are optimized.
*   **Animations:** Animations are kept subtle to enhance user experience without being distracting. These are primarily CSS-based transitions.

## Further Development (TODO)

*   Implement mobile menu toggle functionality (JavaScript).
*   Add a functional backend for the contact form.
*   Integrate a CMS for easier content management.
*   Add more detailed project pages and a project gallery.
*   Optimize images and SVGs further.
*   Implement advanced SEO features.
