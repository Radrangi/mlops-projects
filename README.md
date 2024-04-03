# MLOps Projects

Hands-on MLOps projects to explore and learn the practical aspects of machine learning engineering for production.

| #   | Project                                                                          | Description                                                                                                                                              |
| --- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Deploying a Deep Learning model](01-deploying-a-deep-learning-model)            | Rapid guide to deploying a computer vision model trained to identify common objects in images using YOLOv3 model and FastAPI.                            |
| 2   | [Birds, Cats, and Dogs](02-data-centric-approach)                                | Simple Convolutional Neural Network (CNN) addressing class imbalance and overfitting issues in a data-centric approach.                                  |
| 3   | [YouTube Spam](03-data-labeling)                                                 | Simple classifier exploring how different labeling strategies affect machine learning model performance.                                                 |
| 4   | [Earnings Predictor](04-tensorflow-data-validation)                              | Introduction to generating and visualizing statistics, detecting and fixing anomalies in an evaluation dataset with TensorFlow Data Validation (TFDV).   |
| 5   | [Predicting Patient Readmission](05-data-validation)                             | In-depth look at TFDV to generate and visualize statistics from a dataframe, infer a dataset schema, calculate, visualize, and fix anomalies.            |
| 6   | [Hello World](06-simple-feature-engineering)                                     | Simple feature engineering task to collect data, define metadata, create a preprocessing function, and generate a graph using TensorFlow Transform.      |
| 7   | [Earnings Predictor Pipeline](07-feature-engineering-pipeline)                   | Machine learning pipeline using TensorFlow Extended (TFX) components: ExampleGen, StatisticsGen, SchemaGen, ExampleValidator, and Transform.             |
| 8   | [Traffic Volume Pipeline](08-feature-engineering)                                | Advanced feature engineering pipeline utilizing TFX components: data splitting, dataset analysis, validation, and transforms.                            |
| 9   | [Breast Cancer Features Analysis](09-feature-selection)                          | Exploration of various feature selection techniques: correlation-based filtering, recursive feature elimination (RFE), and feature importance embedding. |
| 10  | [Chicago Taxi Metadata](10-ml-metadata)                                          | Walkthrough of ML Metadata: recording and retrieving project metadata from a MetadataStore.                                                              |
| 11  | [Income Dataset Schemas](11-iterative-schema)                                    | Deep dive into updating an inferred schema and storing the updated version in the TFX metadata store.                                                    |
| 12  | [Forest Cover Pipeline Components](12-data-pipeline-components)                  | Production ML data pipeline: data ingestion, data validation, and data transformation.                                                                   |
| 13  | [Weather Data Transformation](13-time-series-data)                               | Feature engineering process to prepare seasonal data: handling time series, periodicity, and producing batches of dataset windows.                       |
| 14  | [Accelerometer Data Transformation](14-accelerometer-data)                       | Preparation of raw sensor time-series data by grouping it into windows and extracting useful features.                                                   |
| 15  | [Image Data Transformation](15-image-data)                                       | Image data preprocessing: parsing images and converting them into float arrays for feature engineering.                                                  |
| 16  | [Hyperparameter Tuning](16-keras-tuner)                                          | Introduction to hyperparameter tuning with Keras Tuner: automate the search for optimal settings to enhance model performances.                          |
| 17  | [TFX Tuner and Model Training](17-tfx-tuner)                                     | Introduction to hyperparameter tuning and model training with TFX.                                                                                       |
| 18  | [Manual Feature Engineering](18-manual-feature-engineering)                      | Exploration of the impact of manually transforming raw features to improve predictions, using TensorFlow and Keras.                                      |
| 19  | [Algorithmic Dimensionality Reduction](19-algorithmic-dimensionality-reduction)  | Explore dimensionality reduction algorithms using PCA, SVD, and NMF for improved model performance.                                                      |
| 20  | [Quantization and Pruning](20-quantization-and-pruning)                          | Lab optimizing models for mobile and IoT devices using TF Lite format, post-training quantization, quantization aware training, and weight pruning.      |
| 21  | [Distributed Training](21-distributed-training)                                  | Explore distributed training in TensorFlow and Keras using a multi-worker training strategy.                                                             |
| 22  | [Knowledge Distillation](22-knowledge-distillation)                              | Discover model compression through knowledge distillation, where a smaller student model learns from a more complex teacher model.                       |
| 23  | [TensorFlow Model Analysis](23-tensorflow-model-analysis)                        | Dive into TensorFlow Model Analysis (TFMA) to analyze and visualize model performance across various data slices, set thresholds, and compare models.    |
| 24  | [TFX Evaluator](24-tfx-evaluator)                                                | Explore model analysis in the TFX pipeline using TFX Evaluator to ensure trained models meet metrics requirements and compare with previous models.      |
| 25  | [Fairness Indicators](25-fairness-indicators)                                    | Explore fairness metrics in a face image dataset using Fairness Indicators, analyzing model predictions across age groups.                               |
| 26  | [Shapley Values](26-shapley-values)                                              | Investigate SHAP (SHapley Additive exPlanations) by training a CNN and computing Shapley values for each class.                                          |
| 27  | [Permutation Feature Importance](27-permutation-feature-importance)              | Train a Random Forest classifier, compute feature importance, re-train with top features, and compare with other classifiers.                            |
| 28  | [Intro to Docker](28-intro-to-docker)                                            | Dive into the essential foundations for deploying Machine Learning models through Docker installation and curl setup.                                    |
| 29  | [TensorFlow Serving with Docker](29-tensorflow-serving-with-docker)              | Get a first look at using TensorFlow Serving with Docker, a straightforward introduction to this serving system for machine learning models.             |
| 30  | [Serve a Model with TensorFlow Serving](30-serve-model-with-tensorflow-serving)  | Explore TensorFlow Serving without Docker, gaining insights into installation, loading models, REST API interaction, and model versioning.               |
| 31  | [Deploy a ML model with fastAPI and Docker](31-deploy-fastapi-docker)            | Deploy a web server hosting a Random Forest classifier using FastAPI and Docker, exploring batching and single prediction endpoints.                     |
| 32  | [Practice Kubernetes in your Local Environment](32-kubernetes-local-environment) | Expand your Kubernetes skills: set up Minikube locally, create objects with YAML, deploy Tensorflow model servers, and explore autoscaling.              |
| 33  | [Load testing servers with Docker Compose and Locust](33-latency-test-compose)   | Conduct a load test on servers with Docker Compose and Locust, comparing latency across different batching configurations.                               |
| 34  | [ETL Pipelines and Batch Predictions](34-etl-apache-beam-tensorflow)             | Explore the ETL (Extract, Transform, Load) process with Apache Beam and TensorFlow.                                                                      |
| 35  | [Building ML Pipelines with Kubeflow](35-kubeflow-pipelines)                     | Hands-on experience with Kubeflow Pipelines for automating and orchestrating machine learning workflows.                                                 |
| 36  | [Developing Custom TFX Components](36-tfx-custom-components)                     | Learn to build custom components in TensorFlow Extended (TFX) for more flexible machine learning pipelines.                                              |
| 37  | [Model versioning with TensorFlow Serving and Docker](37-tfs-model-versioning)   | Learn to version machine learning models using TensorFlow Serving and Docker for controlled deployments and A/B testing.                                 |
| 38  | [Intro to CI/CD pipelines with GitHub Actions](38-github-actions)                | Explore GitHub Actions for automating ML workflows, including unit testing with pytest for code quality assurance.                                       |

