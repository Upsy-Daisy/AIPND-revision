This **README** provides detailed about the project details and results.


**Image Classification for a City Dog Show**
A Python Programming Nanodegree Project

**Project Description**
Uses pre-trained CNN models (AlexNet, VGG, and ResNet) to classify dog images and breeds.

**Files Included**
 `check_images.py` - Main program
`get_input_args.py` - Command line argument parser
`get_pet_labels.py` - Pet label extractor
`classify_images.py` - Image classifier
`adjust_results4_isadog.py` - Dog/not-dog classifier
`calculates_results_stats.py` - Statistics calculator
`print_results.py` - Results printer
`classifier.py` - CNN classifier (provided)
`dognames.txt` - Dog breed names (provided)

**How to Run**
```bash
# Run all models at once
sh run_models_batch.sh

# Run with AlexNet model
python check_images.py --arch alexnet

# Run with VGG model
python check_images.py --arch vgg

# Run with ResNet model
python check_images.py --arch resnet
```
Results

![1760795035671](https://github.com/user-attachments/assets/79cd5f8e-8c57-4883-876b-e4141cf88644)

![1760796685083](https://github.com/user-attachments/assets/3ddffaa8-998a-4896-84cd-0458d0705874)

![1760796908280](https://github.com/user-attachments/assets/d633d33c-71d4-4062-afde-87c23bf0d449)

![1760796818631](https://github.com/user-attachments/assets/1f6d8e74-7d6b-4e58-a711-644bc8a89493)

**Conclusion: VGG provides the best overall performance for this classification task.**
