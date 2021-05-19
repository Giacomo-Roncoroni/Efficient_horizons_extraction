# 1D Horizon Extraction

This github page refers to the article: Efficient extraction of seismic horizons with Deep Learning submitted to Computers & Geosciences

# Abstract

We propose a procedure for the interpretation of horizons in seismic reflection data based on a Neural Network (NN) approach, which can be at the same time fast, accurate and able to reduce the intrinsic subjectivity of manual or control-points based methods. The training is based on a Long Short Term Memory architecture and is performed on synthetic data obtained from a convolutional model-based scheme, while the extraction step can be applied to any type of field seismic dataset. Synthetic data are contaminated with different types of noise to improve the performance of the NN in a large variety of field conditions. We tested the proposed procedure on 2-D and 3-D synthetic and field seismic datasets. We have successfully applied the procedure also to Ground Penetrating Radar data, verifying its versatility and potential. The proposed algorithm is based on a fully 1-D approach and does not require the input of any interpreter, because the necessary thresholds are automatically estimated. An added benefit is that the prediction has an associated probability, which automatically quantifies the reliability of the results. 


In this repository you can find the Jupyter notebooks of the used codes, the trained model and the data used in the article.
