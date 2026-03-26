# 🐱🐶 Cats vs Dogs Classifier

A beginner-friendly deep learning project that teaches a computer how to tell the difference between a **cat** and a **dog** using images.

---

## 📖 What this project is about

This project builds a simple AI model that can:

* Look at an image
* Understand what is inside the image
* Tell whether it is a **cat** or a **dog**

It learns by studying thousands of example images.

---

## 🧠 How it works

Think of it like training a child:

1. Show many pictures of cats and dogs
2. Let the brain notice patterns like ears, face shape, and fur
3. Practice again and again
4. Test with a new image

The model does the same thing, but using math and data.

---

## ⚙️ Step-by-step workflow

### 1. Load Dataset

The project uses a ready-made dataset called **cats_vs_dogs**.
It contains many images, and each image is labeled as either a cat or a dog.

---

### 2. Prepare the Data

Before training, the images are prepared:

* All images are resized to **128 × 128**
* Pixel values are scaled so the model can process them easily

This helps the model learn faster and more accurately.

---

### 3. Split the Data

The dataset is divided into two parts:

* **80%** for training (learning)
* **20%** for testing (checking performance)

---

### 4. Build the Model

The project uses a **CNN (Convolutional Neural Network)**.

It works in layers:

* First layers detect simple patterns like edges and colors
* Middle layers detect shapes like eyes and ears
* Final layers decide whether the image is a cat or a dog

---

### 5. Train the Model

During training:

* The model looks at training images
* It makes a guess
* It compares the guess with the correct answer
* It improves itself step by step

This process runs for multiple rounds called **epochs**.

---

### 6. Evaluate the Model

After training, the model is tested using images it has never seen before.
This shows how well it actually learned.

---

### 7. Visualize Results

The notebook shows:

* Sample images from the dataset
* Training progress
* Graphs for:

  * Accuracy (how correct the model is)
  * Loss (how much error the model has)

---

## 🛠️ Tools and Libraries Used

This project uses:

* Python
* TensorFlow
* TensorFlow Datasets
* Matplotlib

---

## ▶️ How to Run the Project

### Step 1: Install required libraries

```bash
pip install tensorflow tensorflow-datasets matplotlib
```

### Step 2: Run the notebook

1. Open the `.ipynb` file in **Jupyter Notebook** or **VS Code**
2. Run all cells one by one from top to bottom

---

## 📊 What Output You Will See

When you run the project, you will see:

* Images of cats and dogs
* Training logs showing progress
* Graphs showing:

  * Accuracy increasing
  * Loss decreasing

---

## 💡 Simple Summary

This project teaches a computer to **look at images and decide whether they show a cat or a dog**.
