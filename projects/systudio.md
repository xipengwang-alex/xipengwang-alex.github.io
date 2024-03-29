---
layout: project
type: project
image: img/systudio/icon.png
title: "SyStudio"
date: Aug, 2022
published: true
labels:
  - Python
  - Autodesk Maya
  - MEL (Maya Embedded Language)
  - OpenCV
  - PyTorch
summary: "A synthetic data generation toolkit for general object detection applications."
---

<br>

<img class="img-fluid mx-auto d-block" src="../img/systudio/icon1.png">

<br>
The data collection processes can be costly and time-consuming when training any machine learning model. Our versatile and easy-to-use synthetic data generation pipeline tackles this issue by allowing users to generate photorealistic image data with pixel-perfect annotation. The user inputs the 3D model of the object and randomization parameters into the toolkit, and it generates any amount of synthetic data needed. 

As the primary author, I coordinated and overseed all aspects of the project.

Our synthetic data generation pipeline for SyStudio consists of a six-stage process that transforms 3D models into deployable computer vision models:
 - Model Initialization
 - Parameter Randomization
 - Rendering the Image and Annotation Extraction
 - Dataset Generation
 - Custom Training of YOLOv5 Object Detection Model
 - Evaluation and Iterative Improvement


The work was presented as a research talk during the 2023 Purdue <a href="https://www.purdue.edu/undergrad-research/conferences/spring/archive/documents/AbstractBooklet_Spring2023.pdf#page=442">Spring Undergraduate Research Conference</a>.

Citation:
Wang, X., Xu, M., Yu, G. (2023, April 13). Synthetic Data Generation for RoboMaster Armor Plate Detection [Oral
Presentation]. 2023 Purdue Spring Undergraduate Research Conference, West Lafayette, IN, United States.


Source: <a href="https://github.com/xipengwang-alex/synthetic-armorplate">xipengwang-alex/synthetic-armorplate</a>
