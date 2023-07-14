
# Computer Vision Unicorn Gym 2023 Lab

In this CV Unicorn Gym we will through the steps required to prepare our data, train a model and deploy a model in Amazon SageMaker.

## Lab 1:  Data Labeling
In this lab, we will walkthrough to process to setup Amazon SageMaker GroundTruth and kick off a labelling job.

Additional resources
https://aws.amazon.com/getting-started/hands-on/machine-learning-tutorial-label-training-data/

## Lab 2: Data Augmentation
In some circumstances, we may not have sufficient data or an imbalance dataset to train our model. One way of addressing this is to introduce more data or up sample our minority dataset by performing image augmentation on our dataset. In this lab we will explore Amazon SageMaker DataWrangler image processing feature to perform data augmentation.

To begin, go to the `02_data_augmentation` folder and open the `01_image_augmentation.ipynb`  notebook.

Bonus Lab:
If you like to further techniques/libraries for performing image augmentation, go to `02a_training_pytorch`. In this lab, we will walkthrough an alternative approach of using the `Albumentations` library to perform image augmentation on images. In that lab, we will also walkthrough an end-to-end process in loading a pre-trained model and changing the last layer to adapt to our new dataset and classes for training.

## Lab 3: Training
In this lab, we will walkthrough the steps to prepare our data and train a model using Amazon SageMaker.

Follow the notebook from this folder "training/optional-prepare-data-and-model.ipynb"

## Lab 4: Model Deployment
In this final lab, we will walkthough the process of deploying a model using various inferencing mechanism offered by Amazon SageMaker.

Follow the notebook from this folder "deployment/sagemaker-deploy-model-for-inference.ipynb"