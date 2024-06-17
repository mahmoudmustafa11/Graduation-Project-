# Diagnosing burn cases through image processing in MATLAB

## Description

We have developed an automated diagnosis system using MATLAB that can determine the degree of a burn through image classification. The system uses medical images of burns and classifies them using advanced algorithms to extract features that help doctors classify the burn severity and decide on the optimal treatment. The project aims to assist doctors in accurately and quickly determining burn degrees by analyzing images with Discrete Wavelet Transform (DWT) techniques and energy calculation.

## User Interface

![User Interface](./imgs/interface.PNG)

## Contents

- [Description](#Description)
- [Features](#Features)
- [How to use](#How-to-use)
- [Files and Structure](#Files-and-Structure)
- [Requirements](#Requirements)
- [Install](#Install)
- [Contributions](#Contributions)
- [Communication](#Communication)
- [Meet Our Team](#Meet-Our-Team)

## Features

- Image analysis using DWT
- Diagnosing the degree of burns (first, second, third degree)
- Simple and easy to use user interface
- High accuracy in classifying burn degrees
- Ability to handle a large database of images
- The possibility of training the system on new images to improve performance

## How-to-use

1. Click the “load Image” button to load the burn image.
   ![Load Image Button](./imgs/interface_img.PNG)

2. Click the “training images” button to analyze the images in the database and wait a few seconds.
   ![Training Images Button](./imgs/training_images.png)

3. Click the “Diagnosis of the degree of burn” button to see the burn score of the uploaded image.
   ![Diagnosis Button](./imgs/diagnosis-of-the-degree-of-burn.png)

4. The burn degree result will appear in the listbox.
   ![Result Listbox](./imgs/result.png)

5. Click the “close” button to exit the program.
   ![Close Button](./imgs/close.png)

## Files-and-Structure

```
.
├── database/                     # A folder containing database images
├── save/                         # Folder to save the results
├── plant.mat                     # File containing features extracted from database images
├── untitled.m                    # The main file to run the project
├── untitled.fig                  # Home User Interface File
├── untitled.asv                  # Automatic backup file that MATLAB creates to save a backup copy of working files
├── Graduation project booklet    # The book on the project
└── README.md                     # Project documentation file
```

## Requirements

- MATLAB
- MATLAB version 2016 or higher
- Matlab's following libraries :
  - Wavelet Toolbox

## Install

1. Reproduce the warehouse :

   ```sh
   git clone https://github.com/mahmoudmustafa11/Graduation-Project-
   ```

2. Open Matlab and go to the cloned folder.
3. Run the main file `untitled.m`.

## Contributions

Currently, we are not accepting contributions to this project. If you have any suggestions or find any issues, please feel free to open an issue for discussion, but please note that pull requests are not being accepted at this time.

## Communication

If you have any questions or inquiries, you can contact us me via :

[melshahat799@gmail.com](mailto:melshahat799@gmail.com)

## Meet-Our-Team

#### George Wagih Alper Nicola

- **Role:** Programmer
- **Responsibilities:** Developed the functionality for loading images and exiting the program.
- **Contact:** [georgewagih21@gmail.com](mailto:georgewagih21@gmail.com)

#### Rewan Nasser Ibrahim El-Shawadfi

- **Role:** Programmer
- **Responsibilities:** Implemented feature extraction from stored images using DWT, calculated energy, and saved features to plant.mat.
- **Contact:** [rewanelshawadfy774@gmail.com](mailto:rewanelshawadfy774@gmail.com)

#### Eman Mohammed Kedra

- **Role:** Programmer
- **Responsibilities:** Implemented feature extraction from stored images using DWT, calculated energy, and saved features to plant.mat.
- **Contact:** [eman.kedra55@gmail.com](mailto:eman.kedra55@gmail.com)

#### Mahmoud Mustafa Elshahat

- **Role:** Programmer
- **Responsibilities:** Implemented feature extraction from stored images using DWT, calculated energy, and saved features to plant.mat.
- **Contact:** [melshahat799@gmail.com](mailto:melshahat799@gmail.com)

#### Ahmed Hamdi Mostafa

- **Role:** Programmer
- **Responsibilities:** Implemented the classification of burns using Euclidean distance to compare feature vectors and determine the burn degree.
- **Contact:** [ahmedhamdi5561@gmail.com](mailto:ahmedhamdi5561@gmail.com)

#### Fatma El-Zahraa Darwish

- **Role:** Programmer
- **Responsibilities:** Implemented the classification of burns using Euclidean distance to compare feature vectors and determine the burn degree.
- **Contact:** [ffaattmmaalzhraaa@gmail.com](mailto:ffaattmmaalzhraaa@gmail.com)

#### Farida Mohammed Mohammed Abdallah Ali

- **Role:** Programmer
- **Responsibilities:** Implemented the classification of burns using Euclidean distance to compare feature vectors and determine the burn degree.
- **Contact:** [fareedamohammed852@gmail.com](mailto:fareedamohammed852@gmail.com)

#### Arafa Ahmed Arafat

- **Role:** Database Administrator
- **Responsibilities:** Responsible for managing and organizing third-degree burn images in the database.
- **Contact:** [arafa4111999@gmail.com](mailto:arafa4111999@gmail.com)

#### Mohammed Mostafa Ibrahim Abdel Monaem

- **Role:** Database Administrator
- **Responsibilities:** Responsible for managing and organizing first-degree burn images in the database.
- **Contact:** [mohamedmym86@gmail.com](mailto:mohamedmym86@gmail.com)

#### Maryam Wael Abdel Fattah Abdel Samie

- **Role:** Database Administrator
- **Responsibilities:** Responsible for managing and organizing second-degree burn images in the database.
- **Contact:** [mariamwael2219@gmail.com](mailto:mariamwael2219@gmail.com)

#### Asmaa Ebrahim Rizk

- **Role:** UI/UX Designer
- **Responsibilities:** Designed the user interface and ensured proper functionality and user experience for the program.
- **Contact:** [bdwyasma2@gmail.com](mailto:bdwyasma2@gmail.com)

#### Faisal Mahmoud Hassan

- **Role:** Project Documentation
- **Responsibilities:** Assisted in writing and reviewing the graduation project booklet.
- **Contact:** [faisal.mahmoud369@gmail.com](mailto:faisal.mahmoud369@gmail.com)

#### Maryam Ahmed Omran Ahmed Al-Qenawy

- **Role:** Project Documentation
- **Responsibilities:** Authored the graduation project booklet and compiled all research references.
- **Contact:** [mariammran111@gmail.com](mailto:mariammran111@gmail.com)

#### Maryam Galal Abdel Rafie Elshami

- **Role:** Project Documentation
- **Responsibilities:** Contributed to writing and organizing the graduation project booklet.
- **Contact:** [maryoma10elshamy@gmail.com](mailto:maryoma10elshamy@gmail.com)

<!--
## Get-to-know-our-team

- [Ahmed Hamdi Mostafa](mailto:ahmedhamdi5561@gmail.com)
- [Asmaa Ebrahim Rizk](mailto:bdwyasma2@gmail.com)
- [Eman Mohammed Kedra](mailto:eman.kedra55@gmail.com)
- [George Wagih Alper Nicola](mailto:georgewagih21@gmail.com)
- [Rewan Nasser Ibrahim El-Shawadfi](mailto:rewanelshawadfy774@gmail.com)
- [Arafa Ahmed Arafat](mailto:arafa4111999@gmail.com)
- [Fatma El-Zahraa Darwish](mailto:ffaattmmaalzhraaa@gmail.com)
- [Farida Mohammed Mohammed Abdallah Ali](mailto:fareedamohammed852@gmail.com)
- [Faisal Mahmoud Hassan](mailto:faisal.mahmoud369@gmail.com)
- [Mohammed Mostafa Ibrahim Abdel Monaem](mailto:mohamedmym86@gmail.com)
- [Mahmoud Mostafa Elshahat](mailto:melshahat799@gmail.com)
- [Maryam Ahmed Omran Ahmed Al-Qenawy](mailto:mariammran111@gmail.com)
- [Maryam Galal Abdel Rafie Elshami](mailto:maryoma10elshamy@gmail.com)
- [Maryam Wael Abdel Fattah Abdel Samie](mailto:mariamwael2219@gmail.com)

 -->
