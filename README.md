This script demonstrates how to perform face detection and recognition using deep neural network (DNN)-based models converted to ONNX format. It uses OpenCV's FaceDetectorYN for face detection and FaceRecognizerSF for face recognition, both of which are pre-trained and loaded from ONNX files. The script compares a reference image (e.g., Aadhaar card photo) with a query image to determine if they belong to the same person by computing cosine similarity and L2 norm distance.
