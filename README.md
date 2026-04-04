# 単語カード (Japanese Flashcard App)

A lightweight, purely client-side Japanese vocabulary flashcard web application. It requires no backend services or database setup—all data is securely saved directly in your browser's Local Storage.

## ✨ Core Features

*   **📚 Vocabulary Library**: Manually add Japanese vocabulary, reading (Kana), and Chinese translations.
*   **📥 Batch Import**: Bulk import vocabulary by uploading text (comma/semicolon separated) or directly extracting text from PDF files.
*   **🗂 Categorization & Search**: Tag words into different categories (e.g., Verb Group 1, Adjectives, etc.), and quickly search or filter your vocabulary library.
*   **🎲 Flashcard Quiz Mode**: A randomized quiz mode fetching from your library with a 3D flip card animation. Supports "Japanese → Chinese" and "Chinese → Japanese" modes, along with native Text-To-Speech (TTS) reading.
*   **⭐ Favorites**: Add difficult words to your "Favorites" list along the way for focused review and targeted quizzes later.
*   **💾 Backup & Restore**: Easily export your entire vocabulary library and progress to a local JSON file, and import it across different devices to sync your learning progress.
*   **🌙 Dark/Light Theme**: Built-in beautiful dark and light themes that can be toggled seamlessly for a great UI experience.

## 🚀 Quick Start

Since this is a fully static and standalone web application, running it is incredibly simple:

1. Clone or download this project folder to your local machine.
2. Double-click to open `単語カード.html` (Modern browsers like Google Chrome, Safari, or Edge are recommended).
3. Start building your own custom Japanese vocabulary library!

## 📁 Project Structure

*   `単語カード.html` - The main application entry point, containing UI structure and inline CSS styles.
*   `tango.js` - The core Javascript file handling data storage, business logic, UI rendering, and flashcard operations.
*   Other folders and files (like PDFs and DOCs) are personal Japanese study materials and are not required to run the application itself.

## 🛠 Tech Stack

*   HTML5 / CSS3 (Utilizing CSS Variables and dynamic keyframe animations)
*   Vanilla JavaScript
*   Web Speech API (For native Japanese pronunciation)
*   PDF.js (Used exclusively for parsing text during PDF imports)
