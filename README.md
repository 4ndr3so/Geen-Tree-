# 🌳 Family Tree App

A fully interactive family tree web app that visualizes family relationships (parents, partners, children) with an intuitive canvas interface. Built with **React + TypeScript**, **Konva**, and deployed as a **Single Page Application (SPA)** using **Azure Static Web Apps** and **GitHub Actions** for CI/CD.

---

## 🔍 Features

- 📌 Add people dynamically: first name, last name, birth date, photo.
- 👫 Connect family members as partners or children.
- 🔁 Intelligent layout engine with **collision handling** and recursive repositioning.
- 🖱️ Canvas support: pan, zoom (mouse wheel and mobile gestures), click to select.
- 📱 Mobile-aware UI with orientation prompt.
- 🖼️ Background styling and shape selector for person nodes.
- 📤 Export family tree as an image.
- 💾 GEDCOM import/export (planned).

---

## 🧱 Tech Stack

| Layer        | Technology                                 |
|--------------|---------------------------------------------|
| Frontend     | React, TypeScript, Tailwind CSS             |
| Canvas Engine| [React-Konva](https://konvajs.org/)         |
| State Mgmt   | Redux Toolkit                               |
| CI/CD        | GitHub Actions + Azure Static Web Apps      |
| Hosting      | Azure Static Web App (SPA optimized)        |

---

## 🚀 Demo

Live: [https://tree.andr3sproject.xyz/](https://tree.andr3sproject.xyz/)

Preview:  
![Preview](https://github.com/4ndr3so/GenTree/blob/master/public/assets/img/tree.png)

---
