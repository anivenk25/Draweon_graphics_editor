# Draweon Graphics Editor 🖌️

Draweon is a powerful graphics editor built for intuitive drawing, AI-powered assistance, and seamless user experience. From simple shapes to complex layouts, Draweon lets you design with precision, efficiency, and smart automation.

---

## 🛠️ Getting Started

### 📦 Prerequisites
Before running Draweon, make sure you have the following installed:

- **Node.js & npm**
- **Git** (optional, for cloning the repository)

### 🚀 Run Instructions

```bash
# 1. Clone the repository
git clone https://github.com/anivenk25/Draweon_graphics_editor.git
cd project

# 2. Install dependencies
npm install

# 3. Set up environment variables for AI features
# Create a `.env` file in the root project folder and add the following line:
VITE_OPENAI_KEY=your_openai_api_key_here

# 4. Start the development server
npm run dev

# The app will be available at http://localhost:5173 (or another port shown in terminal)
```

### 🤖 Enabling AI Features
To enable AI-powered suggestions and enhancements:

1. Create a `.env` file inside the project folder.
2. Add your OpenAI API key:
   ```
   VITE_OPENAI_KEY=your_openai_api_key_here
   ```
3. Restart the development server if it's already running.

> 🔐 Keep your API key secure and **do not** commit your `.env` file to version control.

---

## 🚀 Features

### 🎨 Basic Drawing Tools
- Create geometric shapes: **circles, ellipses, rectangles, lines, polygons**
- Add and edit **text** associated with any shape

### 🖱️ Object Selection & Modification
- Click to select objects, with **visual highlighting**
- Modify object attributes: shape, size, position, color, fill, line width/style
- Edit content of text objects

### ✂️ Object Management
- Move, **copy**, and **delete** selected objects
- **Group** multiple objects (including nested groups) to manipulate as one unit
- Store objects in up to **10 clipboards** for quick reuse

### 💾 File Operations
- **Save** drawings to disk with custom filenames
- **Load** previously saved drawing files
- Import **bitmap images** and place them on the canvas

### 🔍 Zoom & Pan
- Zoom into a selected area
- "Fit to screen" to auto-adjust canvas view
- Pan the canvas in any direction with ease

---

## 🤖 AI-Powered Features

### 🧠 Auto Layout Suggestions
- Get smart layout ideas to enhance design alignment and balance
- Accept, tweak, or reject suggestions freely

### 🌈 Style Recommendations
- Discover AI-suggested **color palettes**, **font pairings**, and design styles
- Preview and apply them instantly

### 🖼️ AI-based Image Enhancement
- Automatically improve **brightness, contrast, sharpness**
- Toggle enhancements on/off

### 🔷 AI-generated Shapes
- Generate unique shapes and design elements from user prompts
- Customize, scale, and position them on the canvas

### 📡 AI Model Integration
- Connects with external AI models (DS3) to fetch smart suggestions
- Periodic model updates ensure high accuracy and creativity

### 🧩 Full User Control
- Full manual override of AI suggestions
- Support for **undo/redo** of AI-assisted actions

---
