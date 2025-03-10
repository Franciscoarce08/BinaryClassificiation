
A `requirements.txt` file is included, listing all necessary Python packages.  Common dependencies include:

*   `numpy`: For numerical computations.
*   `scikit-learn`: For machine learning algorithms and evaluation metrics.
*   `matplotlib` and `seaborn`: For data visualization.

## Usage

1.  **Clone the repository:**

    ```
    git clone https://github.com/Franciscoarce08/BinaryClassificiation.git
    cd BinaryClassificiation
    ```

2.  **Install the dependencies:**

    ```
    pip install -r requirements.txt
    ```

3.  **Explore the notebooks:**

    *   Navigate to the `notebooks/` directory.
    *   Open and run the Jupyter notebooks to understand the data preprocessing, model training, and evaluation steps.

4.  **Run the scripts:**

    *   Use the scripts in the `/src` directory to perform specific tasks like data preprocessing, model training, and evaluation.
    *   Example: `python src/binary_classification_nlp`

## Data

The data used for this project should be placed in the `data/` directory. Ensure the data is properly formatted and documented. Include a `data_dictionary.txt` or similar file to describe the features and their meanings.

## Model Training

The model training scripts are located in the `src/` directory. These scripts typically perform the following steps:

1.  Load and preprocess the data.
2.  Split the data into training and testing sets.
3.  Train a selected binary classification model.
4.  Evaluate the model's performance on the testing set.
5.  Save the trained model to the `models/` directory.

## Evaluation

Model evaluation is performed using various metrics suitable for binary classification tasks, such as:

*   **Accuracy:** The proportion of correctly classified instances.
*   **Precision:** The proportion of true positives among the instances predicted as positive.
*   **Recall:** The proportion of true positives among the actual positive instances.
*   **F1-score:** The harmonic mean of precision and recall.
*   **ROC AUC:** The area under the Receiver Operating Characteristic curve, representing the model's ability to distinguish between the two classes.
