# Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project
## Acute Lymphoblastic Leukemia Fast AI 2020


---
title: Order example
---
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses





![Acute Lymphoblastic Leukemia Tensorflow 2020](Media/Images/Peter-Moss-Acute-Myeloid-Lymphoblastic-Leukemia-Research-Project.png)

[![CURRENT RELEASE](https://img.shields.io/badge/CURRENT%20RELEASE-0.0.0-blue.svg)](https://github.com/AMLResearchProject/ALL-FastAI-2020/tree/0.0.0) [![UPCOMING RELEASE](https://img.shields.io/badge/CURRENT%20DEV%20BRANCH-0.1.0-blue.svg)](https://github.com/AMLResearchProject/ALL-FastAI-2020/tree/0.1.0) [![Contributions Welcome!](https://img.shields.io/badge/Contributions-Welcome-lightgrey.svg)](CONTRIBUTING.md)  [![Issues](https://img.shields.io/badge/Issues-Welcome-lightgrey.svg)](issues) [![LICENSE](https://img.shields.io/badge/LICENSE-MIT-blue.svg)](LICENSE)

&nbsp;

# Table Of Contents

- [Introduction](#introduction)
- [DISCLAIMER](#disclaimer)
- [Getting Started](#getting-started)
  - [Hardware](#hardware)
  - [Software](#software)
  - [Clone the repository](#clone-the-repository)
    - [Developer Forks](#developer-forks)
- [ALL-IDB](#all-idb)
  - [ALL_IDB1](#all_idb1)
- [FastAI Classifier Projects](#fastai-classifier-projects)
- [Contributing](#contributing)
  - [Contributors](#contributors)
- [Versioning](#versioning)
- [License](#license)
- [Bugs/Issues](#bugs-issues)

&nbsp;

# Introduction
A series of Acute Lymphoblastic Leukemia CNNs programmed in Python using FastAI. Project by team member [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli").

&nbsp;

# DISCLAIMER

These projects should be used for research purposes only. The purpose of the projects is to show the potential of Artificial Intelligence for medical support systems such as diagnosis systems.

Although the classifiers are accurate and show good results both on paper and in real world testing, they are not meant to be an alternative to professional medical diagnosis.

Salvatore Raieli is a bioinformatician researcher and PhD in Immunology, but does not work in medical diagnosis. Please use these systems responsibly.

Please use this system responsibly.

&nbsp;

# Getting Started 

To get started there are some things you need to collect:

## Hardware

These tutorials were run on Google Colab.

## Software

In this project I used Python 3, FastAI.

## Clone the repository

Clone the [ALL FastAI 2020](https://github.com/AMLResearchProject/ALL-FastAI-2020 " ALL FastAI 2020") repository from the [Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project](https://github.com/AMLResearchProject "Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project") Github Organization.

To clone the repository and install the ALL FastAI 2020 classifiers, make sure you have Git installed. Now navigate to the home directory on your device using terminal/commandline, and then use the following command.

```
  $ git clone https://github.com/AMLResearchProject/ALL-FastAI-2020.git
```

Once you have used the command above you will see a directory called **ALL-FastAI-2020** in your home directory.

```
ls
```

Using the ls command in your home directory should show you the following.

```
ALL-FastAI-2020
```

Navigate to **ALL-FastAI-2020/Projects/** directory, this is your project root directory for this tutorial.

### Developer Forks

Developers from the Github community that would like to contribute to the development of this project should first create a fork, and clone that repository. For detailed information please view the [CONTRIBUTING](CONTRIBUTING.md "CONTRIBUTING") guide. You should pull the latest code from the development branch.

```
  $ git clone -b "0.1.0" https://github.com/AMLResearchProject/ALL-FastAI-2020.git
```

The **-b "0.1.0"** parameter ensures you get the code from the latest master branch. Before using the below command please check our latest master branch in the button at the top of the project README.

## ALL-IDB

You need to be granted access to use the Acute Lymphoblastic Leukemia Image Database for Image Processing dataset. You can find the application form and information about getting access to the dataset on [this page](https://homes.di.unimi.it/scotti/all/#download) as well as information on how to contribute back to the project [here](https://homes.di.unimi.it/scotti/all/results.php). If you are not able to obtain a copy of the dataset please feel free to try this tutorial on your own dataset, we would be very happy to find additional AML & ALL datasets.

### ALL_IDB1 

In this project, [ALL-IDB1](https://homes.di.unimi.it/scotti/all/#datasets) is used, one of the datsets from the Acute Lymphoblastic Leukemia Image Database for Image Processing dataset. We will use data augmentation to increase the amount of training and testing data we have.

"The ALL_IDB1 version 1.0 can be used both for testing segmentation capability of algorithms, as well as the classification systems and image preprocessing methods. This dataset is composed of 108 images collected during September, 2005. It contains about 39000 blood elements, where the lymphocytes has been labeled by expert oncologists. The images are taken with different magnifications of the microscope ranging from 300 to 500."  

&nbsp;

# FastAI Classifier Projects

| Model  | Project                                                                                                                                                                                     | Description                           | Status  | Author                                                                                                                                                                                     |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Resnet | [FastAI Resnet18 Classifier](Projects/ALL_FastAI_Resnet_18.ipynb "FastAI Resnet18 Classifier")         | A FastAI model trained using Resnet18 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| Resnet | [FastAI Resnet34 Classifier](Projects/ALL_FastAI_Resnet_34.ipynb "FastAI Resnet34 Classifier")         | A FastAI model trained using Resnet34 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| Resnet | [FastAI Resnet50 Classifier](Projects/ALL_FastAI_Resnet_50.ipynb "FastAI Resnet50 Classifier")         | A FastAI model trained using Resnet50 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| Resnet | [FastAI Resnet101 Classifier](Projects/ALL_FastAI_Resnet_101.ipynb "FastAI Resnet101 Classifier")         | A FastAI model trained using Resnet101 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| Resnet | [FastAI Resnet152 Classifier](Projects/ALL_FastAI_Resnet_152.ipynb "FastAI Resnet152 Classifier")         | A FastAI model trained using Resnet152 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| AlexNet | [FastAI AlexNet Classifier](Projects/ALL_FastAI_AlexNet.ipynb "FastAI AlexNet Classifier")         | A FastAI model trained using AlexNet | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| Densenet | [FastAI Densenet121 Classifier](Projects/ALL_FastAI_Densenet121.ipynb "FastAI Densenet121 Classifier")         | A FastAI model trained using Densenet121 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| Densenet | [FastAI Densenet161 Classifier](Projects/ALL_FastAI_Densenet161.ipynb "FastAI Densenet161 Classifier")         | A FastAI model trained using Densenet161 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| Densenet | [FastAI Densenet169 Classifier](Projects/ALL_FastAI_Densenet169.ipynb "FastAI Densenet169 Classifier")         | A FastAI model trained using Densenet169 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| Densenet | [FastAI Densenet201 Classifier](Projects/ALL_FastAI_Densenet201.ipynb "FastAI Densenet201 Classifier")         | A FastAI model trained using Densenet201 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| SqueezeNet | [FastAI SqueezeNet_1_0 Classifier](Projects/ALL_FastAI_SqueezeNet_1_0.ipynb "FastAI SqueezeNet_1_0 Classifier")         | A FastAI model trained using SqueezeNet_1_0 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| SqueezeNet | [FastAI SqueezeNet_1_1 Classifier](Projects/ALL_FastAI_SqueezeNet_1_1.ipynb "FastAI SqueezeNet_1_1 Classifier")         | A FastAI model trained using SqueezeNet_1_1 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| VGG | [FastAI VGG16 Classifier](Projects/ALL_FastAI_VGG16.ipynb "FastAI VGG16 Classifier")         | A FastAI model trained using VGG16 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |
| VGG | [FastAI VGG19 Classifier](Projects/ALL_FastAI_Densenet201.ipynb "FastAI VGG19 Classifier")         | A FastAI model trained using VGG19 | Complete | [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") |

&nbsp;

# Contributing

The Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research project encourages and welcomes code contributions, bug fixes and enhancements from the Github.

Please read the [CONTRIBUTING](CONTRIBUTING.md "CONTRIBUTING") document for a full guide to forking our repositories and submitting your pull requests. You will also find information about our code of conduct on this page.

## Contributors

- [Salvatore Raieli](https://www.leukemiaresearchassociation.ai/team/salvatore-raieli  "Salvatore Raieli") - [Asociacion De Investigation En Inteligencia Artificial Para La Leucemia Peter Moss](https://www.leukemiaresearchassociation.ai "Asociacion De Investigation En Inteligencia Artificial Para La Leucemia Peter Moss") Bioinformatics & Immunology AI R&D, Bologna, Italy

&nbsp;

# Versioning

We use SemVer for versioning.

&nbsp;

# License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE.md "LICENSE") file for details.

&nbsp;

# Bugs/Issues

We use the [repo issues](issues "repo issues") to track bugs and general requests related to using this project. See [CONTRIBUTING](CONTRIBUTING.md "CONTRIBUTING") for more info on how to submit bugs, feature requests and proposals.
