# Semantic-segmentation-using-UNet


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
    </li>
    <li>
      <a href="#tools">Tools</a>
    </li>
    <li><a href="#data">Usage</a></li>
    <li><a href="#methodology">Methodology</a></li>
    <li><a href="#results">Results</a></li>
  </ol>
</details>

### Introduction

The development time of new drugs is a long and complex process with different stages of analysis and screening. In most of the analysis stage, the first step is the detection of cells' nuclei. This allows researchers to identify the individual cells in a sample because most of the cells contain a nucleus filled with DNA (Deoxyribonucleic acid). Identification of cell nuclei help measure the reactions of cells when exposed to various treatments and lead to understanding the biological process underlying the work. This process is laborious and slow because it requires the identification and analysis of thousands of images at a time. Deep learning can help in automating this step and speeding up the analytical process. The model used to detect nuclei is a UNet neural network.

### Tools:
Python 3, Tensorflow, OpenCV, Numpy

### Data:
Data Science Bowl 2018 dataset contains images of nuclei cells with their annotation masks in seprate images for training, and a test dataset to test the trained model.

### Methodology:
UNet evolved from the traditional convolutional neural network. It was designed first in 2015 to process biomedical images. It has a "U" shape and its architecture is symmetric, consists of two major parts; the left part is called contracting path, which constituted by convolutional networks (encoder), the right part is expansive path, which constituted by transposed 2D convolutional layers (decoder).

### Results
The network achieved an accuracy of 97.0%.




In biomedical research, you are not only required to distinguish whether there is a disease, but also to localise the area of abnormality. UNet is able to solve this problem, as it is performs classification on every pixel, so the input & the output share the same size.
