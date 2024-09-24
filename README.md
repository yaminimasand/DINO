# DINO
Dataset link:
https://drive.google.com/drive/folders/1DCpmo919b7OrAng9clEbiMHjO3D0hyoa?usp=sharing

Task Instructions:
1. Dataset Preparation:
Split the dataset into two sets: a training set with 160 images and a
validation set with 40 images.
2. Repository Setup:
Clone the DINO repository from <a href="https://github.com/IDEA-Research/DINO"> this link.</a> and set up the necessary
environment and dependencies as outlined in the repository
instructions.
3. GPU Access:
If you do not have access to a GPU locally, use platforms such as Google Colab or Kaggle to carry out the task.
4. Pre-trained Model:
Download the pre-trained DINO-4scale model with the ResNet-50 (R50) backbone from the provided link in the repository.
5. Validation:
Run evaluations on the validation set using the pre-trained weights, as COCO contains a "person" class relevant to this task. You will
need to adjust the config file to point to the correct dataset path. Follow the repository's instructions for running the evaluation script.
6. Report and Analysis:
Report the bounding box Average Precision (AP) values obtained from the validation set. Additionally, visualize the detection results and analyze any errors or cases where the model failed to detect objects correctly.
7. Fine-tuning:
Fine-tune the pre-trained model on the training set and re-evaluate the results on the validation set. You are free experiment any more methods which can help you improve your results.
