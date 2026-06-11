# FITX GYM - Kota's Elite Performance Center

A premium, fully functional, and device-optimized single-page website for **FITX GYM** (established in 1998). This application features a dark industrial modern aesthetic, smooth glassmorphism, responsive navigation, and an interactive WebGL background shader.

## 🚀 Live Demo & Hosting
The application can be run locally using any standard static file server.

## 🛠️ Tech Stack & Features
- **Frontend Core:** HTML5, Tailwind CSS
- **Interactive Logic:** Vanilla JavaScript (ES6+)
- **Background Animations:** WebGL Custom Fragment Shader (Pulsing energy canvas)
- **Responsive Layout:** Optimized for all viewport sizes (Mobile-First responsive sidebar & touch targets)
- **Visual Assets:** High-resolution fitness themed photography (Unsplash)
- **Interactions:**
  - Responsive mobile navigation menu.
  - Interactive "Join Now" and "Inquiry" modals with input validation.
  - Custom Billing Cycle (Monthly / Annual) toggle in pricing plans.
  - Interactive sliding Transformations Carousel.
  - Detail modals for all 3 Kota branches (Gumanpura, Kunhari, Station Area) including schedules and trainer rosters.
  - Custom glassmorphic success Toast notification system.

## 📦 Project Directory Structure
- `index.html` - The core application file containing structure, styling, logic, and WebGL shader code.
- `fitx_gym_kota_s_biggest_fitness_family/` - Original design mockup and screen layout documents.
- `ignite_elite/` - Core typography, layout, and color token configurations.
- `shader/` - Standalone shader animation template code.

## ⚙️ Running Locally
To launch a local development server:
```bash
# Using Node.js http-server
npx http-server -p 3000

# Or using Python
python -m http.server 3000
```
Open your browser and navigate to `http://localhost:3000` to view the application.
