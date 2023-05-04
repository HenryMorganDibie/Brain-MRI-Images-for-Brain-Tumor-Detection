# Brain-MRI-Images-for-Brain-Tumor-Detection
Used SVM and CNN models to classify brain tumor images dataset. SVM outperformed CNN. Data had 253 non-tumor and 155 tumor images. Achieved accuracy of 82%. Fine-tuning can be done by adjusting SVM hyperparameters.

## Here's a summary of the steps performed for detecting brain tumors in MRI images:

* Imported necessary libraries, such as OpenCV, NumPy, scikit-learn, etc.
* Conducted exploratory data analysis (EDA) on the brain tumor dataset to gain insights into the data, such as the distribution of images across different categories (tumor and non-tumor).
* Preprocessed the data by resizing the images to a uniform size and converting them to grayscale.
* Split the preprocessed data into training and testing sets.
* Trained two classifiers - a convolutional neural network (CNN) and a support vector machine (SVM) - to classify brain tumor images.
* Evaluated the performance of both classifiers on the testing set and found that the SVM classifier had higher accuracy.
* Fine-tuned the SVM classifier by experimenting with different hyperparameters, such as changing the kernel function and tuning the regularization parameter C.
