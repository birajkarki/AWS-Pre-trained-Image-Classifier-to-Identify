# Udacity_AI_Projects
# Project: Use a Pre-trained Image Classifier to Identify Dog Breeds

## Overview
This project utilizes a pre-trained image classifier to identify dog breeds. The classifier incorporates popular architectures like VGG, AlexNet, and ResNet. VGG is known for its simplicity and effectiveness with variants like VGG11, VGG16, and VGG19. AlexNet, a 2012 breakthrough, showcases the power of deep learning with 8 layers. ResNet introduces residual learning, addressing vanishing gradient issues in deep networks, with variants such as ResNet18, ResNet34, ResNet50, etc. This README provides essential information to understand, use, and contribute to the project.

## Getting Started
### Prerequisites
- Python 3.x
- Required libraries (see `requirements.txt`)

## Model Details
The image classifier is built on the vgg, resnet and alexnet model architectures, trained on the pet_images and uploaded_images dataset. For additional details on the model architecture and training process, refer to [link to documentation or model details].


## Project Structure
- **pet_images:** Folder containing 40 sample pet images.
- **uploaded_images:** This is a folder containing a test dataset of four images -- Dog_1.jpeg (image of a dog), Dog_2.jpeg (Dog_01.jpeg 180° flipped/ upside down), bucket_01.jpeg (image of an object), Polar_bear_01.jpeg (image of animal that isn't a dog).
- **classifier.py:** Classifier function for image classification.
- **dognames.txt:** List of valid dog names from the classifier function and pet image files.
- **imagenet1000_clsid_to_human.txt:** Dictionary converting classifier function IDs to text labels.
- **adjust_results4_isadog.py:** Program with the `adjust_results4_isadog` function.
- **calculates_results_stats.py:** Program with the `calculates_results_stats` function.
- **classify_images.py:** Program with the `classify_images` function.
- **get_input_args.py:** Program with the `get_input_args` function.
- **get_pet_labels.py:** Program with the `get_pet_labels` function.
- **print_results.py:** Program with the `print_results` function.
- **run_models_batch.bat:** Batch script to run check_images.py for all 3 model architectures on Windows.
- **run_models_batch_uploaded.bat:** Batch script to run check_images.py on uploaded images for all 3 model architectures on Windows.
- **test_classifier.py:** Example program demonstrating how to use the classifier function.
- **print_functions_for_lab_checks.py:** Program with functions to check your code.

## Running Batch Files on Windows OS Locally
To run batch files (`run_models_batch.bat` or `run_models_batch_uploaded.bat`) on Windows:
1. Open the Anaconda Prompt.
2. Navigate to the folder within the Anaconda Prompt that contains the Project files including check_images.py and run_models_batch.bat using the command cd.
3. Execute the batch file:
   ```bash
   run_models_batch.bat
   ```
   or
   ```bash
   run_models_batch_uploaded.bat
   ```

## Acknowledgments
- Credits to Udacity.
- Dataset source: AI Programming with Python: Project 1.
