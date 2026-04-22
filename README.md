# Cosmic AI Evaluator - Code-Mixed Robustness

A cutting-edge, academic-grade web application designed for researchers and engineers to manually evaluate the robustness of Large Language Models (LLMs) when processing code-mixed Indian languages. 

This project provides an interactive 3D diorama-style interface—inspired by minimalist and futuristic design principles—for inputting evaluation data, visualizing performance metrics, and conducting error analysis based on established methodologies.

## Features

- **Futuristic 3D Interface**: Built with Three.js, featuring an interactive astronomical scene with orbiting moons and dynamic lighting.
- **Robustness Evaluation Protocol**: A structured data entry form to add evaluation nodes for code-mixed sentences.
- **Code Mixing Index (CMI) Calculator**: Automatically computes the CMI based on token counts.
- **Multi-Model Comparison**: Compare predictions across leading models (ChatGPT, Gemini, Perplexity) for monolingual and code-mixed inputs.
- **Deep Dive Dashboard**: Generates an analytical report with visualizations using Chart.js.
- **Advanced Metrics**: Calculates Accuracy, Prediction Consistency Rate (PCR), and Robustness Degradation Score (RDS).

## Tech Stack

- **Frontend Framework**: React 18 (via CDN)
- **Styling**: Tailwind CSS
- **3D Graphics**: Three.js
- **Animations**: Framer Motion
- **Charting**: Chart.js
- **Icons**: Flaticon

## How to Run

Since the application uses CDN links for its dependencies, you can simply open the `index.html` file in any modern web browser to run the application locally. No build step or local server is required.

1. Clone the repository.
2. Open `index.html` in your preferred web browser.

## Evaluation Metrics

- **Accuracy**: Percentage of correct sentiment predictions for both monolingual and code-mixed inputs.
- **Prediction Consistency Rate (PCR)**: Percentage of instances where the model's prediction for a code-mixed input matches its prediction for the corresponding monolingual baseline.
- **Robustness Degradation Score (RDS)**: The difference in accuracy between monolingual inputs and code-mixed inputs, indicating the degradation in model performance.
- **Code Mixing Index (CMI)**: The percentage of tokens from the non-matrix language in a code-mixed sentence.

## Contributing

Feel free to fork this project and submit pull requests to add new features or improve existing functionality.
