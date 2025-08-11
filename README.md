<!-- Banner / Logo -->
<p align="center">
  <img src="icons/images/icon.png" alt="PostCat Logo" width="150"/>
</p>

<h1 align="center">🐱 PostCat – API Client for VS Code</h1>
<p align="center">
  A lightweight API testing and management extension for <strong>Visual Studio Code</strong>.<br>
  Send requests, manage collections, and view history — all without leaving your editor.
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=dennismutuku.postcat">
    <img src="https://img.shields.io/visual-studio-marketplace/v/dennismutuku.postcat?label=VS%20Code%20Marketplace&color=purple&logo=visual-studio-code" alt="Marketplace Version">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=dennismutuku.postcat">
    <img src="https://img.shields.io/visual-studio-marketplace/d/dennismutuku.postcat?color=purple&label=Downloads&logo=visual-studio-code" alt="Downloads">
  </a>
  <a href="https://github.com/dennismutuku2005/postcat/stargazers">
    <img src="https://img.shields.io/github/stars/dennismutuku2005/postcat?color=yellow&label=Stars&logo=github" alt="GitHub Stars">
  </a>
  <a href="https://github.com/dennismutuku2005/postcat/issues">
    <img src="https://img.shields.io/github/issues/dennismutuku2005/postcat?color=orange&label=Issues&logo=github" alt="GitHub Issues">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/github/license/dennismutuku2005/postcat?color=blue&label=License" alt="License">
  </a>
</p>

---

## 🚀 Features
- **Send HTTP requests** (GET, POST, PUT, PATCH, DELETE, etc.) directly from VS Code
- **Custom headers & request body** support
- **Request history** with execution time and size
- **Collections & environments** to organize requests
- **Sidebar view** for quick access to saved requests
- **Integrated dark/light theme support**

---

## 📦 Installation
1. Open **VS Code**
2. Go to the **Extensions** view (`Ctrl+Shift+X` / `Cmd+Shift+X` on Mac)
3. Search for **PostCat**
4. Click **Install** and reload VS Code

Or install directly from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=dennismutuku.postcat).

---

## 🛠 Usage

### 1. Open PostCat
- Open the command palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
- Search for **"PostCat: Open"**
- The PostCat panel will appear

### 2. Send a Request
1. Choose **method** (GET, POST, PUT, DELETE, etc.)
2. Enter the **request URL**
3. Add headers and body if needed
4. Click **Send**
5. View the JSON or text response

### 3. Manage Collections
- Save frequently used requests into **collections**
- Organize requests by **environment** (dev, staging, prod)

---

## 🖥 Interface

**Main Panel**
- Method & URL input
- Headers & Body editors
- Send button
- Response viewer with status, time, and size

**Sidebar**
- Collections list
- Request history

---

## ⚡ Commands

| Command                | Description                                  |
|------------------------|----------------------------------------------|
| `PostCat: Open`        | Opens the main PostCat request panel         |
| `PostCat: Show Sidebar`| Opens the PostCat sidebar with collections   |

---

## 📂 Development Setup

```bash
# Clone the repository
git clone https://github.com/dennismutuku2005/postcat.git

# Open in VS Code
cd postcat
code .

# Install dependencies
npm install

# Run the extension in debug mode
npm run watch
