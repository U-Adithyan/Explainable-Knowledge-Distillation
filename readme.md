# Explainable- KD: Deep Learning Final Project
## Team Members
- U Adithyan: CS23BTNCL11001
- Shiv Tikoo: CS23BTNRK11001
## Note
- The coding was done on Kaggle, and the file names needs to be changed to run on local machine.
- The public data used was is avilable at https://www.kaggle.com/datasets/huanghanchina/pascal-voc-2012
- The saved models can be found in Models folder (zipped due to size).
## File Descriptions
- Teacher.ipynb: This file contains the code for the teacher model (ResNet18) being finetuned of PascalVOC20212 data.
- Vanilla Student.ipynb: This file contains the code for the student model (MobileNetV2) being finetuned of PascalVOC20212 data.
- KD.ipynb: This file contains the code for the student model (MobileNetV2) being finetuned of PascalVOC20212 data using Knowledge Distillation.
- Explainable KD.ipynb: This file contains the code for the student model (MobileNetV2) being finetuned of PascalVOC20212 data using Knowledge Distillation with Explainability.
- Performance Metric.ipynb: This file contains the code for the proposed performance metric calculation.
- Detour Metric.ipynb: This file contains the code for the proposed detour metric calculation using the proposed method.
- gradcam-plotting.ipynb: This file contains the code for the gradcam plotting.
