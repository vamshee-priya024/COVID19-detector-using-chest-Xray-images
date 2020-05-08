# COVID19-detector-using-chest-Xray-images
A deep learning model is built using transfer learning with dataset as sample of an open source dataset of X-ray images for patients who have tested positive for COVID-19 and sample “normal” (i.e., not infected) X-ray images from healthy patients and train a CNN to automatically detect COVID-19 in X-ray images via the dataset we created.

DATASET:
The COVID-19 X-ray image dataset we’ll be using for this tutorial was curated by Dr. Joseph Cohen, a postdoctoral fellow at the University of Montreal.
The next step was to sample X-ray images of healthy patients.
To do so, I used Kaggle’s Chest X-Ray Images (Pneumonia) dataset and sampled 25 X-ray images from healthy patients (Figure 2, right). There are a number of problems with Kaggle’s Chest X-Ray dataset, namely noisy/incorrect labels, but it served as a good enough starting point for this proof of concept COVID-19 detector.
