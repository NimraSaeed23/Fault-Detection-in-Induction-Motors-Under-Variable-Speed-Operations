From existing literature, conventional fault diagnosis approaches in an Induction Motor struggle to reliably identify fault patterns at different speeds, 
particularly under variable speed and changing load conditions. 
To resolve this issue, this paper presents a unique hybrid Convolutional Neural Network along with the Long Short-Term Memory for diagnosing faulty patterns 
in motor under loaded and unloaded variable speed settings. 
The proposed method can identify faults such as rotor imbalances, misalignment, stator winding issues, voltage imbalances, broken rotor bars, and broken bearings. 
Experiments performed using the University of Ottawa Electric Motor Dataset – Vibration and Acoustic Faults under Constant and Variable Speed Conditions dataset 
reveal that all three accelerometers are 99.93% accurate at constant speed and 99.96% at variable speed under both loaded and unloaded conditions. 


To summarize, the major contributions of our work are as follows.
1) Data from different sensors is segmented to classify the different fault patterns at the same time.
2) The proposed hybrid CNN-LSTM successfully classifies the Induction motors different faults with an accuracy of 99.96%, including electrical and mechanical for
different speeds and load condition on CWRU and UOEMD-VAFCVS dataset.
3) The consistency of the proposed model is validated through several runs and k-fold validation.
4) An extensive comparison with recent state of the art work is presented in terms of accuracy, F1 score computational cost.
