# Project: Conception d'une Voiture Autonome

![Project Logo](logo.png)

## Overview

This project, "Conception d'une Voiture Autonome," is a collaborative effort by Future Vision Transport to develop computer vision systems for autonomous vehicles. As an AI engineer on the Research and Development (R&D) team, your role is to focus on image segmentation within the embedded vision system.

## Project Description

Future Vision Transport is dedicated to designing computer vision embedded systems for autonomous vehicles. In this project, our team will work on various aspects of the system, including real-time image acquisition, image processing, image segmentation (your primary responsibility), and the decision-making system.

### Your Mission

Your mission is to create a robust image segmentation model that seamlessly integrates into the entire embedded system chain. This project involves collaborating with team members specializing in different parts of the system.

**Key Objectives:**

1. Train an image segmentation model on eight main categories, using Keras as the framework.
2. Develop a user-friendly prediction API (Flask or FastAPI) that takes an image as input and returns the predicted image mask.
3. Design a Flask-based web application for presenting results and testing the API.

## Getting Started

Follow these steps to set up and run the project locally:

### Prerequisites

- Python 3.7 or higher
- Virtual environment (recommended)
- Git (optional, for version control)

### Installation

1. Clone the repository:

```bash
   git clone https://github.com/yourusername/voiture-autonome.git
```

2. Activate the virtual environment:

```bash
python -m venv env
```

3. Activate the virtual environment:
```bash
# Windows:
.\env\Scripts\activate

# macOS and Linux:
source env/bin/activate
```

4. Install project dependencies:
```bash
pip install -r requirements.txt
```

**Usage:**

- Train the image segmentation model by running the appropriate script.
- Launch the Flask API and web application.
- Access the web application in your browser to test the API and view results.

**Project Structure:**

- `/data`: Data related to the project.
- `/models`: Saved model checkpoints.
- `/scripts`: Scripts for training and running the model.
- `/webapp`: Flask-based web application files.
- `/notebooks`: Jupyter notebooks for data exploration and analysis.

**Contributing:**

If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Create a pull request with a clear description of your changes.