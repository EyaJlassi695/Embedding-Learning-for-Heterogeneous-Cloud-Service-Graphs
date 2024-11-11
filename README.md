# Embedding Learning for Heterogeneous Cloud Service Graphs

This project explores and implements embedding learning techniques for heterogeneous cloud service graphs using advanced Graph Neural Networks (GNNs). The aim is to map complex, cloud-based network graphs into low-dimensional, machine-readable representations for classification and clustering tasks. The project also employs data augmentation techniques using graphons to overcome data scarcity and enhance model robustness.

## Project Overview

- **Author**: Eya Jlassi
- **Supervisors**: Dr. Hayet Brabra (Telecom SudParis), Dr. Zacharie Ales (ENSTA Paris)
- **Academic Year**: 2024/2025
- **Institution**: Télécom SudParis

## Project Goals

1. **Graph Embedding**: Map heterogeneous graphs to low-dimensional vectors that capture structural information and semantics using:
   - Relational Graph Convolutional Networks (R-GCN)
   - Heterogeneous Graph Transformers (HGT)

2. **Data Augmentation**: Generate synthetic data through Graphon-based methods to enhance the dataset's volume and diversity, making the model more robust.

## Features

- **Embedding Techniques**: Implements R-GCN and HGT for transforming complex service graphs.
- **Data Augmentation**: Uses graphons for creating synthetic graphs to improve model generalization.
- **Classification and Clustering**: Evaluates embedding quality using classifiers and clustering algorithms.

## Project Structure

- **`src/`**: Source code implementing graph embedding, data augmentation, and model evaluation.
- **`data/`**: Dataset of cloud service graphs with node and edge files in CSV format.
- **`models/`**: Pre-trained models and training scripts.
- **`docs/`**: Project documentation and detailed report.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/EyaJlassi695/Autonomous-Car-Pathfinding.git
   cd Autonomous-Car-Pathfinding
   ```

2. **Install Dependencies**:
   - Python (>= 3.8)
   - PyTorch, PyTorch Geometric
   - Additional packages in `requirements.txt`:
     ```bash
     pip install -r requirements.txt
     ```

## Usage

1. **Prepare the Dataset**: Place node and edge files in the `data/` directory, structured by service categories.
2. **Run Embedding Models**:
   - Train the R-GCN or HGT model on the dataset:
     ```bash
     python src/train_model.py --model rgcn
     ```
3. **Evaluate and Visualize**:
   - Evaluate model performance with classifiers and clustering algorithms.
   - Visualize embeddings for training and test sets.

## Results

- **R-GCN**: Achieved high classification and clustering accuracy.
- **HGT**: Showed excellent performance in capturing heterogeneous relations.

## Project Documentation

Refer to the `docs/` folder for detailed information on:

- Graph embedding techniques
- Data augmentation with graphons
- Model architecture and evaluation metrics

## Acknowledgments

Special thanks to Dr. Hayet Brabra and Dr. Zacharie Ales for their invaluable support and guidance throughout this project.
