# tes_adamata
Trial for Adamata ML Engineering Internship
TrashNet Dataset: https://huggingface.co/datasets/garythung/trashnet
EfficientNet B4: https://pytorch.org/vision/main/models/generated/torchvision.models.efficientnet_b4.html
Jupyter Notebook: https://colab.research.google.com/drive/15VcOcZDbgJe1KFCgQOdHgu_aqOLP0kVs?usp=sharing

HuggingFace Model: https://huggingface.co/Alfiano07/tes_adamata_trashnet/tree/main


The use of EfficientNet B4 for the TrashNet Dataset:
1. Split data into 85% Train & 15% Val data
2. Resize data into 224x224 to be trainable
3. Convert data to be a tensor type so it's trainable
4. Load the EfficientNet B4 model architecture & pretrained weights
5. Train data into the loaded model for 30-50 epochs
6. Visualize the results