## Google Cloud Skills Boost Resources

| Type       | Title                                                                                                                           | Description                                                                                                                                            |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Lab**    | [A Tour of Google Cloud Hands-on Labs](https://www.cloudskillsboost.google/focuses/2794?parent=catalog)                         | Walkthrough of Google Cloud and the Qwiklabs platform.                                                                                                 |
| **Lab**    | [Classify Images of Clouds in the Cloud with AutoML Images](https://www.cloudskillsboost.google/focuses/8406?parent=catalog)    | Hands-on lab introducing the AutoML UI for classifying images of clouds in the Google Cloud environment.                                               |
| **Course** | [Integrate with Machine Learning APIs](https://www.cloudskillsboost.google/course_templates/630)                                | Hands-on course exploring basic features of the Cloud Vision API, Cloud Translation API, and Cloud Natural Language API.                               |
| **Lab**    | [Running Distributed TensorFlow using Vertex AI](https://www.cloudskillsboost.google/focuses/21599?parent=catalog)              | Learn to deploy a distributed TensorFlow training pipeline using Vertex AI's MirrorStrategy and set up an endpoint for cloud-based online predictions. |
| **Lab**    | [Machine Learning with TensorFlow in Vertex AI](https://www.cloudskillsboost.google/focuses/3391?parent=catalog)                | Learn to develop a TensorFlow model in Vertex AI Workbench: train, create input data pipeline, deploy to an endpoint, and get predictions.             |
| **Lab**    | [Introduction to Docker](https://www.cloudskillsboost.google/focuses/1029?parent=catalog)                                       | Explore Docker basics, including container building, running, debugging, and image management with Google Artifact Registry.                           |
| **Lab**    | [Vertex AI Workbench Notebook: Qwik Start](https://www.cloudskillsboost.google/focuses/581?parent=catalog)                      | Hands-on introduction to TensorFlow model training, deployment on Vertex AI, and predicting income categories.                                         |
| **Lab**    | [Deploy a BigQuery ML Customer Churn Classifier to Vertex AI](https://www.cloudskillsboost.google/focuses/20069?parent=catalog) | Deploy a BigQuery ML XGBoost model to Vertex AI for online predictions, predicting user churn in a real mobile application dataset.                    |
| **Course** | [Deploy to Kubernetes in Google Cloud](https://www.cloudskillsboost.google/course_templates/663)                                | Learn about Google Kubernetes Engine, configure and build Docker containers, create clusters, and deploy applications.                                 |
| **Course** | [Advanced ML: ML Infrastructure](https://www.cloudskillsboost.google/course_templates/666)                                      | Advanced-level course covering machine learning at scale and leveraging advanced ML infrastructure tools on Google Cloud Platform.                     |
| **Lab**    | [Data Loss Prevention: Qwik Start - JSON](https://www.cloudskillsboost.google/focuses/600?parent=catalog)                       | Set up a JSON file, send it to the Data Loss Prevention API, inspect and hide sensitive information.                                                   |
| **Course** | [Automate Interactions with Contact Center AI](https://www.cloudskillsboost.google/course_templates/622)                        | Learn to build and design conversation flows, add phone gateways, use Dialogflow for troubleshooting, and review logs to debug virtual agents.         |
| **Course** | [Generative AI Fundamentals](https://www.cloudskillsboost.google/course_templates/556)                                          | Introduction to generative AI, covering fundamental concepts in generative AI, large language models, and responsible AI.                              |
| **Course** | [Analyze Images with the Cloud Vision API](https://www.cloudskillsboost.google/course_templates/633)                            | Learn to analyze images with the Cloud Vision API, including practical use cases such as reading text embedded in an image.                            |
| **Course** | [Analyze Speech and Language with Google APIs](https://www.cloudskillsboost.google/course_templates/634)                        | Explore real-world applications of Natural Language and Speech APIs for speech and language analysis.                                                  |
| **Course** | [Detect Manufacturing Defects using Visual Inspection AI](https://www.cloudskillsboost.google/course_templates/644)             | Master Visual Inspection AI to detect manufacturing defects by deploying solutions and testing their defect identification capabilities.               |
| **Course** | [Get Started with Looker](https://www.cloudskillsboost.google/course_templates/647)                                             | Learn how to analyze, visualize, and curate data using Looker Studio and Looker.                                                                       |
| **Course** | [Exploring Data with Looker](https://www.cloudskillsboost.google/course_templates/628)                                          | Explore data using Looker's interface, covering dimensions, measures, filtering, pivoting, and merging explores.                                       |
| **Course** | [Build LookML Objects in Looker](https://www.cloudskillsboost.google/course_templates/639)                                      | Learn to design and build LookML objects such as dimensions, measures, and views in Looker.                                                            |
| **Course** | [Predict Soccer Match Outcomes with BigQuery ML](https://www.cloudskillsboost.google/course_templates/656)                      | Explore sports data science fundamentals using BigQuery, including creating and analyzing a soccer dataset.                                            |
| **Course** | [Manage Data Models in Looker](https://www.cloudskillsboost.google/course_templates/651)                                        | Learn LookML best practices, optimize queries, and implement caching policies for effective data model management.                                     |
| **Course** | [Build and Deploy ML Solutions on Vertex AI](https://www.cloudskillsboost.google/course_templates/684)                          | Explore Google Cloud's Vertex AI platform for training, evaluating, tuning, explaining, and deploying machine learning solutions.                      |
| **Course** | [Insights from Data with BigQuery](https://www.cloudskillsboost.google/course_templates/623)                                    | Explore basic features of BigQuery, covering SQL queries, database table management, query troubleshooting, and creating reports in Looker.            |
| **Course** | [Create ML Models with BigQuery ML](https://www.cloudskillsboost.google/course_templates/626)                                   | Learn how to use BigQuery ML to create machine learning models, including classification, forecasting, and implementation of a chatbot.                |
| **Course** | [Build and Optimize Data Warehouses with BigQuery](https://www.cloudskillsboost.google/course_templates/624)                    | Transform your data warehouse with BigQuery, covering joins, unions, table partitioning, and working with JSON, arrays, and structs.                   |
| **Course** | [Foundational Data, ML, and AI Tasks in Google Cloud](https://www.cloudskillsboost.google/course_templates/631)                 | Explore basic features of Google Cloud's machine learning and AI technologies, covering BigQuery, Cloud Speech AI, Dataflow, Dataproc, and more.       |
| **Course** | [Vector Search and Embeddings](https://www.cloudskillsboost.google/course_templates/939)                                        | Learn about Vertex AI Vector Search and how to build search applications with large language model (LLM) APIs for embeddings.                          |

## Get Inspired

Check out our [collection of articles](https://www.onbusinessplan.com/) for those beginning their MLOps journey. Find tips, tricks, and motivational content to keep you engaged and motivated throughout your learning process.

## Acknowledgments

Based on [Machine Learning Engineering for Production (MLOps) Specialization](https://www.deeplearning.ai/courses/machine-learning-engineering-for-production-mlops/) by Andrew Ng, Laurence Moroney, and Robert Crowe (2023).

## Show Your Support

If you find these projects helpful or interesting, please consider starring the repository. It's a simple gesture that helps to boost the visibility of the project and show appreciation for the effort put into creating it. Thank you!
