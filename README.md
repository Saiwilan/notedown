# NoteDown 📝

> A powerful, aesthetic, and feature-rich note-taking application designed for modern thinkers.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?logo=typescript&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-2.0-FFC131?logo=tauri&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC?logo=tailwind-css&logoColor=white)

NoteDown is a versatile workspace that combines the best of linear note-taking, infinite canvas whiteboarding, and task management. whether you're brainstorming ideas, organizing your day, or writing detailed documentation, NoteDown adapts to your flow.

## ✨ Features

### 📝 Rich Text Editor
- **Slash Commands**: Type `/` to access a powerful menu for headings, lists, tables, and more.
- **Block-Based**: Move and rearrange content blocks effortlessly.
- **Markdown Support**: Full support for standard markdown shortcuts.

### 🧠 Infinite Canvas & Graph
- **Node-Based Graphs**: Create complex mind maps with nodes that connect in all 4 directions.
- **Drag & Drop**: Seamlessly drag Images and PDFs directly onto the canvas.
- **Smart Connections**: Auto-routing edges that keep your diagrams clean.

### 📌 Sticky Notes & Stickers
- **Sticky Notes**: Place quick reminders anywhere. Customize colors (Yellow, Rose, Blue, etc.) and pin them to stay visible.
- **Creative Stickers**: Add personality with a sticker layer. Spawn, scale, rotate, and place stamps like "Approved", "Postal", or emojis.
- **Layering**: Control the z-index to organize your workspace depth.

### ✅ Task Management
- **Integrated Todos**: Keep track of your tasks with a dedicated view.
- **Progress Tracking**: Visual indicators for completed vs. pending tasks.

### 🎨 Modern UI/UX
- **Responsive Design**: Fluid interfaces that work across window sizes.
- **Floating Menus**: Context-aware floating headers and navigation pills.
- **Aesthetic System**: A carefully curated [Color Palette](./colors.md) for a cohesive look.

## 🛠️ Tech Stack

- **Core**: [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Desktop Engine**: [Tauri](https://tauri.app/) (Rust)
- **Editor**: [TipTap](https://tiptap.dev/)
- **Graph Engine**: [ReactFlow](https://reactflow.dev/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Storage**: SQLite (via Tauri) / IndexedDB fallback

## 🚀 Getting Started

### Prerequisites
- **Node.js** (v16 or higher)
- **Rust** & **Cargo** (only required for Desktop/Tauri builds)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Saiwilan/notedown.git
   cd notedown
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run Web Development Server**
   ```bash
   npm run dev
   ```

4. **Run Desktop App (Tauri)**
   ```bash
   npm run tauri dev
   ```

## 📦 Building for Production

To build the web application:
```bash
npm run build
```

To build the desktop application (creates an installer):
```bash
npm run tauri build
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Made with ❤️ by Saiwilan
</p>
