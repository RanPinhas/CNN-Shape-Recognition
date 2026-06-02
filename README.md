# Exercise 2: Shape Recognition using a Convolutional Neural Network (CNN) from Scratch

**Live Demo Link:** [https://ranpinhas.github.io/CNN-Shape-Recognition/](https://ranpinhas.github.io/CNN-Shape-Recognition/)

## Submitted by (Afeka College of Engineering)
* **Ran Pinhas**

---

## Project Description
This project implements a complete client-side Convolutional Neural Network (CNN) built entirely from scratch using Vanilla JavaScript, HTML, and CSS across three separate files. The project was developed without the use of any external libraries (such as TensorFlow.js).

The model is trained to recognize three basic shape types: **circle, square, and triangle**. The user can draw a shape on a built-in Canvas, train the model, and test its prediction capabilities in real-time.

## Key Features
* **Hyperparameter Configuration:** The interface allows full control over the network's parameters before training, including: number of filters, filter size, learning rate, and number of training epochs.
* **State Persistence (LocalStorage):** After training the model, the weights and biases are automatically saved in the browser's local memory (`LocalStorage`).
* **Pre-trained Model:** To facilitate the grading process, the `cnn.js` file includes the weights of an already trained model. Upon initial visit to the site, these weights are automatically injected into the user's `LocalStorage`, making the model ready for shape recognition immediately upon opening the link.
* **Glossary of Terms:** The project includes a separate HTML page containing a comprehensive glossary of 40 key concepts from the fields of AI and neural networks.

## File Structure
1. `index.html` - The structure of the main model page, parameter controls, and the drawing canvas.
2. `dictionary.html` - The comprehensive glossary page.
3. `style.css` - The interface design and visual layout.
4. `cnn.js` - The network logic, Forward Pass and Backpropagation math, data collection, and LocalStorage management.

## How to Use
1. Visit the project link hosted on GitHub Pages.
2. (Optional) Adjust the different model parameters (Epochs, Learning Rate, etc.).
3. **To retrain the model:** Draw a shape on the canvas and add it to the dataset using the dedicated buttons ("Circle", "Square", "Triangle"). Repeat this process multiple times to gather data, then click **Train Model**.
4. **To test recognition:** Draw a new shape on the canvas and click **Predict Shape**. The system will display the identified shape's name and the model's confidence level.
5. Clicking **Reset Model** will clear the weights from the `LocalStorage` and reset the system's memory.
