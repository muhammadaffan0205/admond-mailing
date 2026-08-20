<div align="center">

# 📬 ADMOND MAILING

### A Modern Gmail-Inspired Webmail Experience

**A fully interactive email simulation built entirely with Vanilla HTML, CSS & JavaScript.**

<br>

<a href="https://muhammadaffan0205.github.io/admond-mailing/">
<img src="https://img.shields.io/badge/🚀_LIVE_DEMO-2563EB?style=for-the-badge&logoColor=white" alt="Live Demo"/>
</a>
&nbsp;
<a href="https://github.com/muhammadaffan0205/admond-mailing">
<img src="https://img.shields.io/badge/⭐_GITHUB_REPOSITORY-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=2563EB&center=true&vCenter=true&width=650&lines=Gmail-Inspired+Webmail+Client;Pure+Vanilla+Web+Technologies;Zero+Dependencies;Single+HTML+Architecture;Interactive+Browser-Based+Email+Experience" alt="Typing SVG"/>

<br><br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Design-10B981?style=flat-square)
![No Dependencies](https://img.shields.io/badge/Dependencies-0-8B5CF6?style=flat-square)
![MIT](https://img.shields.io/badge/License-MIT-111827?style=flat-square)

</div>

---

<div align="center">

> ### ✉️ **Email, Reimagined in One File.**
>
> A polished front-end email simulation designed to demonstrate how far
> **HTML + CSS + JavaScript** can go without frameworks, packages, or build tools.

</div>

---

# 🧭 Table of Contents

* [✨ Overview](#-overview)
* [🎯 Project Vision](#-project-vision)
* [⚡ Core Features](#-core-features)
* [🎨 Interface & Experience](#-interface--experience)
* [🧠 Application Architecture](#-application-architecture)
* [🔄 Application Flow](#-application-flow)
* [🛠️ Technology Stack](#️-technology-stack)
* [📦 Project Structure](#-project-structure)
* [💾 Data Persistence](#-data-persistence)
* [📱 Responsive Design](#-responsive-design)
* [🚀 Getting Started](#-getting-started)
* [🌐 Deployment](#-deployment)
* [🗺️ Roadmap](#️-roadmap)
* [💡 Why This Project?](#-why-this-project)
* [👨‍💻 Developer](#-developer)
* [📄 License](#-license)

---

# ✨ Overview

**Admond Mailing** is a browser-based email client simulation inspired by the usability patterns of modern webmail platforms.

The project focuses on creating a convincing email experience using nothing more than:

```text
HTML
+
CSS
+
Vanilla JavaScript
```

No React.

No Vue.

No Angular.

No Bootstrap.

No npm.

No backend.

No build process.

Just a carefully structured **single-page web application**.

### 🔥 The Result

A lightweight interface capable of simulating common email interactions such as:

* 📥 Inbox management
* ⭐ Email starring
* 📖 Read / unread states
* 🗑️ Email deletion
* 🔎 Email organization
* ↕️ Dynamic sorting
* 🌙 Dark mode
* 👤 Sender avatars
* ☑️ Multi-selection
* 💾 Browser persistence
* ✉️ Message composition
* 📊 Inbox statistics

---

# 🎯 Project Vision

<div align="center">

### **"Build a realistic product experience without relying on a framework."**

</div>

Admond Mailing was created as an exploration of how much functionality and polish can be achieved using fundamental web technologies.

The project demonstrates that a frontend application does not necessarily need a large dependency ecosystem to provide:

**Structure → Interaction → State → Persistence → Visual Polish**

---

# ⚡ Core Features

<table>
<tr>

<td width="50%" valign="top">

### 📥 Inbox Management

* Organized email listing
* Sender identification
* Subject previews
* Date/time indicators
* Read/unread states
* Email count indicators

</td>

<td width="50%" valign="top">

### ⭐ Smart Email Actions

* Star messages
* Remove messages
* Mark as read
* Mark as unread
* Select multiple messages
* Batch operations

</td>

</tr>

<tr>

<td width="50%" valign="top">

### ↕️ Dynamic Sorting

Emails can be reorganized instantly using:

```text
Newest
Oldest
A → Z
Z → A
```

</td>

<td width="50%" valign="top">

### 🌙 Dark Mode

A dedicated interface theme designed for:

* Low-light environments
* Reduced visual fatigue
* Modern appearance
* Persistent user preference

</td>

</tr>

<tr>

<td width="50%" valign="top">

### 👤 Dynamic Avatars

Sender initials are automatically transformed into compact visual identity badges.

Examples:

```text
MT
AK
PU
GC
```

</td>

<td width="50%" valign="top">

### 💾 Local Persistence

Browser `localStorage` keeps important interface state available after refreshes.

Persisted information can include:

* Read state
* Starred messages
* User-created messages
* Interface preferences

</td>

</tr>

</table>

---

# 🎨 Interface & Experience

Admond Mailing is designed around a **clean productivity-first interface**.

### 🧩 Visual System

```text
┌───────────────────────────────────────────────────────────┐
│                     ADMOND MAILING                        │
├───────────────┬───────────────────────────────────────────┤
│               │                                           │
│   SIDEBAR     │              EMAIL WORKSPACE              │
│               │                                           │
│  📥 Inbox     │  ┌─────────────────────────────────────┐  │
│  ⭐ Starred   │  │ Search / Sorting / Actions          │  │
│  📤 Sent      │  └─────────────────────────────────────┘  │
│  🗑 Trash     │                                           │
│               │  ┌─────────────────────────────────────┐  │
│               │  │ 👤 Sender                           │  │
│               │  │ Subject                             │  │
│               │  │ Message preview              ⭐     │  │
│               │  ├─────────────────────────────────────┤  │
│               │  │ 👤 Sender                           │  │
│               │  │ Subject                             │  │
│               │  │ Message preview              ⭐     │  │
│               │  └─────────────────────────────────────┘  │
│               │                                           │
└───────────────┴───────────────────────────────────────────┘
```

### ✦ Design Principles

| Principle       | Implementation                      |
| --------------- | ----------------------------------- |
| 🎯 Clarity      | Clean visual hierarchy              |
| ⚡ Speed         | Minimal JavaScript overhead         |
| 📱 Adaptability | Responsive layouts                  |
| 🧠 Usability    | Familiar email interaction patterns |
| 🎨 Consistency  | Reusable UI patterns                |
| ♿ Accessibility | Semantic HTML and readable contrast |

---

# 🧠 Application Architecture

Although the project is contained inside a single HTML document, the internal implementation follows a logical separation of concerns.

```text
                    ┌─────────────────────┐
                    │     USER INPUT      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │     UI EVENTS       │
                    │ Click / Select /    │
                    │ Sort / Compose      │
                    └──────────┬──────────┘
                               │
                               ▼
                 ┌──────────────────────────┐
                 │     JAVASCRIPT LOGIC      │
                 │                          │
                 │ State Management         │
                 │ Email Operations         │
                 │ Sorting Engine           │
                 │ Theme Management         │
                 │ Validation               │
                 └────────────┬─────────────┘
                              │
                 ┌────────────┴────────────┐
                 ▼                         ▼
       ┌──────────────────┐      ┌──────────────────┐
       │   DOM UPDATES    │      │   LOCAL STORAGE  │
       │                  │      │                  │
       │ Render UI        │      │ Persist State    │
       │ Update Counters  │      │ Restore Data     │
       └──────────────────┘      └──────────────────┘
```

### 🏗️ Architecture Philosophy

The application follows an:

> **Architecture-in-a-File**

approach.

Instead of spreading a small application across dozens of files, the project keeps its core implementation together while still maintaining logical separation between:

```text
Presentation
     ↓
Interaction
     ↓
Application State
     ↓
Persistence
```

---

# 🔄 Application Flow

```text
             ┌───────────────┐
             │    Browser    │
             └───────┬───────┘
                     │
                     ▼
             ┌───────────────┐
             │ Load HTML     │
             └───────┬───────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Initialize App      │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Restore local state │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Render Email List   │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ User Interaction    │
          └──────────┬──────────┘
                     │
          ┌──────────┼──────────┐
          ▼          ▼          ▼
       Compose     Sort       Actions
          │          │          │
          └──────────┼──────────┘
                     ▼
          ┌─────────────────────┐
          │ Update Application  │
          │ State               │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Save to Storage     │
          └─────────────────────┘
```

---

# 🛠️ Technology Stack

<div align="center">

| Technology              | Purpose                             |
| ----------------------- | ----------------------------------- |
| 🧱 **HTML5**            | Application structure               |
| 🎨 **CSS3**             | Styling, layout & responsive design |
| ⚡ **JavaScript**        | Application logic & interactions    |
| 💾 **LocalStorage API** | Client-side persistence             |
| 🌐 **GitHub Pages**     | Deployment                          |

</div>

### 🚫 No Frameworks

```text
React       ❌
Vue         ❌
Angular     ❌
Bootstrap   ❌
Tailwind    ❌
jQuery      ❌
Node.js     ❌
Webpack     ❌
Vite        ❌
```

### ✅ What It Uses

```text
HTML5       ✔
CSS3        ✔
JavaScript  ✔
Browser APIs ✔
```

---

# 📦 Project Structure

The project intentionally keeps the implementation lightweight.

```text
admond-mailing/
│
├── 📄 index.html
│
├── 📄 LICENSE
│
└── 📄 README.md
```

### One File. Complete Experience.

The main HTML document contains the complete front-end experience:

```text
index.html
│
├── HTML Structure
│
├── CSS Styles
│   ├── Layout
│   ├── Components
│   ├── Responsive Rules
│   ├── Theme System
│   └── Animations
│
└── JavaScript
    ├── Email State
    ├── Event Handlers
    ├── Sorting
    ├── Selection
    ├── Actions
    ├── Theme Switching
    └── LocalStorage
```

This makes the project extremely easy to:

* Clone
* Inspect
* Modify
* Learn from
* Deploy

---

# 💾 Data Persistence

Admond Mailing uses the browser's built-in:

```javascript
localStorage
```

to simulate lightweight client-side persistence.

### 🔄 Persistence Lifecycle

```text
User Action
     ↓
Application State
     ↓
Serialize Data
     ↓
localStorage
     ↓
Browser Refresh
     ↓
Read Stored Data
     ↓
Restore Application State
```

This allows the interface to feel significantly more like a real application rather than a static HTML mockup.

---

# 📱 Responsive Design

The interface is designed to adapt across different viewport sizes.

### 🖥️ Desktop

```text
Sidebar + Full Email Workspace
```

### 💻 Laptop

```text
Compact Sidebar + Optimized Workspace
```

### 📱 Mobile

```text
Adaptive Navigation
        +
Stacked Email Content
        +
Touch-Friendly Controls
```

The goal is to maintain usability rather than simply shrinking the desktop interface.

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/muhammadaffan0205/admond-mailing.git
```

## 2️⃣ Enter the Project

```bash
cd admond-mailing
```

## 3️⃣ Launch

Because the project requires no build process, simply open:

```text
index.html
```

in your browser.

That's it.

### ⚡ No Installation Required

```text
npm install       ❌
npm run build     ❌
npm start         ❌
package.json      ❌
dependencies      ❌
```

---

# 🌐 Deployment

Admond Mailing is compatible with static hosting platforms.

### Recommended

**GitHub Pages**

```text
Repository
    ↓
GitHub Pages
    ↓
Static Hosting
    ↓
Public Web Application
```

### 🚀 Live Application

<div align="center">

<a href="https://muhammadaffan0205.github.io/admond-mailing/">

<img src="https://img.shields.io/badge/OPEN_ADMOND_MAILING-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Open Admond Mailing"/>

</a>

</div>

---

# 🗺️ Roadmap

Admond Mailing can evolve from a front-end simulation into a complete webmail platform.

### ✅ Current

* [x] Email inbox
* [x] Email selection
* [x] Star functionality
* [x] Read/unread states
* [x] Delete actions
* [x] Sorting
* [x] Dark mode
* [x] LocalStorage persistence
* [x] Responsive interface
* [x] Static deployment

### 🔮 Future

* [ ] Real authentication
* [ ] Backend API
* [ ] Database integration
* [ ] Real email delivery
* [ ] Attachment support
* [ ] Search engine
* [ ] Advanced filtering
* [ ] Labels & categories
* [ ] Threaded conversations
* [ ] User profiles
* [ ] Push notifications
* [ ] Cloud synchronization

---

# 💡 Why This Project?

Admond Mailing is more than an email UI.

It demonstrates several important frontend engineering concepts:

### 🧩 Component Thinking

Breaking a large interface into reusable visual and functional patterns.

### 🧠 State Management

Managing email states without relying on a frontend framework.

### ⚡ DOM Manipulation

Creating dynamic UI updates using native JavaScript.

### 💾 Client-Side Storage

Using browser APIs to preserve application state.

### 🎨 UI Engineering

Building a polished interface from fundamental CSS techniques.

### 📱 Responsive Development

Designing interfaces that remain usable across different screen sizes.

---

# 📊 Engineering Snapshot

<div align="center">

|    Category    |  Implementation |
| :------------: | :-------------: |
|    Frontend    |   Vanilla Web   |
|  Architecture  | Single-File SPA |
|  Dependencies  |      **0**      |
|   Build Tools  |      **0**      |
|     Backend    |       None      |
|   Persistence  |   LocalStorage  |
|   Deployment   |   GitHub Pages  |
|   Responsive   |       Yes       |
|    Dark Mode   |       Yes       |
| Interactive UI |       Yes       |

</div>

---

# 🧪 What This Project Demonstrates

```text
                  ADMOND MAILING
                        │
          ┌─────────────┼─────────────┐
          │             │             │
          ▼             ▼             ▼
       FRONTEND      JAVASCRIPT      UX/UI
          │             │             │
      HTML5          State          Layout
      CSS3           Events         Styling
      Responsive     DOM            Themes
                     Storage        Accessibility
          │             │             │
          └─────────────┼─────────────┘
                        ▼
               COMPLETE WEB EXPERIENCE
```

---

# 🌟 Project Philosophy

<div align="center">

### **Simple Stack. Serious Execution.**

A project doesn't need hundreds of dependencies to demonstrate engineering ability.

Sometimes the strongest demonstration is taking the fundamentals and pushing them as far as they can go.

<br>

**HTML → Structure**

**CSS → Experience**

**JavaScript → Intelligence**

**Browser APIs → Persistence**

</div>

---

# 👨‍💻 Developer

<div align="center">

### Muhammad Affan

**Software Engineering Student & Developer**

Interested in:

```text
Web Development
Software Engineering
Algorithms
UI/UX
Problem Solving
Interactive Applications
```

<br>

<a href="https://github.com/muhammadaffan0205">
<img src="https://img.shields.io/badge/GitHub-Muhammad_Affan-181717?style=for-the-badge&logo=github" alt="GitHub"/>
</a>

</div>

---

# ⭐ Support

If you find **Admond Mailing** interesting or useful:

⭐ Star the repository
🍴 Fork the project
🧑‍💻 Experiment with the code
💡 Build your own version
📢 Share it with other developers

Every star and contribution is appreciated.

---

# 📄 License

This project is distributed under the **MIT License**.

You are free to:

* Use it
* Modify it
* Study it
* Distribute it
* Build upon it

See the `LICENSE` file for complete details.

---

<div align="center">

<br>

## 📬 ADMOND MAILING

### Built with curiosity.

### Designed with intention.

### Powered by the web.

<br>

<a href="https://muhammadaffan0205.github.io/admond-mailing/">
<img src="https://img.shields.io/badge/🚀_EXPLORE_LIVE_DEMO-2563EB?style=for-the-badge" alt="Live Demo"/>
</a>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=2563EB&height=120&section=footer"/>

</div>
