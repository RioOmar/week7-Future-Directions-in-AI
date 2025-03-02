# week7-Future-Directions-in-AI

Instructions:

Read the provided material on "Future Directions in AI" carefully.

Answer the conceptual/application-based questions in your own words. Be clear and concise.

For the coding question, write a Python program as described. Ensure your code is well-commented and functional.

Submit your answers in a single document (PDF or Word file) along with the Python code file (.py).

Conceptual/Application-Based Questions:

AI for Edge Computing:

Define edge computing and explain how AI enhances its capabilities. Provide an example of a real-world application where AI-powered edge computing is critical.

AI and IoT Integration:

How does the integration of AI with IoT improve the functionality of smart home systems? Explain with an example of an AI-powered IoT device and its benefits.

AI and IoB (Internet of Bodies):

What is the Internet of Bodies (IoB), and how does AI integration with IoB devices improve healthcare monitoring? Provide an example of an AI-powered IoB application.

Human-AI Collaboration:

What is human-AI collaboration, and how does it benefit industries like healthcare and creative arts? Provide an example of how AI can assist humans in a collaborative setting.

Coding Question:

AI in Healthcare:

Write a Python program that simulates an AI model for medical image analysis. Use a simple machine learning model (e.g., RandomForestClassifier) to predict whether a simulated medical image contains a tumor or not. Follow these steps:

Simulate medical image data (e.g., pixel values) using random arrays.

Train a machine learning model on the simulated data.

Predict whether a new simulated image contains a tumor.

Print the result as "Tumor detected!" or "No tumor detected."

Requirements:

Use the following libraries: numpy and sklearn.ensemble.RandomForestClassifier.

Include comments in your code to explain each step.

Ensure your code is functional and produces the correct output.

Example Code Structure:


import numpy as np
from sklearn.ensemble import RandomForestClassifier

# Simulate medical image data (e.g., pixel values)
X = np.random.rand(100, 256)  # 100 images, 256 features each
y = np.random.randint(0, 2, 100)  # Binary labels (0: healthy, 1: tumor)

# Train a simple AI model
model = RandomForestClassifier()
model.fit(X, y)

# Predict on new data
new_image = np.random.rand(1, 256)
prediction = model.predict(new_image)
print("Tumor detected!" if prediction[0] == 1 else "No tumor detected.")
Submission Guidelines:

Submit your answers to the conceptual questions in a PDF or Word file.

Submit your Python code as a separate .py file.
