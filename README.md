# 🟢 Vue.js Learning Journey

Welcome to my Vue.js learning repository! This project tracks my progress as I learn Vue 3, covering basic integrations up to standard CLI setups and reactive components.

---

## 📂 Project Structure & Index

Here is a breakdown of the directories, topics, and key code files:

### 1. [01-Vue-Without-Node](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/01-Vue-Without-Node)
Getting started with Vue.js using the CDN approach (no Node.js or build tools required).
* **Key Files:**
  * [index.html](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/01-Vue-Without-Node/index.html) - Setup of the Vue 3 CDN script and app mounting point.
  * [app.js](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/01-Vue-Without-Node/app.js) - Simple reactive app initialization using `Vue.createApp()`.

### 2. [02-Vue-CLI](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/02-Vue-CLI)
Migrating to a standard Vue CLI environment. Understanding project structure and Single File Components (`.vue`).
* **Key Files:**
  * [main.js](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/02-Vue-CLI/src/main.js) - Entrance script mounting the root Vue app.
  * [App.vue](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/02-Vue-CLI/src/App.vue) - Root component managing child components.
  * [HelloWorld.vue](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/02-Vue-CLI/src/components/HelloWorld.vue) - Example component utilizing props (`msg`).
  * [HomeView.vue](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/02-Vue-CLI/src/components/HomeView.vue) - Home layout/view subcomponent.

### 3. [03-Interpolation](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/03-Interpolation)
Understanding text interpolation and evaluating expressions inside double curly braces `{{ }}` in Vue templates.
* **Key Files:**
  * [App.vue](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/03-Interpolation/src/App.vue) - Root component nesting the text interpolation exercises.
  * [HomeView.vue](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/03-Interpolation/src/components/HomeView.vue) - Demonstrates simple JS expression evaluations (e.g., `{{ 10+10 }}`) and scoped styling via `<style scoped>`.
  * [HelloWorld.vue](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/03-Interpolation/src/components/HelloWorld.vue) - Basic hello component inside the interpolation workspace.

---

## 🚀 How to Run the Projects

### 🌐 For `01-Vue-Without-Node` (CDN Setup)
No installation is required.
1. Simply open [index.html](file:///home/parrot/Storage/GithubRepo/Vuejs-Learning/01-Vue-Without-Node/index.html) in your browser of choice.
2. Alternatively, use a local development server (like VS Code's Live Server extension).

### 💻 For `02-Vue-CLI` & `03-Interpolation` (Node.js/Vue CLI Projects)
Ensure you have Node.js installed.
1. Navigate to the desired project folder (e.g., `02-Vue-CLI` or `03-Interpolation`).
2. Install the necessary dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run serve
   ```
4. Build for production:
   ```bash
   npm run build
   ```
5. Run the linter:
   ```bash
   npm run lint
   ```

---

## 🧠 Concepts Explored
* **Vue CDN Integration**: Injecting Vue using external global packages.
* **Single File Components (SFC)**: Bundling HTML template, JS behavior, and CSS styles in a single `.vue` file.
* **Props System**: Passing dynamic data from parent to child components.
* **Text Interpolation**: Using Mustache syntax `{{ }}` to bind data and evaluate lightweight JavaScript statements.
* **Scoped Styling**: Preventing CSS leakage by scoping template tags using `<style scoped>`.
