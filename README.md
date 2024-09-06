

# Music Recommendation System

## Overview
This project implements a music recommendation system using a machine learning model trained on a dataset of songs. The system employs a decision tree classifier to recommend music based on user preferences and gender. The project consists of data preparation, model training, and visualization of results.

The model was saved using `joblib` for easy reusability and can be used to make predictions about song recommendations.

## Project Structure
- **`Musicrecommender.ipynb`**: Jupyter notebook containing the code for data preprocessing, model training, and music recommendation.
- **`visualization.ipynb`**: A separate Jupyter notebook for visualizing the results of the recommendations.
- **`music recommender.joblib`**: Serialized model file saved using `joblib` to load the trained decision tree classifier.
- **`music recommender.dot`**: Visualization file for the decision tree structure.
- **`music.csv`**: The dataset containing song information used for training the model.


## Dependencies
This project relies on the following Python libraries:
- `pandas`: Data manipulation and analysis.
- `numpy`: Numerical operations.
- `scikit-learn`: Machine learning library used for building the decision tree classifier.
- `matplotlib`: Data visualization.
- `joblib`: Serialization and deserialization of the machine learning model.

## Getting Started

### Prerequisites
Ensure you have Python installed and a virtual environment set up.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Yvokim/ML-Music-Recommender.git
   cd ML-Music-Recommender
   ```

2. Set up the virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib joblib
   ```

### Running the Project

1. Open `Musicrecommender.ipynb` in Jupyter Notebook to review the data preprocessing and model training steps.

2. Load the trained model from the `music recommender.joblib` file and use it to make music recommendations:
   ```python
   import joblib
   model = joblib.load("music recommender.joblib")
   ```

3. Use `visualization.ipynb` to visualize the decision tree and understand the model's decision-making process.

## Usage

- Modify the dataset or adjust the model parameters in `Musicrecommender.ipynb` to experiment with different types of recommendations.
- Visualize the decision tree using the provided `.dot` file to understand how the model makes predictions.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
