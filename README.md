# Breast Cancer Histopathology Classification Using a Convolutional Neural Network (CNN)

**Team Member(s):**
- Anthony Areas

## Project Description

This project uses a Convolutional Neural Network (CNN) to classify breast histopathology images as either cancerous or non-cancerous. The objective is to evaluate the effectiveness of deep learning for automated medical image classification using a publicly available dataset. Images are preprocessed, divided into training, validation, and testing sets, and used to train a CNN model. The model is evaluated using accuracy, loss, confusion matrix, and other classification metrics to determine its performance.

## Running the Project

1. Clone the repository.

```
git clone https://github.com/USERNAME/Breast-Cancer-Histopathology-CNN.git
```

2. Navigate to the project folder.

```
cd Breast-Cancer-Histopathology-CNN
```

3. Install the required libraries.

```
pip install -r requirements.txt
```

4. Open Colab.

```
Google colab notebook use runtime t4GPU
```

5. Open:

```
notebooks/CV_project2(2).ipynb
```

6. Run all notebook cells from top to bottom.

## Dependencies

- Python 3.10+
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- OpenCV
- Pillow
- tqdm
- YOLO
- ultralytics

## Dataset

This project uses the Breast Histopathology Images dataset.

If the dataset cannot be redistributed due to licensing restrictions, see the `data/README.md` file for download instructions.

## Results

The trained CNN is evaluated using:

- Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Confusion Matrix
- Precision
- Recall
- F1-score

## Repository Structure

- `notebooks/` - Jupyter notebooks
- `data/` - Dataset or download instructions
- `models/` - Saved trained models
- `results/` - Evaluation results
- `images/` - Figures used in reports
