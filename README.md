# Tree Species Classification using Neural Network

## Project Overview

This project aims to develop a neural network to classify tree species found in our university garden. The goal is to distinguish between visually similar species using data collected from the field.

## Group Members

- **Risfath Ahamed**
- **Mohammed Rishny**
- **Fathima Hiba**

## Project Tasks

1. **Field Survey and Data Collection**
   - Conducted a detailed field survey to gather data on tree species.
   - Collected various physical characteristics and measurements.

2. **Data Preparation**
   - Cleaned and prepared the dataset, ensuring quality and relevance.
   - Added Gaussian noise to enhance generalization.
   - Encoded the target labels and split the data into training and testing sets.
   - Normalized the features for better model performance.

3. **Neural Network Development**
   - Designed a neural network architecture using TensorFlow and Keras.
   - Optimized the model through hyperparameter tuning.
   - Achieved a test accuracy of **76.67%%**.

4. **Model Training and Evaluation**
   - Trained the model over 30 epochs with a validation split for performance monitoring.
   - Visualized training history to track accuracy and loss.

5. **Model Deployment**
   - Saved the trained model, label encoder, and scaler for future use.

6. **Viva Presentation**
   - Presented findings, discussed the approach, results, and challenges faced.

## Usage

1. **Clone the repository**:
   ```bash
   git clone [<repository-link>](https://github.com/RRisfathAhamed/Tree-Species-Classification-Using-NN.git)
   cd <repository-directory>
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the code**:
   Ensure the dataset file `Euphoria.csv` is in the project directory.

   ```python
   python train_model.py
   ```

4. **Evaluate the model**:
   The code will output the test accuracy and save the model and preprocessing objects.

## Code Explanation

The main code for training the model is in `train_model.py` and includes the following steps:
- Load and preprocess the data.
- Define and train the neural network model.
- Evaluate the model's performance.
- Save the model and preprocessing objects for future use.

## Results

- **Test Accuracy**: 76.67%%

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank our university for providing the resources and support for this project.

---

Group Euphoria: Risfath Ahamed, Rishny, & Hiba.
```

Replace `<repository-link>` with your actual GitHub repository link and `XX.XX%` with your achieved accuracy. This README file provides a comprehensive overview of your project, including tasks, usage instructions, and acknowledgments.
