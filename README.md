# PREDICTION OF PATIENTS' LENGTH OF STAY IN AN ICU

## INSPIRATION

The length of stay in the ICU is an important metric for healthcare professional as it can impact patient outcomes and resource utilisation. In the United States, the average length of stay in the ICU is 3.3 days, with a median of 2.2 days. However, this can vary widely depending on the patient's condition, with some patients staying in the ICU for several weeks or even months. Also ,a longer stay can increase the risk of contracting a hospital acquired condition like a staph infection as well.In light of the current global health crisis, I strongly believe that equipping our healthcare professionals with AI functionalities will have a huge impact.

## METHODOLOGY

I have developed a model that predicts the length of stay for a patient admitted to the ICU, based on demographic, services, vitals and lab data, that is available within 24 hours of admission.The MIMIC-III dataset was extensively explored to understand the various aspects of an ICU stay that can affect the patients length of stay. I performed detailed research using medical reference literatures and speaking to medical experts to understand the data from a medical domain perspective. Further , the data was transformed using python to form our final dataset. The model was built using Azure AutoML, which allowed me to leverage a powerful cloud-based platform to automate the model training process.

