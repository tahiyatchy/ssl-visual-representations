# Self-Supervised Visual Representation Learning with Mask Auto-Encoder
## Overview
This assignment was completed for the course Computer Vision at UNC Charlotte. With a dataset of only 2,400 images, we are tasked with developing a self-supervised model without the option to leverage externally pretrained weights.
The proposed model to address this problem jointly leverages self-supervision through mask auto-encoding, and partial supervision using a classification token. The best validation accuracy is 80.21%.

## Setup Guide

### Environment
* **IDE**: Google Colab
* **Hardware Accelerator**: A100 GPU High-RAM
* **Libraries:**: PyTorch 2.11

### Instructions to Execute
1. Create shortcut to <a href="https://drive.google.com/drive/folders/1NWC3TMsXSWN2TeoYMCjhf2N1b-WRDh-M">data folder</a> in Google Drive.
2. Open ssl_final_model.ipynb in Google Colab. Connect to a hosted runtime with a GPU hardware accelerator (A100 GPU recommended).
3. After mounting to Google Drive (code indicated by comment), change the variable <em>PATH</em> to your shortcut from Step 1.
4. Run all cells.
