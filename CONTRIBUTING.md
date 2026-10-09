# Contributing to Device Cloud Explorer

Thank you for taking the time to contribute! We welcome community contributions to help improve this infinite 3D WebGL data center simulation. 

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## How Can I Contribute?

### 🪲 Reporting Bugs
* Check the **GitHub Issues** tab to ensure the bug hasn't already been reported.
* Open a new issue and include:
  * A clear, descriptive title.
  * Steps to reproduce the issue.
  * Your browser and operating system details (e.g., Chrome on Windows 11).
  * Any relevant console error messages or screenshots.

### 💡 Suggesting Enhancements
* Open an issue describing your idea (e.g., adding sound effects, new server environment configurations, or custom UI elements).
* Explain *why* this feature would be useful and how it fits the device cloud environment aesthetic.

### 🛠️ Code Contributions
If you want to fix a bug or add a new feature yourself:
1. **Fork the Repository:** Create your own copy of this repository on GitHub.
2. **Make Your Changes:** Work on your features in a separate branch.
3. **Keep Code Clean:** Maintain clean Three.js/JavaScript architecture. Do not add any corporate or trademarked brand names anywhere in the user interface or code logs.
4. **Submit a Pull Request (PR):** Open a PR back to the main branch with a clear explanation of your changes.

## Development Checklist

To ensure your game changes run smoothly across different setups:
* **WebGL Optimization:** Ensure any new 3D geometries or materials do not drop the game's framerate. Use instanced meshes or basic geometry where possible.
* **Responsive Layouts:** Verify that changes to the viewport canvas scale cleanly across both desktop and mobile simulation view constraints.
* **File Names:** All core static assets (like texture maps or scripts) must use lowercase alphanumeric characters and clear paths.

## Style Guidelines

* **Project Framing:** This project is strictly an independent, fictional 3D ambient art simulation.
* **No Branding:** Do not re-introduce any real corporate brand names or proprietary logistics names into the environment text, HUD, or log overlays. Keep all hardware terminology generic.
