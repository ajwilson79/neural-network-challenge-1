# neural-network-challenge-1

# Student Loan Repayment Prediction - Module 18 Challenge

This notebook aims to predict whether a borrower will repay their student loan using a neural network model. The prediction model uses various features from the dataset to determine the likelihood of loan repayment, which can help in providing accurate interest rates for borrowers.

## Files in the Repository

- `student_loans_with_deep_learning.ipynb`: Jupyter notebook containing the code to preprocess the data, build, evaluate, and use the neural network model for predictions.
- `student_loans.csv`: CSV file with information about previous student loan recipients.

## Requirements

Before running the notebook, ensure you have the following dependencies installed:

- Python 3.7+
- pandas
- scikit-learn
- tensorflow
- keras

You can install these dependencies using pip:

```sh
pip install pandas scikit-learn tensorflow keras
```

## How to Use

1. **Clone the Repository:**

   Clone the repository to your local machine using the following command:

   ```sh
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Upload Notebook to Google Colab:**

   - Open Google Colab and upload the `student_loans_with_deep_learning.ipynb` notebook.
   - Alternatively, you can run the notebook locally using Jupyter Notebook.

3. **Prepare the Data:**

   - Load the data from the provided CSV file.
   - Preprocess the data using Pandas and scikit-learn’s `StandardScaler()`.

4. **Build and Evaluate the Neural Network Model:**

   - Create a deep neural network model using TensorFlow’s Keras.
   - Compile and fit the model using the `binary_crossentropy` loss function, the `adam` optimizer, and the `accuracy` metric.
   - Evaluate the model using test data to calculate its loss and accuracy.

5. **Predict Loan Repayment Success:**

   - Reload the saved model.
   - Make predictions on the testing data.
   - Generate a classification report with the predictions and testing data.

6. **Recommendation System Discussion:**

   - Discuss the data needed to build a recommendation system for student loans.
   - Choose an appropriate filtering method and justify your choice.
   - Consider real-world challenges while building the recommendation system.

## Results

After running the notebook, you will have a trained neural network model that can predict the likelihood of a borrower repaying their student loan. The notebook also includes a classification report to evaluate the model’s performance.

## Notes

- Ensure to periodically save your progress and push the changes to your GitHub repository.
- Follow best practices for preprocessing to ensure consistent results between training and testing data.

## References

Based on starter files and data provided as part of OSU-VIRT-AI-PT-02-2024-U-LOLC-MTTH (OSU AI Bootcamp) for Challenge 18. Remaining code based on code examples provided as part of the course.
