## Massachusetts General Hospital

### Overview
You are provided with synthetic data of approximately 1,000 patients from Massachusetts General Hospital, covering the years 2011 to 2022. The dataset includes information on patient demographics, insurance coverage, medical encounters, and procedures.

The link to the dataset is [here](https://maven-datasets.s3.amazonaws.com/Hospital+Patient+Records/Hospital+Patient+Records.zip).

Business problem: Given encounter data and patient data, predict the total claim cost.

Potential business use cases:
* Predicted total claim costs can be used as a quote at triage.
* Predictions can be sent ahead to insurance provider for pre-authorization or a more informal check if the patient still has credits.
* Total claim costs that are not comparable to predicted total claim cost can be audited by the insurance provider for potential cases of overutilization or unnecessary care leading to overbilling.