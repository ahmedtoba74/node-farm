<div align="center">

  # **Node Farm 🌽**

  **A simple web application built from scratch with pure Node.js, demonstrating core concepts like routing, reading files, and template rendering without frameworks.**

  <img src="/NodeFarm.jpg" alt="Node Farm Application Interface"/>

  [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  [![Node.js Version](https://img.shields.io/badge/Node.js-v18-339933?logo=node.js&logoColor=white)](https://nodejs.org/)

  [ **Report Bug** ](https://github.com/ahmedtoba74/node-farm/issues) · [ **Request Feature** ](https://github.com/ahmedtoba74/node-farm/issues)

</div>

---

## 📖 Table of Contents

- [About The Project](#-about-the-project)
- [Key Features](#-key-features)
- [Core Concepts Demonstrated](#-core-concepts-demonstrated)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#️-project-structure)
- [Getting Started](#-getting-started)
- [Author](#-author)
- [License](#-license)

---

## 🧐 About The Project

**Node Farm** is a fundamental project from the renowned [Complete Node.js Bootcamp](https://www.udemy.com/course/nodejs-express-mongodb-bootcamp/) by Jonas Schmedtmann. Its primary goal is to provide a solid understanding of how Node.js works "under the hood" by building a web server and a simple API entirely from scratch.

Unlike modern applications that rely on frameworks like Express, this project intentionally uses only the core modules of Node.js (`http`, `fs`, `url`) to handle requests, read data, and render HTML templates. This approach highlights the foundational principles of back-end development in the Node.js environment.

---

## ✨ Key Features

-   **Simple Web Server:** A server built using the native `http` module.
-   **Static Data API:** Serves JSON data of farm products read from a local file.
-   **Dynamic HTML Rendering:** Populates HTML templates with product data before sending them to the client.
-   **Basic Routing:** A simple routing system to handle different URLs (`/overview`, `/product`, `/api`).

---

## 🧠 Core Concepts Demonstrated

This project is a practical application of the following core Node.js concepts:

-   **File System Module (`fs`):** Synchronous and asynchronous file reading to get product data and templates.
-   **HTTP Module (`http`):** Creating a server, handling requests and responses, and setting headers.
-   **URL Module (`url`):** Parsing URL parameters to determine which page or product to display.
-   **Event-Driven Architecture:** Understanding the basics of the Node.js event loop.
-   **Streams:** Efficiently reading and writing data (not explicitly used but a core concept).
-   **Module System:** Creating reusable code modules (e.g., `replaceTemplate`).

---

## 🛠️ Tech Stack

This project intentionally uses a minimal set of technologies to focus on the fundamentals.

| Category             | Technologies                                                                                                                                                                                            |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Core Runtime** | ![Node.js](https://img.shields.io/badge/Node.js-v18-339933?logo=node.js&logoColor=white)                                                                                                                  |
| **Templating** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)                                                     |
| **Development Tools**| ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?logo=visualstudiocode&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-CB3837?logo=npm&logoColor=white) |

---

## 🏛️ Project Structure

The project has a simple and organized structure to separate data, templates, and server logic.

```

node-farm/
├── dev-data/
│   └── data.json       \# JSON file containing all product data
├── templates/
│   ├── template-card.html   \# HTML template for a single product card
│   ├── template-overview.html \# HTML template for the overview page
│   └── template-product.html  \# HTML template for the product detail page
├── index.js                \# Main server file containing all logic
└── ...

````

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### **Prerequisites**

-   Node.js (v18.x or later)
-   Git

### **Installation & Setup**

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/ahmedtoba74/node-farm.git](https://github.com/ahmedtoba74/node-farm.git)
    cd node-farm
    ```
2.  **Install NPM packages:**
    (Note: This specific project might not have external dependencies, but this is a standard step.)
    ```sh
    npm install
    ```
3.  **Run the application:**
    ```sh
    node index.js
    ```
4.  Open your browser and navigate to `http://127.0.0.1:8000/`.

---

## 👨‍💻 Author

**Ahmed Toba Mahmoud**
- **LinkedIn:** [@ahmed-toba](https://www.linkedin.com/in/ahmed-toba-12345678)
- **GitHub:** [@ahmedtoba74](https://github.com/ahmedtoba74)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

````
