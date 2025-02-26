## This project is about using MLFLOW for ML project lifecycle

# Project Goal
The primary goal of this project is to leverage MLflow to streamline and enhance the machine learning lifecycle. By integrating MLflow into our workflow, I aim to :
1. Improve Experiment Tracking
2. Enhance Reproducibility
3. Simplify Model Management
4. Automate Model Deployment
5. Facilitate Collaboration and Scalability

By achieving these objectives, the project seeks to establish a robust, transparent, and efficient pipeline for developing, testing, and deploying machine learning models, ultimately reducing the time and effort required to move from experimentation to production.

Directory structure:
└── atharvaud29-mlflow_starter/
    ├── README.md
    ├── LICENSE
    ├── get-started.ipynb
    ├── requirements.txt
    ├── 1-MLproject/
    │   └── gettingstarted.ipynb
    ├── mlartifacts/
    │   └── 989302141365780316/
    │       ├── 3344bfc0a2704c31af67c909897c3518/
    │       │   └── artifacts/
    │       │       └── iris_model/
    │       │           ├── MLmodel
    │       │           ├── conda.yaml
    │       │           ├── input_example.json
    │       │           ├── model.pkl
    │       │           ├── python_env.yaml
    │       │           ├── requirements.txt
    │       │           └── serving_input_example.json
    │       ├── 3a1698cedcba46b9b53831c812f83b2c/
    │       │   └── artifacts/
    │       │       └── iris_model/
    │       │           ├── MLmodel
    │       │           ├── conda.yaml
    │       │           ├── input_example.json
    │       │           ├── model.pkl
    │       │           ├── python_env.yaml
    │       │           ├── requirements.txt
    │       │           └── serving_input_example.json
    │       ├── 99b9a4e13f374a17b43e89970c971db7/
    │       │   └── artifacts/
    │       │       └── iris_model/
    │       │           ├── MLmodel
    │       │           ├── conda.yaml
    │       │           ├── input_example.json
    │       │           ├── model.pkl
    │       │           ├── python_env.yaml
    │       │           ├── requirements.txt
    │       │           └── serving_input_example.json
    │       ├── def992ab1327477699b82ecd9331eba9/
    │       │   └── artifacts/
    │       │       └── iris_model/
    │       │           ├── MLmodel
    │       │           ├── conda.yaml
    │       │           ├── input_example.json
    │       │           ├── model.pkl
    │       │           ├── python_env.yaml
    │       │           ├── requirements.txt
    │       │           └── serving_input_example.json
    │       └── ec27f3b1b15f42af88939b1d91ca3e0b/
    │           └── artifacts/
    │               └── iris_model/
    │                   ├── MLmodel
    │                   ├── conda.yaml
    │                   ├── input_example.json
    │                   ├── model.pkl
    │                   ├── python_env.yaml
    │                   ├── requirements.txt
    │                   └── serving_input_example.json
    └── mlruns/
        ├── 0/
        │   └── meta.yaml
        ├── 857122109708159347/
        │   ├── meta.yaml
        │   ├── 671ca9a60cbf439797116b75ce5440fb/
        │   │   ├── meta.yaml
        │   │   ├── metrics/
        │   │   │   ├── Atharva1
        │   │   │   └── test1
        │   │   └── tags/
        │   │       ├── mlflow.runName
        │   │       ├── mlflow.source.name
        │   │       └── mlflow.source.type
        │   ├── 6d975a2893bd45dbb931f4dc8f365afb/
        │   │   ├── meta.yaml
        │   │   ├── metrics/
        │   │   │   ├── Atharva
        │   │   │   └── test
        │   │   └── tags/
        │   │       ├── mlflow.runName
        │   │       ├── mlflow.source.name
        │   │       └── mlflow.source.type
        │   └── cf09ad0ccb854e449652a812fa0e12d9/
        │       ├── meta.yaml
        │       ├── metrics/
        │       │   ├── Atharva2
        │       │   └── test2
        │       └── tags/
        │           ├── mlflow.runName
        │           ├── mlflow.source.name
        │           └── mlflow.source.type
        ├── 989302141365780316/
        │   ├── meta.yaml
        │   ├── 3344bfc0a2704c31af67c909897c3518/
        │   │   ├── meta.yaml
        │   │   ├── metrics/
        │   │   │   └── accuracy
        │   │   ├── params/
        │   │   │   ├── max_iter
        │   │   │   ├── multi_class
        │   │   │   ├── random_state
        │   │   │   └── solver
        │   │   └── tags/
        │   │       ├── Training Info
        │   │       ├── mlflow.log-model.history
        │   │       ├── mlflow.runName
        │   │       ├── mlflow.source.name
        │   │       └── mlflow.source.type
        │   ├── 3a1698cedcba46b9b53831c812f83b2c/
        │   │   ├── meta.yaml
        │   │   ├── metrics/
        │   │   │   └── accuracy
        │   │   ├── params/
        │   │   │   ├── max_iter
        │   │   │   ├── multi_class
        │   │   │   ├── penalty
        │   │   │   ├── random_state
        │   │   │   └── solver
        │   │   └── tags/
        │   │       ├── Training Info
        │   │       ├── mlflow.log-model.history
        │   │       ├── mlflow.runName
        │   │       ├── mlflow.source.name
        │   │       └── mlflow.source.type
        │   ├── 8254297ff37b47e9927e3b03d25f8d53/
        │   │   ├── meta.yaml
        │   │   └── tags/
        │   │       ├── mlflow.runName
        │   │       ├── mlflow.source.name
        │   │       └── mlflow.source.type
        │   ├── 99b9a4e13f374a17b43e89970c971db7/
        │   │   ├── meta.yaml
        │   │   ├── metrics/
        │   │   │   └── accuracy
        │   │   ├── params/
        │   │   │   ├── max_iter
        │   │   │   ├── multi_class
        │   │   │   ├── random_state
        │   │   │   └── solver
        │   │   └── tags/
        │   │       ├── Training Info
        │   │       ├── mlflow.log-model.history
        │   │       ├── mlflow.parentRunId
        │   │       ├── mlflow.runName
        │   │       ├── mlflow.source.name
        │   │       └── mlflow.source.type
        │   ├── def992ab1327477699b82ecd9331eba9/
        │   │   ├── meta.yaml
        │   │   └── tags/
        │   │       ├── mlflow.log-model.history
        │   │       ├── mlflow.runName
        │   │       ├── mlflow.source.name
        │   │       └── mlflow.source.type
        │   ├── ec27f3b1b15f42af88939b1d91ca3e0b/
        │   │   ├── meta.yaml
        │   │   ├── metrics/
        │   │   │   └── accuracy
        │   │   ├── params/
        │   │   │   ├── max_iter
        │   │   │   ├── multi_class
        │   │   │   ├── random_state
        │   │   │   └── solver
        │   │   └── tags/
        │   │       ├── Training Info
        │   │       ├── mlflow.log-model.history
        │   │       ├── mlflow.runName
        │   │       ├── mlflow.source.name
        │   │       └── mlflow.source.type
        │   └── f0dddd5460274ff1a1c2824e871ecf9c/
        │       ├── meta.yaml
        │       └── tags/
        │           ├── mlflow.runName
        │           ├── mlflow.source.name
        │           └── mlflow.source.type
        └── models/
            └── tracking-quickstart/
                ├── meta.yaml
                ├── aliases/
                │   └── bestmodel
                ├── version-1/
                │   └── meta.yaml
                ├── version-2/
                │   ├── meta.yaml
                │   └── tags/
                │       └── production
                ├── version-3/
                │   ├── meta.yaml
                │   └── tags/
                │       └── success
                └── version-4/
                    └── meta.yaml
