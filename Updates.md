- **GitHub Upload**:
  - Uploaded project files:
    - Jupyter Notebook (`Human_act_recog.ipynb`).
    - `UPDATES.md` file for progress tracking.
    

### **14th January**
- **Dataset Exploration**:
  - Downloaded and explored the UCI HAR dataset structure.
  - Verified the local paths for the dataset and ensured compatibility with the code.
  - Imported required libraries and performed data preprocessing for x, y, and subject columns in the training dataset.
  - Analyzed the contents:
    - Folders: `train`, `test`
    - Files: `features.txt`, `activity_labels.txt`, `subject_train.txt`, `X_train.txt`, `y_train.txt`, and respective test files.
    -  - Examined feature and activity label mappings (`features.txt`, `activity_labels.txt`).

### **15th January**
- **Model Development**:
  - Selected logistic Regression for activity classification.
  - Implemented a training pipeline:
    - Trained the model on `X_train` and `y_train`.
    - Tuned hyperparameters for optimal performance.
  - Evaluated the model on training data:
    Evaluated the model's accuracy based on the training dataset.
    - Generated initial metrics (confusion matrix and classification report).

### **16th January**
- **Model Testing**:
  - Tested the model on the test dataset provided (x, y, and subject columns).
  - Generated predictions for the test dataset.
- Evaluated model performance using:
  - Measured and recorded the accuracy of predictions on the test dataset.
  - Confusion matrix: Visualized classification results for each activity.
  - Classification report: precision, recall, and F1-score 

### **17th January**
- **Finalization and Documentation**:
    - Results visualization.
  - Added comments  to improve code readability.
-Verified the end-to-end pipeline from training to testing












