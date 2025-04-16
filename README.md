# Human Action Detection Project

## Project Description
This project classifies 13 human activities (e.g., walking, running) using the Mobile Health dataset's sensor data (acceleration, gyroscope) from 10 subjects. It employs a Random Forest model, optimized with preprocessing, achieving >90% accuracy, with visualization and real-time prediction.

## Dataset
The dataset is too large for GitHub. Download it using the link in [dataset.txt](dataset.txt). Save the file as `mhealth_raw_data.csv` in the project directory after downloading.

## Instructions
1. Download the dataset from the link in `dataset.txt`.
2. Ensure Python 3.x, pandas, numpy, matplotlib, and scikit-learn are installed (`pip install -r requirements.txt` if using a requirements file).
3. Run the Jupyter Notebook `human_action_detection.ipynb` to execute the project.

## Usage
- The code trains a Random Forest model to detect activities.
- Use the model to predict new actions with real-time sensor data (12 features: alx, aly, alz, glx, gly, glz, arx, ary, arz, grx, gry, grz).
- Adjust `new_data` in Cell 12 with actual sensor readings for prediction.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

## License
[MIT License](LICENSE) (or specify your preferred license)
