# BentoML_Tutorial

In this tutorial, we'll learn the basics about BentoML, an open tool that help in the model deployment task. More information about the tool can be found in the following links:

- Original webpage: https://docs.bentoml.org/en/latest/index.html
- Git repository: https://github.com/bentoml/BentoML

## Quick start

1. Clone the code into your local machine.
2. Install the dependencies, there are two options:
    - Conda: Create and install a conda environment using the *conda.yaml* file
    - Requirements: install all the requirements under the *requirements.txt* file.
3. Edit and run the `train.py` script in order to get a trained model and saved into bentoml.
4. Edit the `service.py` script to configure a BentoML Service.
5. Execute the following command, inside `/src`: `bentoml serve service.py:clf --reload`
6. Send new data to your service with the `predict.py` script.
