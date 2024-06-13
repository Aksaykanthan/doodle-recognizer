# Doodle Recognizer

This project is a Doodle Recognizer that can identify hand-drawn doodles of various objects such as cars, bicycles, trees, clocks, houses, guitars, pencils, and fish. The project was developed using vanilla JavaScript without any external modules.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Data Collection](#data-collection)
- [Feature Extraction](#feature-extraction)
- [Algorithms](#algorithms)
- [References](#references)

## Overview

The Doodle Recognizer uses machine learning algorithms to classify drawings into predefined categories. The project involves the following steps:
1. Data collection through a web interface.
2. Feature extraction from the collected drawings.
3. Classification using K-Nearest Neighbors (KNN) and Multi-Layer Perceptron (MLP) algorithms.

## Features

- Recognizes the following objects:
  - Car
  - Bicycle
  - Tree
  - Clock
  - House
  - Guitar
  - Pencil
  - Fish
- Data collection via a web-based canvas.
- Feature extraction based on shape metrics such as elongation, roundness, height, and width.
- Convex Hull calculation using Graham Scan algorithm.
- Classification using KNN and MLP algorithms.

## Data Collection

Data was collected from our classmates using a web interface hosted on Firebase. Participants were asked to draw the specified objects on a canvas. The drawings were then stored in Firebase for further processing.

## Feature Extraction

Several features were extracted from the drawings to aid in classification:
- **Elongation**: Measures how stretched the shape is.
- **Convex Hull**: Calculated using the Graham Scan algorithm to find the outer boundary of the drawing.
- **Roundness**: Indicates how circular the shape is.
- **Height and Width**: The dimensions of the drawing.

## Algorithms
- **Graham Scan**: To find the outer boundary of the drawing
Two machine learning algorithms were implemented to classify the drawings:
- **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm.
- **Multi-Layer Perceptron (MLP)**: A neural network-based algorithm.

## References

- [K-Nearest Neighbors Algorithm](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
- [Multi-Layer Perceptron](https://en.wikipedia.org/wiki/Multilayer_perceptron)
- [Graham Scan Algorithm](https://en.wikipedia.org/wiki/Graham_scan)
- [Firebase Documentation](https://firebase.google.com/docs)
- [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [Javascript canvas and MLP](https://www.youtube.com/@Radu)
