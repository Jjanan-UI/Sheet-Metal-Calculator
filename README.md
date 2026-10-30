# Sheet Metal Bend Calculator

<img width="1122" height="1121" alt="Single Bend" src="https://github.com/user-attachments/assets/634028ba-98c2-4685-abbb-11788e004639" />


## 📌 Project Overview
This repository contains a lightweight, fully client-side web application designed to calculate bend allowance (BA), bend deduction (BD), and flat pattern lengths for sheet metal fabrication. Built for engineers, machinists, and hobbyists, the tool provides real-time visual feedback through interactive SVG diagrams, eliminating the need for manual formula calculations or expensive CAD software for simple flat pattern estimations.

## 📊 Key Specifications
| Parameter | Specification |
| :--- | :--- |
| **App Type** | Client-side Web Application |
| **Tech Stack** | HTML5, CSS, and JavaScript |
| **Supported Units** | Metric (mm) & Imperial (in) |
| **Calculations** | Bend Allowance (BA), Bend Deduction (BD), Setback, Flat Length |
| **Material Presets** | Mild Steel, Stainless Steel 304, Aluminum 5052, Copper, Brass |
| **UI Features** | Responsive Design, Dark/Light Mode Support, Copy-to-Clipboard Summary |

## 🛠️ Features
*   **Single Bend Calculator:** Input thickness, inside radius, angle, and K-factor to instantly calculate the flat length. Supports both outside and inside flange dimensioning.
*   **Multi-Bend Profiles:** Build complex multi-bend profiles with up/down bend directions. The tool automatically sums the straight legs and bend allowances to output the total cut length.
*   **Dynamic SVG Visualizations:** Renders real-time, to-scale SVG diagrams of the flat pattern and the formed profile. Visualizes the bend zone, neutral axis, and virtual sharp dimensions.
*   **Smart Warnings:** Built-in validation alerts the user if a flange is too short for the bend setback, or if the inside radius is smaller than the material thickness (cracking risk).
*   **Integrated Reference Tables:** Includes typical K-factor guidelines based on R/t ratios and material density/tensile strength presets to help users get accurate starting values.

<br>

<img width="1106" height="1036" alt="Multi Bend" src="https://github.com/user-attachments/assets/7180deb5-fb4e-44d2-9610-c716603435f3" />


## 📂 Repository Structure
*   `/` - Contains the primary `index.html` file.
*   `/assets` - Screenshots.
*   `README.md` - Project documentation.

## 🚀 Getting Started
This application requires no build tools, package managers, or server-side backend.
