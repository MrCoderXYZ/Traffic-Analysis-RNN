# Traffic Prediction using RNN

This repository contains code for predicting traffic counts at various intersections using a Recurrent Neural Network (RNN). The project includes preprocessing, model training, evaluation, and visualization.

## Features

- Time-series traffic data preprocessing.
- Model training using RNN with TensorFlow/Keras.
- Visualization of predictions and model efficiency.
- Save and load trained models for future use.

---

## Prerequisites

Ensure you have the following installed on your system:

- Python 3.8–3.11
- Git

---

## Clone the Repository

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/your-username/traffic-prediction-rnn.git
cd traffic-prediction-rnn
```

---

## Install Dependencies

Set up the Python environment and install required dependencies:

1. **Create a virtual environment** (recommended):

   ```bash
   python -m venv myenv
   source myenv/bin/activate       # For Linux/Mac
   myenv\Scripts\activate          # For Windows
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Verify installation**:

   ```bash
   python -m pip list
   ```

---

## Run the Project

1. Place your dataset (e.g., `traffic_data.xlsx`) in the project directory.
2. Update the file path in the code, if necessary.
3. Execute the script:
   ```bash
   python traffic_prediction.py
   ```

---

## Dependencies

All required Python packages are listed in `requirements.txt`:

```
pandas
numpy
scikit-learn
matplotlib
tensorflow
openpyxl  # For handling Excel files
```

To manually install a specific package:

```bash
pip install <package-name>
```

---

## Outputs

- **Prediction Plots**: Visualize actual vs predicted traffic counts.
- **Saved Model**: The trained RNN model is saved as `traffic_prediction_rnn_model.h5`.

---

## Contributing

Feel free to contribute to this project. To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature-name'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a pull request.

---

## License

This work is provided without any associated license.
