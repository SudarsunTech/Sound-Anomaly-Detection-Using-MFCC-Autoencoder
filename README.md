# Sound-Anomaly-Detection-Using-MFCC-Autoencoder

In the realm of industrial machinery, the detection of sound anomalies is of paramount importance for ensuring operational efficiency and safety. This paper presents a novel approach for sound anomaly detection employing Mel-frequency cepstral coefficients (MFCC) in conjunction with an Auto-Encoder model. The proposed method is designed to detect anomalies in four common industrial machinery components: conveyor.

Initially, audio data samples are transformed into MFCC feature vectors, which capture the spectral characteristics of the machinery sounds. An Auto-Encoder is then employed to encode and decode these MFCC features, effectively reconstructing the original audio data. The reconstruction error between the input and output of the Auto-Encoder serves as a crucial indicator of sound anomalies. Anomalies manifest as deviations from the expected reconstruction, enabling the model to identify and classify abnormal sound patterns.

The experimental results demonstrate the effectiveness of the proposed approach in accurately detecting anomalies in industrial machinery, providing a valuable tool for predictive maintenance, and ensuring the continuous, safe, and efficient operation of these critical components.
