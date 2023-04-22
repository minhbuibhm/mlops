# MLOps
## 1. Introducion to Machine Learning in Production.
- What MLOps is, get used to 4 stages in MLOps: Scoping, Data, Modeling, Deploying.
- Deployment: challenges in data/concept drift or software engineering; architecture/patterns (shadow mode, Blue Green mode, canary mode); monitoring (including software metrics, input metrics, output metrics).
- Modeling: challenges in business metrics vs project goal; test accuracy is not enough; important accuracy in rare classes; iterative error analysis; last step is audit performance (brainstorm some problems such as gender, ethnicity, condition of input devices).
- Data iteration: data-centric approach; define data and establish baseline; label (improve label consistency) and organize data (data and metadata).
- Scoping: brainstorm business problems and AI solutions to assess the feasibility; consider ethical considerations; consider milestones and resources.
- Try deploying on local the model (YOLOv3) using fastAPI.

## 2. Machine Learning Data Lifecycle in Production: Understanding and implementing data pipeline with TFX.
> Understanding and implementing data pipeline with TFX: 
- Ingesting data.
- Generating statistics from Csv or dataframe or data ingested.
- Generating schema from statistics (types, categories and ranges).
- Validating anomalies from the statistics and the schema and try to fix anomalies by looking at the description of data from schema and stiatistics.
- Transform the data ingested (feature engineering).

## 3. Machine Learning Modeling Pipelines in Production (Progress: 1/5)
- Understand and try using Keras tuner, AutoML; get used to gcloud bucket and some APIs.
- ...
