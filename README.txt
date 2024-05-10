---------------------------------------------------------
  Folder Structure
---------------------------------------------------------
CW_Folder_PG/
|-- Code/
|   |-- Training.ipynb                                      # Grid search and train models
|   |-- Testing.ipynb                                       # Test models performance, using whole test set
|   |-- Tools.ipynb                                         # Libraries and functions
|   |-- Models.ipynb                                        # Models structure and pipelines
|   |-- face_detection_yunet_2023mar.onnx                   # Yunet model file for face detection
|-- models/                                                 # Saved trained models for evaluation
|   |-- SVM-HOG/
|   |-- SVM-SIFT/
|   |-- Custom-CNN/
|   |-- Pretrained-CNN/
|-- CW_Dataset/                                          
|   |-- CV2024_CW_Dataset.zip                               # Source dataset
|   |-- esrgan_train_imgs.zip                               # Processed training set with ESRGAN
|-- Video/                                                  # Video files
|   |-- Video1.mp4
|-- test_functions.ipynb                                    # Test files to evaluate models with 4 random testing images, and video
|-- requirements.txt                                        # Libraries and dependencies
|-- Video-Result-FaceMaskDetection.mp4                      # Processed video with face mask detection results
