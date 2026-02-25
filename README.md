# SaaS Landing Page

This project is a modern and clean landing page designed for a SaaS product. It is built with Next.js, React, and TailwindCSS, offering a responsive and visually appealing user interface.

## Features

-   **Responsive Design**: Adapts seamlessly to various screen sizes and devices.
-   **Interactive Components**: Utilises `framer-motion` for engaging animations and transitions.
-   **Modular Structure**: Organised into reusable components and sections for easy maintenance and scalability.
-   **Modern UI**: Clean and contemporary design with `TailwindCSS` for rapid styling.
-   **TypeScript**: Enhances code quality and developer experience with static type checking.

## Technologies Used

-   **Next.js 15**: React framework for production-grade applications.
-   **React 18**: JavaScript library for building user interfaces.
-   **TypeScript**: Superset of JavaScript for type-safe development.
-   **TailwindCSS**: A highly customisable, utility-first CSS framework.
-   **Framer Motion**: A powerful animation library for React.
-   **clsx**: A tiny utility for constructing `className` strings conditionally.

## Up and Running

To get this project up and running on your local machine, follow these steps:

### Prerequisites

Ensure you have Node.js (v18 or higher) and npm installed.

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/eanutt1272v2/SaaS-Landing-Page.git
    cd SaaS-Landing-Page
    ```
2.  Install dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

### Running the Development Server

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Project Structure

```
SaaS-Landing-Page/
├── public/                   # Static assets
├── src/
│   ├── app/                  # Next.js app router pages
│   ├── assets/               # Images, icons, etc.
│   ├── components/           # Reusable UI components
│   └── sections/             # Page sections (Hero, Pricing, Testimonials, etc.)
├── tailwind.config.ts        # TailwindCSS configuration
├── tsconfig.json             # TypeScript configuration
└── package.json              # Project dependencies and scripts
```

## License

Distributed under the MIT License. See LICENSE for more information.
