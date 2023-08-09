# CSC420 Project 

For a more detailed description of the project, please see the [final report](report/report.pdf).

## Summary
This project delves into super-resolution using deep learning techniques, focusing on the application of Delta-STN optimization to the SRResNet architecture. We also evaluate the effectiveness of transfer learning on a customized dataset, shedding light on dataset preparation, Delta-STN integration, and neural network implementation.

<!-- srgan_arch -->
#### SRGAN Architecture
![Alt text](report/srgan_arch.png?raw=true "SRGAN Architecture")

## Experiments
We preprocess a dataset of Pokémon images, employing data augmentation techniques to enhance model generalization and generate high-quality results. We explore two key architectures, SRGAN and SRResNet, where we fine-tune pretrained weights and integrate the Delta-STN optimization method.

Through qualitative and quantitative assessments on a series of test images, we showcase our approach's prowess in enhancing image quality and regularizing outputs. We also highlight noteworthy performance enhancements, including improvements in Mean Squared Error (MSE), Peak Signal-to-Noise Ratio (PSNR), and perceptual losses.

<!-- 039 -->
#### Sample Results
![Alt text](report/results/039.png?raw=true "039")
<!-- 066 -->
![Alt text](report/results/066.png?raw=true "066")
<!-- 327 -->
![Alt text](report/results/327.png?raw=true "327")
<!-- 384 -->
![Alt text](report/results/384.png?raw=true "384")
<!-- 681_f2 -->
![Alt text](report/results/681_f2.png?raw=true "681_f2")
<!-- 808 -->
![Alt text](report/results/808.png?raw=true "808")

## Conclusion
In navigating the complexities of super-resolution, our project combines Delta-STN optimization, transfer learning, and dataset preparation. The results underscore the potential for elevating image quality, regularization, and model performance in the realm of super-resolution.



<!-- ################################################## -->

## How to run the code
All of our data, models, and results are available at [this link](https://drive.google.com/file/d/1s_zOwZ4OHIkRV1jlK5hmWsmi1PnqS9RH/view?usp=sharing).

To perform training, download the following:
- Extract the ```superresolution_data.zip``` dataset and extract it into the ```data/``` and ```pretrained/``` folders.

After that, run the ```finetune.ipynb``` notebook.

## Team: Tree Wizards
Adam Adli, Linwen Huang, Jason Tang
