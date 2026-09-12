#  Bear Classifier

An educational deep learning project for classifying bear images using a trained neural network.

 Project Description

This project was developed by **ABDESSAMAD AIT HAKI** as a personal extension of a Deep Learning practical session (TD) carried out in class.

During the practical session, we worked on the implementation of a basic bear image classification model. The original work was limited to the standard model provided during the course.

For this personal project, I extended the original work by developing a complete interactive application and expanding the classification task to **three categories**.

The application allows the user to upload an image of a bear and uses a trained deep learning model to predict its type.

The model provides:
- The predicted bear class
- The confidence score
- The top 3 predictions with their probabilities

# Bear Classes

The extended model can classify images into three categories:

-  Black bear
-  Grizzly bear
-  Teddy bear

# Technologies

- Python
- Fastai
- PyTorch
- IPyWidgets
- Jupyter Notebook
- Deep Learning

# How to Use

1. Open `bear_app_clean.ipynb` in Google Colab or Jupyter Notebook.
2. Install the required dependencies from `requirements.txt`.
3. Load the trained model `export.pkl`.
4. Run the notebook cells.
5. Upload an image.
6. Click **CLASSIFY**.
7. The application displays the predicted class and confidence score.

# Project Structure

```text
Bear Classifier/
│
├── bear_app_clean.ipynb
├── export.pkl
├── requirements.txt
├── .gitattributes
└── README.md
