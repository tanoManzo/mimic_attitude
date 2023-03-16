# Caregiver Attitude Detection from Clinical Notes

This project aims to detect the attitudes of caregivers from their clinical notes. This repository contains all the notebooks used for the study.

## Installation

All notebooks work with Python 3.9. The required libraries are listed in the respective notebook, and can be installed using the following command:

~~~
pip install -r requirements.txt
~~~


## Usage

Notebooks **MIMIC_attitude_models_training_few_shot** and **MIMIC_attitude_models_training_few_shot** contain the code for training and fine-tuning the models for few-shot and full-trained scenarios, respectively.

Notebooks **zero_shot_mimic_sentiment** and **full_mimic_sentiment** contain the code for testing the zero-shot and full-trained models, respectively. The few-shot scenario can be tested using a smaller percentage of the dataset used in `full_mimic_sentiment`.

The evaluation of the testing results can be found in **zero_shot_mimic_sentiment_eval** and **full_mimic_sentiment_eval**, respectively. The same evaluation can be conducted for the few-shot scenario.

The graphs used in the paper are generated in **Graphs** and **ModelGraphs**.

Finally, the annotation agreement can be found in **AnnoAgreement**.

The Hugging Face APIs for using the models can be found here: https://huggingface.co/tanoManzo/

## License

The annotated data and the clinical notes follow the PhysioNet license. For information on the code token, please contact gaetano.manzo@nih.gov.
