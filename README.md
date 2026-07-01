# Brain Tissue Segmentation Comparison between classical and Deep Learning approaches
This repository contains the implementation of a comparative analysis between unsupervised and deep learning-based methods for brain tissue segmentation from MRI volumes, developed for the Methods for Image Processing course (A.Y. 2025/2026, University of Milan)[cite: 1].

# Overview
Brain tissue segmentation is a fundamental task in neuroimaging, as the precise quantification of Gray Matter (GM), White Matter (WM), and Cerebrospinal Fluid (CSF) is essential for assessing brain health and monitoring neurodegenerative conditions such as Alzheimer’s disease, Parkinson’s, and Multiple Sclerosis.

However, accurate brain tissue segmentation remains a challenging task due to the nature of MRI signals: tissue intensity distributions often overlap in T1w images, and images are frequently affected by scanner noise, magnetic field inhomogeneities, and significant inter-subject anatomical variability. This project implements and evaluates a framework that contrasts a classical unsupervised approach (K-Means) with a supervised Deep Learning approach (3D U-Net), providing a comprehensive assessment of their performance in terms of Dice score, precision, and recall.
