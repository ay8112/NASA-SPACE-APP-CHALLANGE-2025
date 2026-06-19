# WELCOME TO NASA SPACE APP CHALLANGE 2025

## You can access this Project: https://nasachallange2025.netlify.app

## Project info


## How can I edit this code?

There are several ways of editing your application.

## ITS A NASA ASTRO WEATHER AI PREDICTABLE WEB APP 


**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

##TEAM NAME: CODE Breaker ##TEAM MEMBERS: 


1. Aman Singh Yadav
2. Aradhya Tripathi

##You can access Nasa Space App Challenges 2025 here: https://www.spaceappschallenge.org/

##About Team Details: https://www.spaceappschallenge.org/2025/find-a-team/code-breaker/

More details
# NASA Astro Weather AI - Complete Tech Stack Details 




## 📋 Project Title & Description

```
NASA Astro Weather AI
```

```
A sophisticated weather forecasting application featuring AI-powered insights, 
interactive 3D Earth visualization, and real-time meteorological data. 
Built with modern web technologies and serverless architecture.
```

---

## 🎯 One-Line Summary 

```
Full-stack weather forecasting app with 3D Earth visualization, AI-powered advice, 
and serverless backend using React, Three.js, TypeScript, and Supabase Edge Functions.
```

---

## 📝 Detailed Project Description (for Portfolio)

```
NASA Astro Weather AI is a space-themed weather forecasting application that combines 
real-time meteorological data with artificial intelligence to provide personalized 
weather advice. The application features an interactive 3D Earth globe with realistic 
textures and atmospheric effects, animated star fields, and a modern glass-morphism UI design.

Key Features:
• Real-time weather forecasting using Open-Meteo API
• AI-powered personalized weather advice using Google Gemini 2.5 Flash
• Interactive 3D Earth visualization with WebGL
• Location-based geocoding and weather data retrieval
• Responsive design with space-themed UI/UX
• Serverless backend architecture with Edge Functions
```

---

## 🛠️ Technologies Used (Bullet Format)

```
Frontend:
• React 18.3.1
• TypeScript
• Vite (Build Tool)
• Tailwind CSS
• Shadcn/UI Components
• React Router DOM

3D Visualization:
• Three.js
• React Three Fiber
• React Three Drei

State Management & Data Fetching:
• TanStack React Query
• React Hook Form
• Zod (Validation)

Backend & Cloud:
• Supabase (BaaS)
• Deno Edge Functions
• Lovable AI Gateway

External APIs:
• Open-Meteo Weather API
• Open-Meteo Geocoding API
• Google Gemini 2.5 Flash (via AI Gateway)
```

---

## 🛠️ Technologies Used (Comma-Separated)

```
React, TypeScript, Vite, Tailwind CSS, Shadcn/UI, Three.js, React Three Fiber, 
React Three Drei, TanStack Query, React Hook Form, Zod, Supabase, Deno, 
Edge Functions, Google Gemini AI, Open-Meteo API
```

---

## 📊 Technical Skills Demonstrated

```
• Frontend Development: React, TypeScript, Component Architecture
• 3D Graphics & WebGL: Three.js, React Three Fiber, Shader Programming
• UI/UX Design: Tailwind CSS, Responsive Design, Glass-morphism Effects
• API Integration: RESTful APIs, Geocoding, Weather Data
• AI/ML Integration: LLM APIs, Prompt Engineering, AI Gateway
• Backend Development: Serverless Functions, Deno Runtime
• Cloud Services: Supabase, Edge Computing, BaaS Architecture
• State Management: React Query, Custom Hooks
• Form Handling: React Hook Form, Zod Validation
• Build Tools: Vite, ESLint, PostCSS
```

---

## 🏗️ Architecture Overview

```
┌─────────────────────────────────────────────────────────────┐
│                    FRONTEND (React + Vite)                  │
├─────────────────────────────────────────────────────────────┤
│  Components:                                                │
│  • WeatherSearch - Location & date input                    │
│  • WeatherResults - Weather data display                    │
│  • Earth3D - Interactive 3D globe (Three.js)                │
│  • StarField - Animated background                          │
├─────────────────────────────────────────────────────────────┤
│                         ↓ API Calls                         │
├─────────────────────────────────────────────────────────────┤
│                    EXTERNAL APIS                            │
│  • Open-Meteo Geocoding API (Location → Coordinates)        │
│  • Open-Meteo Weather API (Coordinates → Weather Data)      │
├─────────────────────────────────────────────────────────────┤
│                         ↓                                   │
├─────────────────────────────────────────────────────────────┤
│              SUPABASE EDGE FUNCTION (Deno)                  │
│  • weather-ai-advice                                        │
│  • Processes weather data                                   │
│  • Calls Lovable AI Gateway                                 │
├─────────────────────────────────────────────────────────────┤
│                         ↓                                   │
├─────────────────────────────────────────────────────────────┤
│                 AI GATEWAY                          │
│  • Google Gemini 2.5 Flash Model                            │
│  • Generates personalized weather advice                    │
└─────────────────────────────────────────────────────────────┘
```

---

## 📦 Dependencies List

```json
{
  "Frontend Framework": "React 18.3.1",
  "Language": "TypeScript",
  "Build Tool": "Vite",
  "Styling": "Tailwind CSS + tailwindcss-animate",
  "UI Components": "Shadcn/UI (Radix UI primitives)",
  "3D Graphics": "Three.js 0.180.0 + React Three Fiber 8.18.0 + Drei 9.122.0",
  "Routing": "React Router DOM 6.30.1",
  "Data Fetching": "TanStack React Query 5.83.0",
  "Forms": "React Hook Form 7.61.1 + Zod 3.25.76",
  "Backend": "Supabase + Deno Edge Functions",
  "AI": "Google Gemini 2.5 Flash via Lovable AI Gateway",
  "Notifications": "Sonner 1.7.4",
  "Date Handling": "date-fns 3.6.0"
}
```

---

## 🎨 Key Features (for Resume)

```
• Developed interactive 3D Earth visualization using Three.js and React Three Fiber
• Integrated real-time weather data from Open-Meteo API with geocoding support
• Implemented AI-powered weather advice using Google Gemini 2.5 Flash model
• Built serverless backend with Supabase Edge Functions (Deno runtime)
• Designed responsive UI with Tailwind CSS and glass-morphism effects
• Created animated star field background with canvas-based rendering
• Implemented form validation using React Hook Form and Zod schema
```

---

## 📄 Resume Bullet Points

```
• Built a full-stack weather app with React, TypeScript, and Supabase Edge Functions
• Implemented 3D Earth visualization using Three.js with realistic textures and lighting
• Integrated Google Gemini AI for personalized weather recommendations
• Designed space-themed UI with Tailwind CSS and animated WebGL effects
• Developed serverless API endpoints using Deno runtime on Supabase
• Consumed external REST APIs for geocoding and meteorological data
```

---

## 🔗 Technical Highlights

```
1. 3D Graphics: WebGL-based Earth globe with atmospheric effects, cloud layers, and orbital controls
2. AI Integration: LLM-powered advice generation with structured prompts and error handling
3. Serverless Architecture: Edge Functions for secure API key management and AI gateway access
4. Responsive Design: Mobile-first approach with adaptive layouts and touch interactions
5. Type Safety: Full TypeScript implementation with Zod schema validation
6. Modern Tooling: Vite for fast builds, ESLint for code quality, TanStack Query for caching
```

---

