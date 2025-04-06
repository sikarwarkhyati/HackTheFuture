# Forge - Multi-Agent E-Commerce Platform

Forge is a multi-agent system project designed to deliver real-time, hyper-personalized recommendations for an e-commerce platform. This project is structured around independent agents that handle user behavior tracking, product intelligence, dynamic pricing, recommendations, and feedback. We have set up a basic home page using Flask with templated HTML, CSS, and JavaScript to serve as the landing page.

## What We Have Done So Far

- **Project Setup:**  
  - Created a project folder named `Forge` with a modular structure.
  - Established key directories: `agents`, `shared`, and `orchestrator`.

- **Orchestrator Service:**  
  - Developed a basic Flask application in `orchestrator/controller.py` that serves a home page.
  - Created a `templates` folder with `home.html` for the HTML content.
  - Added a `static` folder containing `styles.css` for styling and `scripts.js` for simple JavaScript interactions.
  
- **Basic Home Page:**  
  - The home page displays a welcoming message, navigation links, and a "Get Started" button that triggers a JavaScript alert.
  - This page serves as the starting point for further development of multi-agent functionalities.

## Getting Started

1. **Set Up Virtual Environment:**  
   ```bash
   python -m venv venv
   venv\Scripts\activate
