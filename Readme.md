# ML pipeline with Tensorflow

A prduction-ready ML pipeline using Tensorflow Extended (TFX), BigQuery, Apache Beam & Kubeflow on Google Cloud Platform. Components:
1. Data generation with BigQuery ExampleGen
2. Data streaming with Apache Beam
3. Generate schema using schemagen
4. Validator: Perform data validation
5. Transformer: Transform into usable input for training
6. Trainer: Train regression model
7. Evaluator: Evaluate model performance metrics on eval set
8. Pusher: Export model for serving
9. Kubeflow backend for orchestrating pipeline