# Plant-Disease-Recognition-System
Plant Disease Recognition System

# Dataset Required
Dataset Link: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

# Model Setup Instructions

To use this project, you need to download a pre-trained model from the given Google Drive link and place it in the `models` directory. Follow the steps below to set it up correctly:

1. **Trained Model**
   - Click [here](https://drive.google.com/file/d/1D7M0vK2JswSwxAY6AM4GZh3Qh4-LSXbO/view?usp=drive_link) to open the Google Drive link.

1. **Specify the Model File Location**
   - Open the `app.py` file in a text editor.
   - Locate line 8, which contains the following code:
     ```python
     tf.keras.models.load_model("")
     ```
   - Update the empty string with the relative path to the model file. For example:
     ```python
     tf.keras.models.load_model("models/your_model_file.h5")
     ```
     Replace `your_model_file.keras` with the actual name of the model file you downloaded.

2. **Run the Server**
   - Open a terminal and navigate to the root directory of this project.
   - Run the following command to start the server:
     ```bash
     python app.py
     ```
     [Watch the demo video](https://drive.google.com/file/d/1WEUjAAlyLqnj-B_tgJqUaR0MBcMmSKEQ/view?usp=drive_link)
<img width="3840" height="1775" alt="image" src="https://github.com/user-attachments/assets/b69b111e-cd17-44ee-bafe-d6a43403bf86" />
