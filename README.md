Overview:
The ICBHI dataset is designed to support research in biomedical signal processing, particularly focusing on respiratory sound classification. The dataset is commonly used for developing machine learning models for the classification of respiratory diseases. It contains audio recordings and associated metadata collected from patients with various respiratory conditions.

Contents:
The dataset includes the following components:

Respiratory Sound Recordings:

Audio files in .wav format.
Files contain breathing sounds with various respiratory cycles.
Recorded using a stethoscope at different locations (e.g., trachea, lung, etc.).
Annotations:

Class Labels: Labels for each recording, indicating the respiratory sound type (normal, wheezes, crackles, etc.).
Patient Information: Metadata about the patient, including age, gender, and diagnosis.
Recording Conditions: Information on the location and environment of the recording.

Features:
Precomputed features extracted from the audio files, such as Mel-frequency cepstral coefficients (MFCCs), spectral features, and time-domain statistics.

The research focuses on the benefits of using automation in the diagnosis of lung
disorders. The mortality rates for lung diseases have increased over the years. After
the COVID-19 pandemic, It has become extremely important that lung disorders are
diagnosed at an early stage for better chances of recovery. Researchers have developed various Machine Learning and Deep Learning models for accurately predicting
lung diseases. Various techniques such as CNN Models, LSTM models, and SVM
models have shown promising results. The main aim of the research is to investigate
if a hybrid model consisting of CNN, LSTM, and Attention layers would improve the
performance of the model significantly. MFCCs are computed for all the recordings
after data augmentation and then fed to each model. The models were then compared and evaluated on different metrics. The CNN model with LSTM performed
better than the baseline CNN Model and the hybrid attention model because of its
ability to capture temporal dependencies. Risk assessment was implemented using
the softmax function of the CNN+LSTM Model. Risk assessment furnishes healthcare establishments with valuable insights to enable them to distinguish between
patients with varying risk profiles. Research in this domain should be encouraged
Because automation improves diagnostic accuracy and consistency through objective data analysis and sophisticated algorithms. Automation also helps medical
professionals by lessening their workload and providing more access to cutting-edge
diagnostic tools, especially in underprivileged areas.
