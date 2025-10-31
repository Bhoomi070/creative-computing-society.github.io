# Creative Computing Society Hacktoberfest Website

This repository hosts the Hacktoberfest contribution website for the **Creative Computing Society** (CCS), built upon the popular **Start Bootstrap - Creative** theme. This project is intended to be a **beginner-friendly** starting point for anyone looking to make their first open-source contribution!

---

## 🌟 Hacktoberfest Contribution Guide

We warmly welcome contributions from everyone! If you're new to open source, this is the perfect place to start.

### Quick Start: Fix a Typo (Easiest PR)

1.  **Fork** this repository.
2.  Navigate to a file (like `index.html` or this `README.md`) and click the **pencil icon** to edit it directly on GitHub.
3.  Fix a typo or improve the wording of a sentence.
4.  Commit your change with a clear message (e.g., `Fix: Clarified instructions in README`).
5.  Open a **Pull Request (PR)** from your fork back to this repository.

### For More Detailed Guidance:

For a comprehensive walkthrough on the Git/GitHub workflow (Fork $\rightarrow$ Clone $\rightarrow$ Edit $\rightarrow$ PR), please visit our dedicated guide:

👉 [CCS Guide to Contributing in Hacktoberfest](https://github.com/creative-computing-society/Guide_to_contribute_in_Hacktoberfest)

---

## 🛠️ Local Development Setup

If you wish to run the website locally and test more complex changes (like CSS or JavaScript updates), follow these steps:

This project uses **[Gulp](http://gulpjs.com/)** to compile SASS/SCSS files and **[BrowserSync](https://browsersync.io/)** for live-reloading.

### Prerequisites

You must have **Node.js** and **npm** (Node Package Manager) installed on your system.

### Installation & Run

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/creative-computing-society/creative-computing-society.github.io.git](https://github.com/creative-computing-society/creative-computing-society.github.io.git)
    ```
2.  **Install Dependencies:** Navigate into the directory and install the necessary packages.
    ```bash
    cd creative-computing-society.github.io
    npm install
    ```
3.  **Start Local Server:** Run the development command.
    ```bash
    gulp dev
    ```
    This command will open the site in your browser at `http://localhost:3000` (or similar) and watch your files for changes.

---

## 📚 Project Technology

This theme is based on the following key libraries, as listed in the `package.json`:

* **Frontend Framework:** Bootstrap (v4.1.3)
* **Icons:** Font Awesome (v5.3.1)
* **Scrolling Effects:** ScrollReveal, jQuery Easing
* **Image Gallery:** Magnific Popup

### License

This project is licensed under the **MIT License**.
