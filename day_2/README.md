---

## Handwritten Digit Recognition with CNN

Convolutional Neural Network for handwritten digit recognition using TensorFlow and Keras.





---

# Table of Contents

About

Demo

How It Works

Quick Start

Real-Life Example

Requirements

Future Improvements

Credits

License

Contributing



---

## About

This project trains a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) from the MNIST dataset.
It’s a classic beginner deep learning project to understand how image recognition works.


---

## Demo

https://paste.pics/T7BC1

Above: Screenshot link of model predicting a handwritten number with 99.15% accuracy.


---

## How It Works

1. Load the MNIST dataset (prebuilt in TensorFlow).


2. Normalize pixel values between 0 and 1 for faster training.


3. Reshape grayscale images to the format (28x28x1).


4. Build a CNN model with convolutional and pooling layers.


5. Train the model over 5 epochs.


6. Evaluate the model's performance on test data.


7. Predict new unseen images.




---

## Quick Start

# Install dependencies
pip install tensorflow numpy matplotlib keras

# Run the project
python day2.py


---

## Real-Life Example

This type of technology powers systems like:

- Postal services that read zip codes automatically

- Bank apps that recognize handwritten checks

- Automatic number plate recognition (ANPR) in traffic systems

- Classroom learning apps that read handwritten math equations



---

## Requirements

- Python 3.7 or higher

- TensorFlow 2.x

- NumPy

- Matplotlib

- Keras



---

## Future Improvements

Train for more epochs to achieve higher accuracy

Add dropout layers to prevent overfitting

Try different optimizers (SGD, RMSprop, etc.)

Deploy the model as a simple web app using Flask



---

## Credits

Made with ❤️ by Adam2fg

GitHub: https://github.com/adam2fg

---

## License

This project is licensed under the MIT License.

---

## Contributing

Pull requests are welcome!
If you spot any issues or want to suggest improvements, feel free to fork the repo and submit a PR.


---
