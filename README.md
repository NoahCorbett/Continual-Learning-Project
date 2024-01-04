# 3rd CLVision CVPR Project



## Overview

This gitlab project is based on the CLVision 3rd edition [devkit](https://github.com/ContinualAI/clvision-challenge-2022) which primarly includes the avalanche library and starting templates for the challenge track. In addition there are the models I developed base_model_instance_classification.py and new_model_instance_classification.py As well as the smaller dataset json ego_objects_demo_test - 15 classes.json and ego_objects_demo_test - 15 classes.json

## Requirements

torch~=1.13.1 <br/>
scikit-learn~=0.24.1 <br/>
numpy~=1.20.1 <br/>
torchvision~=0.14.1 <br/>
pathlib~=1.0.1 <br/>
pytorchcv~=0.0.67 <br/>
pillow~=8.2.0 <br/>
lvis~=0.5.3 <br/>
pycocotools~=2.0.6 <br/>
setuptools~=52.0.0 <br/>
matplotlib~=3.3.4 <br/>
tqdm~=4.59.0 <br/>
quadprog~=0.1.11 <br/>
typing_extensions~=3.7.4.3 <br/>
gdown~=4.6.4 <br/>
torchmetrics~=0.11.4 <br/>
psutil~=5.8.0 <br/>
gputil~=1.4.0 <br/>
wandb~=0.13.11 <br/>




## To run the code

- [ ] Download the [demo dataset](https://forms.gle/bGXCHxcGRPaTcKPg6)
- [ ] Move ego_objects_demo_test - 15 classes.json and ego_objects_demo_test - 15 classes.json to the same directory as the json files for the demo dataset
- [ ] Rename the DATASET_PATH to the path location to the dataset directory for both base_model_instance_classification.py and new_model_instance_classification.py
- [ ] Rename TRAINING_JSON and TESTING_JSON to the names of the dataset set you want to run in base_model_instance_classification.py or new_model_instance_classification.py
- [ ] Run base_model_instance_classification.py or new_model_instance_classification.py

