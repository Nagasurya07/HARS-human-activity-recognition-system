# Human Activity Recognition System (HARS)

## Overview

The Human Activity Recognition System (HARS) is a machine learning project designed to classify different types of human activities based on sensor data. This project utilizes data from accelerometers and gyroscopes to identify activities such as walking, running, sitting, and more.

## Features

- **Data Preprocessing**: Clean and preprocess raw sensor data for analysis.
- **Feature Extraction**: Extract relevant features from the sensor data to improve model performance.
- **Model Training**: Train machine learning models to classify human activities.
- **Model Evaluation**: Evaluate the performance of the trained models using various metrics.
- **Prediction**: Predict human activities based on new sensor data.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Nagasurya07/HARS-human-activity-recognition-system.git
   cd HARS-human-activity-recognition-system
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Prepare the dataset:
   - Place your sensor data in the `data/` directory.

2. Run the preprocessing script:
   ```sh
   python preprocess.py
   ```

3. Train the model:
   ```sh
   python train.py
   ```

4. Evaluate the model:
   ```sh
   python evaluate.py
   ```

5. Make predictions:
   ```sh
   python predict.py --input data/new_sensor_data.csv
   ```

## Project Structure

- `data/`: Directory to store raw and processed data.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and experimentation.
- `src/`: Source code for the project.
  - `preprocess.py`: Script for data preprocessing.
  - `train.py`: Script for training the machine learning model.
  - `evaluate.py`: Script for evaluating the model.
  - `predict.py`: Script for making predictions.
- `requirements.txt`: List of dependencies required for the project.
- `README.md`: Project description and usage instructions.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset used in this project is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones).
- Special thanks to the contributors and the open-source community.
