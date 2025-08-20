# Wheat XAI Project
This project is about using Explainable Artificial Intelligence (XAI) on a multimodal model (both SNP and UAV-imagery data) to uncover insights into the factors that influence wheat yeild.
The purpose of this project is to assist wheat breeders to make more informed decisions about crop selection, contributing a solution to the global food security challenge.
This repo contains the following:

## BLGR MODEL
This is our baseline model to determine how well yeild can be modelled based on SNP data alone, using a Bayseian-lasso statistical model.

## SNP MACHINE LEARNING (NN) MODEL
A unimodal Neural Network based on SNP data only

## IMAGE MACHINE LEARNING (CNN) MODEL
A unimodal Convolutional Neural Network based on UAV-image data only

## MULTIMODAL MACHINE LEARNING (CNN) MODEL
By pulling layers from the unimodal models, and tying them together with dense/dropout layers, a multimodal model (utilising both SNP and image data) is developed

## XAI (SHAP) ANALYSES
These are in progress, being done within the model notebooks.
