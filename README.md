# 🌼 Iris Flower Classification with PyTorch

This project is a beginner-friendly neural network built using **PyTorch** to classify **Iris flower species** based on sepal and petal measurements.

It was developed by following the excellent YouTube tutorial series by [John Elder of Codemy.com](https://www.youtube.com/playlist?list=PLCC34OHNcOtpcgR9LEYSdi9r7XIbpkpK1), specifically episodes 5 and 6, and expanding on them with original contributions and experiments.

---

## 📚 Tutorial Source

- **Series:** Deep Learning With PyTorch (Codemy.com)
- **Videos Used:**  
  - [Create a Basic Neural Network](https://www.youtube.com/watch?v=JHWqWIoac2I&index=5)  
  - [Train Neural Network Model](https://www.youtube.com/watch?v=Xp0LtPBcos0&index=6)  

---

## 🧠 What This Project Does

- Loads the **Iris dataset** from a public GitHub CSV
- Preprocesses the data and splits into training/testing sets
- Builds a **neural network with PyTorch** using `nn.Module`
- Trains the model using **cross-entropy loss** and the **Adam optimizer**
- Evaluates model performance with **test loss** and **classification accuracy**

---

## 🧪 Model Architecture

- Input: 4 features (sepal length, sepal width, petal length, petal width)
- Hidden Layers:
  - Layer 1: 8 neurons
  - Layer 2: 9 neurons
  - **Layer 3 (Added): 10 neurons**
- Output: 3 classes (setosa, versicolor, virginica)
- Activation: **LeakyReLU**
- Regularization: **Dropout** (p=0.2)
- Learning Strategy: **StepLR learning rate scheduler**

---

## ✅ My Contributions Beyond the Tutorial

To go beyond simply following along, I implemented several enhancements and learning experiments:

- 🔼 **Added a third hidden layer** to increase model capacity and test deeper architectures
- 🔁 **Replaced ReLU with LeakyReLU** to reduce the risk of vanishing gradients
- 💧 **Added Dropout** for regularization and to reduce overfitting
- 📉 **Implemented a learning rate scheduler** (`StepLR`) with `gamma=0.9` for smoother optimization over long training
- 📊 **Evaluated test loss and accuracy**, achieving:
  - **Test Loss:** `0.163`
  - **Test Accuracy:** `96.7%`
- 📈 Visualized loss across training epochs
- ✅ Maintained code version control and structure using **Google Colab** + **GitHub**

---

## 🚀 How to Run This Notebook

1. Clone this repo or open in Google Colab
2. Run each cell top to bottom
3. Observe training loss graph and final test accuracy

---

## 🧩 Tools & Libraries Used

- [PyTorch](https://pytorch.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/)

---

## 🙌 Acknowledgments

Thanks to [John Elder](https://www.youtube.com/@Codemycom) for his clear and approachable tutorials that inspired this project.

---

## 📌 Future Ideas

- Confusion matrix visualization
- Save/load model with `torch.save()`
- Add command-line interface (CLI) or streamlit dashboard

---

## 🧑‍💻 Author

**Your Name**  
[Jonathon Leiding]([(https://github.com/JonathonLeiding])

