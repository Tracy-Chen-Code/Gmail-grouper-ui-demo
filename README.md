# ⚡ Smart Gmail Grouper – UI Demo

This project is a **front-end UI demo** that showcases the interaction design of the **Smart Gmail Grouper Chrome Extension**.

The demo simulates the Gmail inbox interface and reproduces the UI behavior that appears after the extension is injected into Gmail.

It includes features such as:

* Floating AI action button
* Smart grouping sidebar
* AI grouping suggestions
* Quick email actions (Archive, Mark as Read, Undo)

This project focuses **only on the front-end interaction layer** and does **not require Gmail API access or backend services**.

---

# 🌐 Live Demo

If deployed on GitHub Pages:

```
Insert your demo link here
```

---

# ✨ Features

### 📧 Mock Gmail Interface

Uses pure **HTML + CSS** to simulate:

* Gmail left navigation bar
* Email list interface

This provides a realistic environment to demonstrate the extension UI.

---

### 📌 Floating Action Button

A fixed **“⚡ Group Inbox” button** appears in the bottom-right corner.

When clicked, it **opens the AI grouping sidebar**.

---

### 🤖 AI Analysis Simulation

Simulates a backend LLM analysis process.

The UI displays:

* AI grouping categories

  * Ads
  * Subscriptions
  * Important
* AI reasoning explanation

This is **only a simulated loading and result display**, not a real API call.

---

### ⚡ Quick Actions

Supports interactive email actions:

* Archive All
* Mark as Read

Includes **smooth card removal animations** for better UX.

---

### ↩ Undo Function

After performing an action, a **toast notification** appears at the bottom of the screen.

Users can **restore the removed email with one click**.

---

### 📦 Zero Dependencies

The entire project is written using:

* Vanilla JavaScript
* HTML
* CSS

No frameworks or build tools are required.

No React, Vue, Webpack, or Vite.

---

# 🚀 How to Run

This is a **pure static front-end project**.

### Step 1

Download or clone the repository.

### Step 2

Open the file:

```
index.html
```

### Step 3

Click the button:

```
⚡ Group Inbox
```

at the bottom-right corner of the page.

The AI grouping sidebar will appear.

---

# 📁 Project Structure

```
gmail-grouper-ui-demo
│
├── index.html      # Main UI demo (HTML + CSS + JS)
└── README.md       # Project documentation
```

The project uses a **single-file architecture** for simplicity.

`index.html` contains:

* HTML structure
* CSS styling
* JavaScript interaction logic

---

# 🛠 Future Development Guide

If you want to convert this demo into a **real Chrome Extension**, you can:

### 1️⃣ Extract CSS

Move styles from the `<style>` tag into:

```
content.css
```

---

### 2️⃣ Extract JavaScript

Move scripts from the `<script>` tag into:

```
content.js
```

---

### 3️⃣ Connect Gmail API

Replace the mocked data with real Gmail API calls, for example:

```
gapi.client.gmail.users.messages.list
```

This allows the extension to **analyze real inbox emails**.

---

# 📄 License

MIT License
