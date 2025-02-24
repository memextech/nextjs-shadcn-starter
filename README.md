# Landing Page Starter Kit

## Overview

This template is a modern Next.js starter kit built with TypeScript and styled using Tailwind CSS. Inspired by the Shadcn UI pattern and powered by Radix UI primitives, this project comes with a comprehensive library of reusable UI components that accelerate building production-ready user interfaces.

## Potential app functionality expansions to explore

Here are some ideas of how to expand this template after you get it up and running:
- Give Memex a specific topic or idea and let it come up with a first draft of your website
- Update layouts, colors, components and sections
- Add authentication for admin usage


## Features

- **Next.js & React**: Optimized for server-side rendering and static site generation.
- **Rich Component Library**: Includes components such as Accordion, Alert Dialog, Avatar, Badge, Breadcrumb, Button, Calendar, Card, Carousel, Chart, Checkbox, Collapsible, Command, Context Menu, Dialog, Drawer, Dropdown Menu, Form, Hover Card, Input (and OTP), Label, Menubar, and more.
- **Tailwind CSS Styling**: Fully customizable theming with light/dark modes configured in `globals.css`.
- **Modern Layout**: A clean and responsive global layout defined in `layout.tsx` with integrated Google Fonts (Inter) and essential meta tags.
- **Developer Experience**: Organized file structure and scalable components for rapid development.

## Quick start

Just ask Memex to run this app locally and it will take care of the rest! If you run into any errors, just point Memex to fix them.

If you’d like to set up the environment and dependencies manually, follow these steps:

1. **Install Dependencies**

   Install the project dependencies using npm:
   ```bash
   npm install
   ```

2. **Run the Development Server**

   Start the development environment with:
   ```bash
   npm run dev
   ```

3. **Build for Production**

   When you're ready for deployment, build the project:
   ```bash
   npm run build
   ```
## File Structure

- **app/**
  - **`page.tsx`**  
    The entry point of the application. It displays a centered message ("Start prompting.") and serves as a placeholder for your home page content.
    
  - **`layout.tsx`**  
    Defines the root layout of your app. It imports global styles, applies typography using the Inter font, and sets essential metadata.
    
  - **`globals.css`**  
    Contains Tailwind CSS directives along with custom CSS variables and base styles. It defines a comprehensive theming system for light and dark modes.

- **components/**  
  This directory holds a rich collection of UI components—from basic inputs and buttons to more complex elements like carousels, charts, and menus—each built to work seamlessly with Tailwind CSS and styled following modern design principles.


## Development

See Rules for AI (rendered from .memex/rules.md) for detailed development guidelines Memex will follow, including:
- Complete setup instructions
- Model-specific parameters
- Error handling
- Potential improvements
- Development workflow

You can ask Memex to update rules.md to reflect your project needs as you expand it, or set it as part of your Custom Instructions so that it does it automatically after important steps.

## License

This project is licensed under the MIT License.
