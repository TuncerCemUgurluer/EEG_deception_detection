# Deception Detection using EEG Signals

## Project Description
This project aims to analyze EEG signals to detect deception using machine learning techniques. The system processes EEG data collected during lie and truth states and employs various signal processing and deep learning methods to classify the states accurately. Due to the complexity of lying patterns for each individual, the model is not fully generalized, achieving an accuracy of approximately 80% for single individuals.

## Features
- **EEG Signal Analysis**: The system analyzes EEG signals collected during lie and truth states to identify patterns associated with deception.
- **Data Augmentation**: EEG data is augmented using frequency-domain perturbations and jittering techniques to enhance model robustness.
- **Model Training and Evaluation**: Deep learning models, including LSTM networks, are trained and evaluated on EEG data to classify lie and truth states. Metrics such as accuracy, loss, and classification reports are used for evaluation.
- **Visualization**: The project includes visualizations of training and evaluation metrics to assess model performance and provide insights into its behavior.

## Code Structure and Usage
The codebase consists of several components:

- **Data Preparation**: EEG data from lie and truth states are preprocessed and augmented for training and testing.
- **Model Building**: Deep learning models, such as LSTM networks, are constructed for classifying lie and truth states based on EEG signals.
- **Training**: The models are trained on augmented EEG data, and data augmentation techniques are employed to improve model performance.
- **Evaluation**: The trained models are evaluated on validation and test datasets to assess accuracy and performance in classifying lie and truth states.
- **Visualization**: Training and evaluation metrics, such as accuracy and loss, are visualized using plots to analyze model behavior and performance over epochs.

## Repository Structure
The repository structure is organized as follows:

- **README.md**: Provides an overview of the project, usage instructions, and examples.
- **code/**: Contains the source code files for data preparation, model building, training, evaluation, and visualization.
- **data/**: Includes the collected EEG dataset, augmented data, and preprocessed data (Note: Actual data will not be published).
- **models/**: Stores the trained model weights and configurations (Note: Actual models will not be published).
- **results/**: Contains visualizations of training and evaluation metrics, as well as classification reports.
- **LICENSE**: License information for the project.
- **requirements.txt**: Lists the dependencies required to run the project.

This structure facilitates easy navigation and understanding of the project, enabling users to replicate the experiments and analyze the results effectively. Additionally, it promotes collaboration and reproducibility by providing clear documentation and organization of the codebase. Please note that data and models will not be published, and the project is still ongoing.
