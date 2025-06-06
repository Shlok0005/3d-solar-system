# 🚀 3D Solar System Simulation

A dazzling and interactive 3D simulation of our solar system, featuring colossal planets, bright, distinct orbits, and a background filled with countless stars! Explore the dynamic movement of the planets and customize their orbital speeds.

## ✨ Features

* **Colossal Planets:** Planets are rendered at a significantly increased scale for an impactful and easy-to-observe view.
* **Dominant Sun:** The Sun is depicted as the largest celestial body, radiating intense light and energy.
* **Vibrant, Visible Orbits:** Each planet's orbital path is clearly rendered, making their trajectories easy to follow.
* **Densely Populated Starfield:** The background is filled with a vast number of bright stars, creating an immersive cosmic environment.
* **Interactive Camera Controls:** Orbit the scene, zoom in and out, and pan around to get different perspectives of the solar system.
* **Planet Interaction:** Click on any planet to zoom to it and display its key information (radius and distance from the Sun).
* **Dynamic Speed Adjustment:** Control the orbital speed of each individual planet using dedicated sliders in the control panel.
* **Pause/Resume Simulation:** Pause and resume the motion of the planets at any time.
* **Reset Options:** Easily reset all planet speeds or reset the camera to its initial wide view.
* **Toggle Orbits Visibility:** Show or hide the orbital paths with a click of a button.
* **Dark/Light Mode:** Switch between dark (space-themed) and light backgrounds for user preference.

## 🛠️ Technologies Used

* **HTML5:** For the core structure of the web page.
* **CSS3 (Tailwind CSS):** For responsive and modern styling of the interface.
* **JavaScript:** For all interactive logic and simulation control.
* **Three.js (r128):** A powerful 3D JavaScript library used for rendering the planets, Sun, orbits, and stars.
* **OrbitControls (Three.js):** Provides intuitive camera navigation and interaction.
* **GSAP (GreenSock Animation Platform):** Used for smooth, high-performance animations, especially for camera transitions.

## 🚀 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/solar-system-simulation.git](https://github.com/your-username/solar-system-simulation.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd solar-system-simulation
    ```
3.  **Open the `index.html` file:**
    Simply open the `index.html` file in your preferred web browser (e.g., Chrome, Firefox, Edge).

## 🌐 Deployment (GitHub Pages)

This project is designed to be easily deployable using GitHub Pages.
1.  Push your `index.html` file (and any other assets if you add them) to the `main` (or `master`) branch of your GitHub repository.
2.  Go to your repository's **Settings** -> **Pages**.
3.  Under "Build and deployment", select **Deploy from a branch** and choose your `main` (or `master`) branch.
4.  Your site will be live at `https://your-username.github.io/your-repository-name/`.

## 🎮 Controls

* **Rotate Camera:** Click and drag anywhere on the canvas.
* **Zoom In/Out:** Scroll your mouse wheel or use pinch gestures on touch devices.
* **Pan Camera:** Right-click and drag (or two-finger drag on touchpads).
* **Click on a Planet/Sun:** Zooms the camera to that celestial body and displays its information.
* **Sliders:** Adjust the orbital speed of individual planets.
* **Buttons:**
    * `Pause/Resume`: Toggles the animation state.
    * `Reset Speeds`: Resets all planet orbital speeds to their defaults.
    * `Reset Camera`: Returns the camera to its initial wide view.
    * `Hide/Show Orbits`: Toggles the visibility of the orbital paths.
    * `Light/Dark Mode`: Switches the overall theme of the application.

## 🔮 Future Enhancements (Ideas)

* Add more celestial bodies (moons, asteroids, comets).
* Implement realistic textures for planets.
* Include data visualizations for orbital periods or relative sizes.
* Allow customization of planet sizes or orbital distances.
* Add sound effects or background music.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
