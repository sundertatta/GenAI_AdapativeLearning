**LightweightFineTuningFoundationModel**


PEFT technique: LoRA (Low-Rank Adaptation) technique was used

Model: GPT2 Model was used as a base model

Evaluation approach: Evaluate method of Trainer class from Huggging Face was chosen More Specifically, compute_metrics method was overloaded which takes the mean of predicted value vs actual value

Fine-tuning dataset: duxprajapati/symptom-disease-dataset was chosen This is a data set which comprises symptoms in the "text" column and the actual disease in the "label" column; The objective is to predict a disease based on the symptoms
