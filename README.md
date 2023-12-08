# MLOps Projects

Hands-on MLOps projects to explore and learn the practical aspects of machine learning engineering for production.

| #   | Project                                                               | Description                                                                                                                                              |
| --- | --------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Deploying a Deep Learning model](01-deploying-a-deep-learning-model) | Rapid guide to deploying a computer vision model trained to identify common objects in images using YOLOv3 model and FastAPI.                            |
| 2   | [Birds, Cats, and Dogs](02-data-centric-approach)                     | Simple Convolutional Neural Network (CNN) addressing class imbalance and overfitting issues in a data-centric approach.                                  |
| 3   | [YouTube Spam](03-data-labeling)                                      | Simple classifier exploring how different labeling strategies affect machine learning model performance.                                                 |
| 4   | [Earnings Predictor](04-tensorflow-data-validation)                   | Introduction to generating and visualizing statistics, detecting and fixing anomalies in an evaluation dataset with TensorFlow Data Validation (TFDV).   |
| 5   | [Predicting Patient Readmission](05-data-validation)                  | In-depth look at TFDV to generate and visualize statistics from a dataframe, infer a dataset schema, calculate, visualize, and fix anomalies.            |
| 6   | [Hello World](06-simple-feature-engineering)                          | Simple feature engineering task to collect data, define metadata, create a preprocessing function, and generate a graph using TensorFlow Transform.      |
| 7   | [Earnings Predictor Pipeline](07-feature-engineering-pipeline)        | Machine learning pipeline using TensorFlow Extended (TFX) components: ExampleGen, StatisticsGen, SchemaGen, ExampleValidator, and Transform.             |
| 8   | [Traffic Volume Pipeline](08-feature-engineering)                     | Advanced feature engineering pipeline utilizing TFX components: data splitting, dataset analysis, validation, and transforms.                            |
| 9   | [Breast Cancer Features Analysis](09-feature-selection)               | Exploration of various feature selection techniques: correlation-based filtering, recursive feature elimination (RFE), and feature importance embedding. |
| 10  | [Chicago Taxi Metadata](10-ml-metadata)                               | Walkthrough of ML Metadata: recording and retrieving project metadata from a MetadataStore.                                                              |
| 11  | [Income Dataset Schemas](11-iterative-schema)                         | Deep dive into updating an inferred schema and storing the updated version in the TFX metadata store.                                                    |
| 12  | [Forest Cover Pipeline Components](12-data-pipeline-components)       | Production ML data pipeline: data ingestion, data validation, and data transformation.                                                                   |
| 13  | [Weather Data Transformation](13-time-series-data)                    | Feature engineering process to prepare seasonal data: handling time series, periodicity, and producing batches of dataset windows.                       |
| 14  | [Accelerometer Data Transformation](14-accelerometer-data)            | Preparation of raw sensor time-series data by grouping it into windows and extracting useful features.                                                   |
| 15  | [Image Data Transformation](15-image-data)                            | Image data preprocessing: parsing images and converting them into float arrays for feature engineering.                                                  |
| 16  | [Hyperparameter Tuning](16-keras-tuner)                               | Introduction to hyperparameter tuning with Keras Tuner: automate the search for optimal settings to enhance model performances.                          |
| 17  | [TFX Tuner and Model Training](17-tfx-tuner)                          | Introduction to hyperparameter tuning and model training with TFX.                                                                                       |
| 18  | [Manual Feature Engineering](18-manual-feature-engineering)           | Exploration of the impact of manually transforming raw features to improve predictions, using TensorFlow and Keras.                                      |

## Google Cloud Skills Boost Resources

| Type       | Title                                                                                                                        | Description                                                                                                              |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| **Lab**    | [A Tour of Google Cloud Hands-on Labs](https://www.cloudskillsboost.google/focuses/2794?parent=catalog)                      | Walkthrough of Google Cloud and the Qwiklabs platform.                                                                   |
| **Lab**    | [Classify Images of Clouds in the Cloud with AutoML Images](https://www.cloudskillsboost.google/focuses/8406?parent=catalog) | Hands-on lab introducing the AutoML UI for classifying images of clouds in the Google Cloud environment.                 |
| **Course** | [Integrate with Machine Learning APIs](https://www.cloudskillsboost.google/course_templates/630)                             | Hands-on course exploring basic features of the Cloud Vision API, Cloud Translation API, and Cloud Natural Language API. |

Based on [Machine Learning Engineering for Production (MLOps) Specialization](https://www.deeplearning.ai/courses/machine-learning-engineering-for-production-mlops/) by Andrew Ng, Laurence Moroney, and Robert Crowe (2023).
