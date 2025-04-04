# Medical Imaging Cardiac Segmentation Project

This repository contains four Jupyter notebooks implementing different models for cardiac segmentation on CT and MRI images.

## Notebooks

### Baseline Models
- **Benchmark_CorrectedDice(CT)_Final_NoRolloutAttention_HighResolution_Imaging_Final_Project.ipynb**  
  Baseline 3D-UNet model for CT image segmentation without attention mechanisms.

- **Benchmark_CorrectedDice(MRI)_Final_NoRolloutAttention_HighResolution_Imaging_Final_Project.ipynb**  
  Baseline 3D-UNet model for MRI image segmentation without attention mechanisms.

### Attention-Enhanced Models
- **CorrectedDice_Final_RolloutAttention(CT)_HighResolution_Imaging_Final_Project.ipynb**  
  Attention-enhanced 3D-UNet model for CT image segmentation with attention rollout capabilities.

- **CorrectedDice_Final_RolloutAttention(MRI)_HighResolution_Imaging_Final_Project.ipynb**  
  Attention-enhanced 3D-UNet model for MRI image segmentation with attention rollout capabilities.

## Usage

Each notebook is self-contained and can be run independently. They include data loading, model training, evaluation, and visualization of results.

The notebooks with attention rollout functionality provide additional visualizations of the model's attention maps, which can help understand how the model focuses on different cardiac structures.