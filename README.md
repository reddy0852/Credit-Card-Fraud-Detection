# Credit Card Fraud Detection using Autoencoders

This project demonstrates the use of deep autoencoders for detecting credit card fraud using TensorFlow and Keras. Autoencoders are employed to learn normal transaction patterns and detect anomalies, offering a potential solution to the highly imbalanced nature of fraud detection datasets.

## Project Highlights

- **Objective**: Detect credit card fraud using autoencoders and reconstruction errors.
- **Dataset**: Utilized credit card transaction data with imbalanced classes.
- **Approach**: Trained autoencoder on non-fraud transactions to learn normal patterns.
- **Evaluation**: Calculated reconstruction errors and applied threshold for fraud prediction.
- **Results**: Achieved efficient detection with controlled precision and recall.
- **Visualizations**: Generated graphs for error distribution and performance metrics.

## Usage

1. Install required dependencies: `pip install pandas numpy matplotlib seaborn tensorflow keras`.
2. Run the provided Python script to load and preprocess the dataset.
3. Train the autoencoder model using training data.
4. Evaluate the model on test data and analyze the results.

## Key Files

- `credit_card_fraud_detection.ipynb`: Jupyter Notebook containing the complete project.
- `model.h5`: Saved model for the trained autoencoder.
- `logs/`: Directory containing TensorBoard logs for visualization.

## Results

- Achieved accurate credit card fraud detection using autoencoders.
- Demonstrated precision-recall trade-offs through visualization of metrics.
- Highlighted potential for anomaly detection using threshold-based classification.

Feel free to explore the notebook for detailed implementation steps, visualizations, and results.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
