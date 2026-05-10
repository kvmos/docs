# RiAdmin Dashboard


A modern admin dashboard template built with Vite, React, TypeScript.

### Getting Started

Firstly, a huge thanks for purchasing this theme, your support is truly appreciated!

This document covers the installation and use of this theme and often reveals answers to common problems and issues - read this document thoroughly if you are experiencing any difficulties. If you have any questions that are beyond the scope of this document, feel free to email at [suppot@ducor.net](mailto:__EMAIL__) Thank you so much!

##### Main Dependencies
- [React](https://reactjs.org)
- [Tailwind CSS](https://tailwindcss.com)
- [TypeScript](https://www.typescriptlang.org)

#### Prerequisites

Before you begin, make sure your development environment includes the following:

#### 1 . Node.js 
[Node Js](https://nodejs.org) is a JavaScript runtime that allows you to run JavaScript code outside of a web browser. Since our project uses JavaScript, Node.js is required to build and run the application.

Install Node.js using downloaded file.

To check your node version, run node -v in a terminal/console window & Ensure that you have Node.js (v16 or higher)
  ```bash
  node -v
npm -v
  ```

### 2 . pnpm
[pnpm](https://pnpm.io) is a fast and efficient package manager for Node.js projects. It manages and installs libraries your project depends on. pnpm is more performant and disk space-saving compared to npm or yarn.

`pnpm` is a fast and disk space-efficient package manager for managing dependencies in JavaScript projects. It helps with installing, updating, configuring, and removing dependencies, allowing you to reach your goals more quickly and with fewer distractions.

> **Note**: Unlike most other package managers that delegate non-install-related commands to other tools, `pnpm` reimplements all commands to have full control over the developer experience and stability.

- Once you have Node.js and npm installed, You also need pnpm installed globally. If you do not have pnpm,Install pnpm globally using npm: 
```bash
pnpm install -g pnpm
```
Verify Yarn installation with:
```bash
pnpm -v
```
For better understanding Vue we suggest you to once go through official documentation of Pnpm from [pnpm.io](https://pnpm.io)

#### Basic

1.  After unzip the download pack, you'll found a Template Folder with all the files.
- **RiAdmin Template**: An installable React.js template zip file.
- **Documentation Folder**: Contains this documentation you are reading now.



### Workspace Structure

```bash
riadmin/
│
├── packages/
│   ├── cms/                    → Main React + ViteJS admin template
│   │   ├── public/             → Static assets
│   │   ├── src/                → Application source code
│   │   ├── vite.config.ts
│   │   ├── package.json
│   │   └── tsconfig.json
│   │
│   ├── color/                  → Theme colors and design tokens
│   ├── forms/                  → Reusable form system
│   ├── helpers/                → Shared utility functions
│   ├── hooks/                  → Custom React hooks
│   ├── notify/                 → Notification and toast system
│   ├── types/                  → Shared TypeScript types
│   └── ui/                     → Shared UI component library
│
├── nx.json                     → Nx workspace configuration
├── lerna.json                  → Lerna package management configuration
├── pnpm-workspace.yaml         → pnpm workspace configuration
├── package.json                → Root dependencies and scripts
└── tsconfig.base.json          → Shared TypeScript configuration
```

---

#### Architecture Overview

The `cms` package is the main application template built with React and ViteJS.

All other packages inside the `packages/` directory are designed specifically for the CMS application as reusable internal libraries.

This structure helps keep the project:

- Modular
- Reusable
- Scalable
- Maintainable
- Easy to extend

---

### Packages

#### cms

Main React + ViteJS admin dashboard template.

#### Includes

- Public assets
- Application pages
- Routing system
- Dashboard layouts
- Authentication pages
- Vite configuration
- Application entry setup

---

#### color

Shared color system and design tokens.

##### Features

- Theme palettes
- Global colors
- Design token management
- Dark & light mode support

---

#### forms

Reusable form utilities and components.

#### Features

- Form components
- Validation helpers
- Input management
- Shared form logic

---

#### helpers

Shared utility functions across the workspace.

#### Features

- Date helpers
- String utilities
- Object utilities
- General reusable helpers

---

#### hooks

Reusable custom React hooks.

#### Features

- State hooks
- UI hooks
- Lifecycle helpers
- Shared application hooks

---

### notify

Notification and toast management system.

#### Features

- Toast notifications
- Alert system
- Global notification handlers

---

### types

Shared TypeScript interfaces and type definitions.

#### Features

- Shared interfaces
- API response types
- Common utility types

---

### ui

Reusable UI component library.

#### Features

- Buttons
- Inputs
- Modals
- Cards
- Layout components
- Shared design system

---

### Core Technologies

| Technology | Description |
|---|---|
| Nx | Monorepo workspace management |
| Lerna | Internal package management |
| pnpm | Fast dependency management |
| React | Frontend UI library |
| ViteJS | Frontend build tool |
| TypeScript | Static typing support |

---



###  Project Installation 
Before running the project, you need to install a few essential tools:

1.  Open your terminal or command prompt.
2.  Navigate to the project folder.
   ```bash
   cd riadmin
   ``` 
3.  Run the following commands to set up the project:

 **Install Dependencies:**
 ```bash
 pnpm install
 ```
 **Start Development Server:** This command starts the development server, enabling you to preview changes live in your browser. By 
     default, the server runs at `http://localhost:5173/`.
 ```bash
    pnpm run dev
  ```
#### Add a New Package with `pnpm`

To add a new package to your project, use the following command:

```bash
pnpm add <package-name>

```



### Customizer

Use the layout customizer to:

- Choose between `Light`, `Dark` themes
- Switch between layout **direction**: `ltr` (Left-to-Right) or `rtl` (Right-to-Left)
- Set **header position**: `fixed` or `static`
- Choose **sidebar type**: `mini`, `full`, or `compact`
- Change **sidebar position**: `fixed` or `static`


![image](./dark-mode.png)
![image](./layout-customizer.png)

- **Sidebar Colors**: Select sidebar color options to match your style
- **Global Fonts**: Change the font family for the **entire website** with just a click


![image](./color-font-customizer.png)

These powerful tools help you design a fully personalized and professional interface in minutes.

If you want to remove customizer from whole template, Just you need to remove ducor > src > provider > admin.tsx in  <Customizer /> component

###  Build for Production  

To build the project for production, use:  

```bash
pnpm run build
```

####  Clean Up  

To remove the `node_modules` folder and clean your project, run:  

```bash
pnpm run clean
```

###  Support  

If you enjoy using our product, [Please Rate Us](https://themeforest.net/user/ducor). 😊  

# Sources & Credits

- [React](https://react.dev)
- [Tailwind CSS](https://tailwindcss.com)
- [Axios](https://axios-http.com)
- [React Router](https://reactrouter.com)
- [Headless UI](https://headlessui.com)
- [React Icons](https://react-icons.github.io/react-icons)
- [Sonner](https://sonner.emilkowal.ski)
- [Chart.js](https://www.chartjs.org) + [React ChartJS 2](https://react-chartjs-2.js.org)
- [Recharts](https://recharts.org)
- [FullCalendar](https://fullcalendar.io)
- [Tailwind Plugins](https://tailwindcss.com/docs/plugins):
  - `@tailwindcss/forms`
  - `@tailwindcss/typography`
  - `@tailwindcss/aspect-ratio`
  - `@tailwindcss/container-queries`
- [Tailwind Merge](https://github.com/dcastil/tailwind-merge)
- [React i18next](https://react.i18next.com)
- [Prettier](https://prettier.io)
- [Prop Types](https://github.com/facebook/prop-types)

