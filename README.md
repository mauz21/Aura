# Aura: Quiet Living

*Organic technology designed to disappear into your life.*

Aura is a conceptual e-commerce experience for a premium, minimalist electronics brand. Founded on the principle that technology should feel as natural as the world around it, Aura products prioritize materiality, silence, and human-centric design.

## 🌿 Brand Philosophy
"Technology should not feel like technology. It should feel like a stone smoothed by a river, or a page turned in a book."

In an age of infinite distraction, Aura designs objects that respect your silence. We use materials that age gracefully—sandstone, untreated aluminum, and organic cotton—creating a tactile bridge between the digital world and your physical home.

## ✨ Key Features
- **Curated Collection**: A high-end showcase of audio, wearable, mobile, and home products.
- **AI Concierge**: A sophisticated virtual assistant powered by Google Gemini, trained on Aura's brand voice and product catalog.
- **The Journal**: An editorial space exploring the psychology of texture, minimalism, and intentional living.
- **Adaptive UI**: A warm, minimalist interface that responds to user interaction with serene animations and a mobile-first approach.
- **Integrated Cart & Checkout**: A streamlined commerce flow from discovery to simulated purchase.

## 🛠 Tech Stack
- **Framework**: React 19
- **AI Engine**: Google Gemini API (@google/genai)
- **Styling**: Tailwind CSS
- **Typography**: 
  - *Serif*: Playfair Display (for elegance and authority)
  - *Sans*: Inter (for clarity and modern utility)
- **Icons**: Heroicons (SVG)

## 🚀 Getting Started

### Prerequisites
- A Google Gemini API Key.

### Environment Setup
The application expects an API key to be provided via environment variables. Ensure `process.env.API_KEY` is configured in your deployment or local environment.

### Installation
Since this is a standard React ESM project:
1. Ensure your local server supports ES6 modules.
2. The `index.html` automatically imports `index.tsx`.
3. Tailwind CSS is loaded via CDN for rapid, configuration-free styling.

## 📁 Project Structure
- `components/`: Modular UI elements (Navbar, Hero, ProductGrid, etc.).
- `services/`: Logic for AI integration and external APIs.
- `constants.ts`: The "Source of Truth" for product data and editorial content.
- `types.ts`: TypeScript interfaces for robust data handling.
- `App.tsx`: Central state management and view orchestration.

---
Created with care for the quiet mind.
