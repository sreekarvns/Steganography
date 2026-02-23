Steganography App
A modern, full-featured steganography application for hiding and retrieving secret messages within images and audio files. Built with React, TypeScript, and Tailwind CSS.
Features

Image Steganography: Hide and retrieve messages in image files
Audio Steganography: Embed secret data in audio files
Message Detection: Detect hidden messages in media files
Research Suite: Advanced tools and analysis capabilities
Dark Mode Support: Beautiful light and dark themes
Responsive Design: Works seamlessly on desktop and mobile devices
Audio Mode: Dedicated interface for audio-based operations

Tech Stack

Frontend: React 18 with TypeScript
Styling: Tailwind CSS 4 with custom theming
Build Tool: Vite 5
UI Components: shadcn/ui (Radix UI primitives)
Animations: Framer Motion
Forms: React Hook Form
Notifications: Sonner Toast

Getting Started
Prerequisites

Node.js (v16 or higher)
npm or yarn

Installation
bashnpm install
Development
bashnpm run dev
The app will be available at http://localhost:5173
Build
bashnpm build
Project Structure

App.tsx - Main application component with routing
components/ - Reusable React components
globals.css - Global styles and CSS variables
tailwind.config.ts - Tailwind CSS configuration
vite.config.ts - Vite build configuration

Features Overview
Core Modules

HomePage: Main navigation hub
HideMessage: Encode messages into images
RetrieveMessage: Extract hidden messages from images
DetectorPage: Analyze media for hidden content
AudioModePage: Audio steganography operations
SettingsPanel: User preferences and theme control

Styling
The application uses a comprehensive color system with CSS variables supporting both light and dark modes. Colors are automatically managed through Tailwind CSS configuration.
Attribution
This project includes:

Components from shadcn/ui (MIT License)
Images from Unsplash

Security
Please refer to SECURITY.md for security policies and vulnerability reporting procedures.
License
[Add your license here]

Note: This is a cutting-edge steganography tool for educational and legitimate purposes. Please ensure compliance with local laws and regulations when using this application.
