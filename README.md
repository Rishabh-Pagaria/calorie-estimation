# Multi-Modal Deep Learning for Calorie Estimation
This project implements a novel multi-modal deep learning approach for estimating lunch calorie intake. The model integrates Convolutional Neural Networks (CNNs) for processing food images and Long Short-Term Memory (LSTM) networks for analyzing Continuous Glucose Monitoring (CGM) data. <br>
# Key Features
<ul>
  <li>Multi-modal architecture integrating CNNs and LSTMs</li>
  <li>Custom fusion network for combining features from multiple data modalities</li>
  <li>Implemented in Python using deep learning frameworks</li>
  <li>Achieves a validation Root Mean Squared Relative Error (RMSRE) of 0.3701</li>
</ul> <br>
# Model Architecture
<ol>
  <li><strong>CNN Encoder:</strong> Processes food images (breakfast and lunch)</li>
  <li><strong>LSTM Encoder:</strong> Analyzes CGM time-series data</li>
  <li><strong>Fusion Network:</strong> Combines features from CNN and LSTM encoders</li>
  <li><strong>Fully Connected Layers:</strong> Produce final calorie prediction</li>
</ol><br>

