# 単語カード (Japanese Flashcard App)

A lightweight, purely frontend-based Japanese vocabulary flashcard web application designed to help users learn and memorize Japanese words efficiently. It runs entirely in the browser and saves all data locally.

## ✨ Features

* **Vocabulary Management**:
  * Manually add new words with Japanese (Kanji/Kana), reading (Furigana/Romaji), and Chinese translation.
  * Organize words into custom categories/banks (e.g., General, Group 1/2/3 Verbs, Adjectives, Nouns).
  * Edit and delete existing words.
  * Search through the vocabulary list.
* **Bulk Import & Backup**:
  * Bulk import words by pasting CSV-like text (comma or semicolon separated).
  * Auto-skips duplicate words during import.
  * Experimental PDF text extraction for bulk importing.
  * Export all data to a `.json` backup file and restore it on any device.
* **Flashcard Quiz Mode**:
  * Test yourself with interactive flipping flashcards.
  * Customizable quizzes: choose the number of cards, direction (JP $\rightarrow$ CN or CN $\rightarrow$ JP), and specific word banks.
  * Option to quiz only on favorited words.
* **Favorites System**:
  * Star words to add them to your favorites for focused review.
  * Filter and view favorites by word categories.
* **Text-to-Speech (TTS) & Audio**:
  * Built-in browser speech synthesis to listen to the Japanese pronunciation of words.
* **User Interface**:
  * Clean, responsive, and modern aesthetic.
  * Dark and Light theme toggle.
  * Optimized for both desktop and mobile views.

## 🚀 Getting Started

Since this is a purely frontend application, no installation or server setup is required. 

1. Simply download the project files.
2. Double-click the `単語カード.html` file to open it in any modern web browser.
3. Start adding your words and learning!

> **Note:** All your words, banks, and settings are saved in your browser's `localStorage`. Clearing your browser data will wipe out your vocabulary unless you export a backup first!

## 📂 File Structure

* `単語カード.html` - The main HTML file containing the app's structure and CSS styling.
* `tango.js` - The JavaScript file holding all the business logic, state management, UI rendering, and interaction handling.

## 🛠️ Technology Stack

* **HTML5** & **CSS3** (CSS Variables, Flexbox, CSS Grid)
* **Vanilla JavaScript** (ES6+)
* **Browser APIs**: `localStorage` (data persistence), `SpeechSynthesis` (audio).
* **External Library**: [PDF.js](https://mozilla.github.io/pdf.js/) (for extracting text from PDFs).
