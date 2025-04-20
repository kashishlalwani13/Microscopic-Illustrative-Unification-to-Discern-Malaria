🦠 Microscopic Illustrative Unification to Discern Malaria

This project leverages deep learning to automate the detection of malaria-infected cells in microscopic blood images. Using preprocessed image data and neural networks, it classifies whether a given cell is healthy or infected.

📁 Files & Structure

Cells.npy, labels.npy - Numpy arrays containing cell image data and corresponding labels.

MalriaDetectionr.ipynb - Notebook for training and evaluating the malaria detection model.

MalariaCells.ipynb - Additional analysis and visualization notebook.

app.py - Web app to upload/test images and get malaria classification.

Procfile - Deployment configuration for Heroku or similar platforms.

🧠 Model Overview

CNN-based architecture trained on labeled microscopy images.

Uses transfer learning and image preprocessing techniques for improved accuracy.

Evaluated using metrics like accuracy, precision, recall.
