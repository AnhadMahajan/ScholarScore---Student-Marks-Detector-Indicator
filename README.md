# ScholarScore - Student Marks Indicator

This project is a web application that predicts student marks based on various features. It uses a machine learning model to make predictions and provides a user-friendly interface to interact with the model.

## Features

*   Predicts student marks based on input features.
*   Provides a web interface for easy interaction.
*   Includes a data processing pipeline for cleaning and transforming data.
*   Uses a CatBoost model for prediction.

## Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/ScholarScore---Student-Marks-Detector-Indicator.git
    ```
2.  Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  Run the application:
    ```bash
    python app.py
    ```
2.  Open your web browser and navigate to `http://127.0.0.1:5000`.

## Technologies Used

*   Python
*   Flask
*   CatBoost
*   Scikit-learn
*   Pandas
*   Numpy

## Project Structure

```
├── app.py
├── requirements.txt
├── setup.py
├── artifacts/
├── catboost_info/
├── logs/
├── Notebook/
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │   └── train_pipeline.py
│   ├── __init__.py
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
└── templates/
    ├── index.html
    └── home.html
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
