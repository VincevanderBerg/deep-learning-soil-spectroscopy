# Deep Learning Showcase: LUCAS Soil Spectroscopy

Welcome to the Deep Learning Showcase repository, featuring two cutting-edge projects from my coursework in Data Science and Artificial Intelligence at the University of London. These projects showcase my expertise in deep learning, specifically in the realm of soil spectroscopy using the LUCAS dataset. Python and Tensorflow were my tools of choice to complete these two projects.

## Coursework 1

### Objectives

This project aimed to unravel the potential of sequential neural networks on the LUCAS-dataset (Orgiazzi, et al., 2018) with the following objectives:

1. Determine an optimal sequential neural network architecture for modeling spectroscopic data and predict soil carbon.
2. Apply regularization techniques to enhance the model's generalisability.

### Key Findings

The final model outperformed the established PLSR method used in soil spectroscopy literature, achieving a commendable MAE of 9.45 g/kg. However, recognizing the significance of accurate soil quality predictions, there's a drive to develop a model with even greater precision.

Considering the sequential nature of spectroscopic data, this study acknowledges the potential of convolutional neural networks (CNN) and transformer networks, as highlighted by Padarian et al. (2019) and Lei and Sun (2022).

### Additional Insights

- Workflow included dimensionality reduction (PCR and PLSR) as preprocessing techniques. PLSR was favored over PCR for better performance.
- K-fold validation employed for robust model evaluation.
- The Huber loss function used for each neural network.

### Future Directions

To elevate this research, future investigations should explore:
- Advanced deep learning architectures such as CNN architectures.
- A more comprehensive search for optimal learning rates.
- Fine-tuning of layer and unit selection for an optimized architecture.

## Coursework 2

### Objectives

This study addressed the gap in evaluating multiple CNN architectures for predicting multiple soil properties simultaneously. Objectives included:

1. Evaluate three novel CNN architectures, two based on VGG and ResNet, and one using a hybrid CNN approach with fully connected neural layers.
2. Predict soil pH, carbon, nitrogen, and potassium contents from the LUCAS soil spectroscopy dataset.

### Key Outcomes

The RESNET-16-based model emerged as the top performer, outshining the other architectures and surpassing the multiple linear regression baseline for most target variables, except for soil pH.

### Recommendations and Limitations

Despite promising results, the study acknowledged limitations, including the use of a single dataset, limited exploration of CNN architectures, and a shallow analysis of hyperparameters. Recommendations for improvement include exploring additional neural network architectures, conducting a comprehensive hyperparameter search, and incorporating multiple datasets for broader generalizability.

### Future Work

To advance this research, future studies should consider:
- Exploring additional neural network architectures such as Transformers.
- Conducting a comprehensive hyper-parameter search.
- Including multiple datasets for improved generalisability.
- Investigating more effective approaches for modeling soil pH.

In summary, these projects showcase the potential of deep learning in soil spectroscopy. While significant strides have been made, the pursuit of optimal models and methodologies continues, setting the stage for future advancements in this exciting field.
