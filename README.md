Sure, here's a draft for your README file for your ESENSE HAR repository. Please replace `[INFO]` sections with your own information.

---
# ESENSE HAR Repository

This repository contains code for Human Activity Recognition (HAR) using the ESENSE wearable sensor. We use two different methods to validate our models: Leave-One-Out cross-validation and Random Split.

## Requirements

- Python 3.x
- Scikit-learn
- NumPy
- pandas

## Dataset

We use the ESENSE sensor dataset for Human Activity Recognition. Please place the dataset in the `data/` directory.

## Methodology

We use the following two methods for model validation:

### Leave-One-Out Cross-Validation

In this method, we use all but one of the data instances to train our model, then validate the model on the left out data instance. This process is repeated such that each data instance is used exactly once for validation.

### Random Split

In this method, we randomly split our data into a training set and a test set. The model is trained on the training set, and validated on the test set.

## Results

The performance of our model was as follows:

- `[INFO]: Performance metrics when using Leave-One-Out Cross-Validation`
- `[INFO]: Performance metrics when using Random Split`

Please replace the `[INFO]` sections with your model's performance metrics.

## How to Run

To run the Leave-One-Out Cross-Validation:

```
python leave_one_out.py
```

To run the Random Split:

```
python random_split.py
```

## Contact

For any further questions, please feel free to reach out to me at [your-email@domain.com]

---

This is just a basic template. Feel free to expand it to include more details about your project, such as the problem statement, more details about the methodology and results, how to interpret the results, any limitations of your current approach, future work, etc. The more details you can provide, the easier it will be for others to understand and use your code.
