# 🧠 Neural Network Layers + FizzBuzz Demo

This project demonstrates the inner workings of neural network layers through a simple yet effective example: solving the classic FizzBuzz problem using a fully connected neural network.

## 🎯 Purpose

- To **visualize and understand the structure of neural networks**
- To **apply a neural net to the FizzBuzz problem**
- To provide a **minimal yet instructive** example of training, data transformation, and prediction in Python

## 📁 Project Structure

```
neural-fizzbuzz/
├── data.py         # Prepares FizzBuzz training data
├── tensor.py       # Defines the neural network layers and tensor operations
├── train.py        # Trains the network and prints predictions
├── README.md       # You’re reading it!
```

## 🧠 What is FizzBuzz?

FizzBuzz is a simple programming challenge:
- Print `"Fizz"` for numbers divisible by 3
- Print `"Buzz"` for numbers divisible by 5
- Print `"FizzBuzz"` for numbers divisible by both
- Otherwise, print the number

Here, we use it as a classification problem for a neural net.

## 🚀 How to Run

### 1. Clone and navigate to the project:
```bash
git clone https://github.com/shinigxmi3087/neural-fizzbuzz.git
cd neural-fizzbuzz
```

### 2. (Optional) Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3. Install required packages:
```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, install manually:
```bash
pip install numpy
```

### 4. Run the training script:
```bash
python train.py
```

You should see training outputs, followed by FizzBuzz predictions.

## 🧱 Key Components

- **data.py**: Encodes integers into binary vectors, assigns FizzBuzz labels.
- **tensor.py**: Custom implementation of neural layers and activations.
- **train.py**: Builds the network, trains it, and prints predictions.

## 📦 Requirements

- Python 3.x
- `numpy`

## 🔍 Example Output

```
epoch 0 loss: 0.9712
epoch 10 loss: 0.5638
...
98 => Buzz
99 => Fizz
100 => Buzz
```

## 📚 Educational Value

This project is designed for:
- Beginners learning how neural nets work internally
- Anyone curious how basic ML can solve toy problems
- Demonstrating concepts **without relying on large ML libraries**

## 📄 License

MIT License
