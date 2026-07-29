<a id="readme-top"></a>

<!-- PROJECT LOGO & HEADER -->
<br />
<div align="center">
  <a href="https://github.com/GuilhermeGraca/WebPage-Example-Portfolio">
    <img src="WebPage_Example_Portfolio/imagens/Slide 1.jpg" alt="Portfolio Logo" width="120" height="80" style="border-radius: 8px; object-fit: cover;">
  </a>

  <h3 align="center">Academic Responsive Web Portfolio</h3>

  <p align="center">
    A modern, responsive web portfolio developed as an academic project for the <strong>Programação e Comunicação Multimédia (PCM)</strong> course at <strong>ISEL (Instituto Superior de Engenharia de Lisboa)</strong>.
    <br />
    <br />
    <a href="#about-the-project"><strong>Explore the Documentation »</strong></a>
    <br />
    <br />
    <a href="https://github.com/GuilhermeGraca/WebPage-Example-Portfolio/issues">Report Bug</a>
    &middot;
    <a href="https://github.com/GuilhermeGraca/WebPage-Example-Portfolio/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#key-features">Key Features</a></li>
      </ul>
    </li>
    <li><a href="#lessons-learned">Lessons Learned</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation--running-locally">Installation & Running Locally</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

---

<!-- ABOUT THE PROJECT -->
## About The Project

<div align="center">
  <video src="preview/PreviewVidProtfolioPCM.mp4" controls="controls" width="100%" style="max-width: 800px; border-radius: 8px;"></video>
  <br />
  <a href="preview/PreviewVidProtfolioPCM.mp4"><strong>Watch Project Demo Video »</strong></a>
</div>
<br />

This repository contains an **Academic Responsive Web Portfolio** developed from scratch for the *Programação e Comunicação Multimédia (PCM)* course at **ISEL (Instituto Superior de Engenharia de Lisboa)**.

The project serves as a central showcase for our academic achievements and multidisciplinary engineering projects across Web Development, Object-Oriented Programming (Java/Python), and 3D Multimedia Modeling (Blender). It emphasizes clean **Vanilla CSS3** (geometric clip-paths, linear-gradient overlays, custom animations), **Bootstrap 5** for responsive layouts, and **Vanilla JavaScript** for DOM interactions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### Built With

* [![HTML5][HTML5-badge]][HTML5-url]
* [![CSS3][CSS3-badge]][CSS3-url]
* [![Bootstrap][Bootstrap-badge]][Bootstrap-url]
* [![JavaScript][JavaScript-badge]][JavaScript-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### Key Features

* **Responsive Sticky Navbar**: Built with Bootstrap 5 and Vanilla JS, featuring an animated hamburger toggle and scroll-aware sticky positioning (`stickyNavbar`).
* **Dynamic Hero Carousel**: Full-width slider with dark contrast linear-gradient overlays and custom diagonal bottom dividers (`clip-path: polygon`).
* **Hexagonal Skill Cards**: Custom geometric badges with hover elevation (`translateY(-10px)`) highlighting proficiency in Web, OOPL, Multimedia, and Teamwork.
* **Hover Micro-Interactions**: Interactive project cards equipped with image brightness filtering and an animated magnifying glass zoom icon (`.icon-lupa`).
* **Dark-Theme Contact Form**: Clean contact section styled with background imagery and minimalist transparent input fields.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- LESSONS LEARNED -->
## Lessons Learned

* **CSS Geometry (`clip-path`)**: Created non-rectangular shapes (diagonal section dividers and hexagonal badges) using pure CSS coordinate polygons.
* **Linear Gradient Overlays**: Applied layered pseudo-elements (`::before`) to maintain typography contrast and readability over background images.
* **Mobile-First RWD**: Mastered Bootstrap 5 grid classes (`col-lg`, `col-md`, `col-sm`) and custom media queries for responsive layouts across devices.
* **Vanilla JS DOM & Scroll Lifecycle**: Built a performant sticky navbar and smooth scroll-to-top button using native browser scroll events (`window.onscroll`).
* **UX & Micro-Animations**: Enhanced user engagement through subtle CSS transitions, hover animations, and immediate visual feedback.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- GETTING STARTED -->
## Getting Started

Follow these instructions to set up a local copy of the project and test the web portfolio on your machine.

### Prerequisites

* Any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).
* [Git](https://git-scm.com/) installed on your machine.
* Optional: A code editor like [Visual Studio Code](https://code.visualstudio.com/) with the **Live Server** extension.

### Installation & Running Locally

1. **Clone the repository**:
   ```sh
   git clone https://github.com/GuilhermeGraca/WebPage-Example-Portfolio.git
   ```
2. **Navigate to the project directory**:
   ```sh
   cd WebPage-Example-Portfolio
   ```
3. **Open the application**:
   * Open `WebPage_Example_Portfolio/html/main.html` directly in your web browser.
   * *Alternatively*, right-click `main.html` in VS Code and select **"Open with Live Server"**.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- USAGE -->
## Usage

* **Desktop & Mobile Navigation**: Scroll through the page to observe the sticky navbar lock to the top of the viewport. Resize the browser window to test the mobile hamburger menu.
* **Interactive Elements**: Hover over the hexagonal badges in **OUR SKILLS** and the project cards in **PROJETOS** to trigger custom CSS micro-animations.
* **Preview Media**: Check the `preview/` directory to view the project demonstration video (`PreviewVidProtfolioPCM.mp4`).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- CONTACT -->
## Contact

* **Guilherme Graça**
  * LinkedIn: [Guilherme Graça](https://www.linkedin.com/in/guilherme-gra%C3%A7a-b58299330/)
  * GitHub: [@GuilhermeGraca](https://github.com/GuilhermeGraca)

Project Link: [https://github.com/GuilhermeGraca/WebPage-Example-Portfolio](https://github.com/GuilhermeGraca/WebPage-Example-Portfolio)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* **ISEL – Instituto Superior de Engenharia de Lisboa** – For the academic framework and engineering education.
* **Programação e Comunicação Multimédia (PCM)** – For the project guidelines and multidisciplinary learning objectives.
* [Bootstrap 5.3](https://getbootstrap.com/) – For responsive UI components and grid architecture.
* [Google Fonts](https://fonts.google.com/) – For providing the *Oswald*, *PT Sans*, and *Kalam* font families.
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template) – For the professional Markdown documentation structure.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- MARKDOWN LINKS & IMAGES -->
[HTML5-badge]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[HTML5-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[CSS3-badge]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
[CSS3-url]: https://developer.mozilla.org/en-US/docs/Web/CSS
[Bootstrap-badge]: https://img.shields.io/badge/Bootstrap_5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JavaScript-badge]: https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E
[JavaScript-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
