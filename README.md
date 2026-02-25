# 🌱 Plant AI: Because your plants can't talk.

Ever looked at a spot on a leaf and wondered, "Is this normal, or is my garden in trouble?" I built **Plant AI** to solve that. It’s a full-stack web tool that acts as a digital doctor for your crops, using Deep Learning to spot diseases before they spread.

## ✨ Why this matters
Most farmers lose a huge chunk of their harvest to diseases that could have been stopped if caught early. This project bridges the gap between complex AI and everyday farming with a simple, "upload-and-diagnose" interface.

## 🛠️ What’s under the hood?
To make this work, I had to connect a lot of moving parts:
* **The Brain**: A Convolutional Neural Network (CNN) built with **TensorFlow** that "looks" at the leaves.
* **The Engine**: A **FastAPI** backend that handles the image processing and communicates with the AI.
* **The Face**: A responsive **React** frontend that makes the whole experience smooth and easy to use.

## 🚀 How to see it in action
1. **Clone it**: Get the code onto your machine.
2. **Setup the Backend**: Install the libraries with `pip install -r requirements.txt` and run `python main.py`.
3. **Launch the Frontend**: Move into the `plant-health-portal` folder and run `npm start`.

---
*Created as part of my 2026  Internship Project.*
