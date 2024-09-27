This repository contains the code used to calculate the performance metrics of Faster R-CNN and YOLOv8. Inference was run on both models in separate Jupyter notebooks, allowing for a detailed comparison of their performance.

- YOLOv8_EE_GPU contains the ipynb file of the notebook used for evaluating YOLOv8
- FASTER_RCNN_EE_GPU contains the ipynb file of the notebook used for evaluating Faster RCNN

Key Features

- Notebooks Structure: The code is organized in cell format, enabling you to run individual cells separately rather than executing the entire notebook at once. This allows for flexible experimentation and adjustments as needed.
- Performance Metrics Calculation: The same notebook used for calculating mAP was also used to compute other metrics, such as precision, recall, and F1 score, with adjustments made only to the confidence threshold.
- Resource Utilization: To write and debug the code, I utilized various resources including: Forums: Reddit, Stack Overflow, and Stack Exchange for troubleshooting and guidance. Blogs: GeeksforGeeks and other technical blogs for understanding libraries and coding concepts. AI Tools: ChatGPT and Microsoft Copilot for debugging assistance and refining the code.

I used these notebooks for various purposes, including debugging and ensuring everything was functioning as expected. Some cells were specifically used to format the data for calculations. I calculated precision, recall, F1 score, AP, and gathered true positives, false positives, and true negatives for each class individually. These results were then exported to Excel, where I summed the true positives, false positives, and false negatives to obtain aggregate values. From that I calculated overall precision, recall, and F1 score, and mAP from the mean of the APs. Average IoU was calculated as the mean of all the IoUs from the matches, and average times were determined by averaging across all predictions.
