# Enhancing End-to-End Automatic Speech Recognition with Bayesian Optimisation and Audio Augmentation

This coursework investigates the enhancement of end-to-end automatic speech recognition (ASR) systems through advanced model optimisation and data augmentation techniques. A Long Short-Term Memory (LSTM) network is trained using the Connectionist Temporal Classification (CTC) loss, eliminating the need for precise phoneme-level alignments. The study applies Bayesian optimisation to efficiently explore a hyperparameter space of 650 configurations, reducing optimisation time by 58% compared to traditional grid search. Furthermore, novel audio augmentation methods, including speed perturbation and noise superposition, are employed to regularise large models and improve generalisation. Experiments reveal that deeper Bi-LSTM architectures paired with combined regularisation and augmentation techniques outperform alternative approaches, achieving a significant reduction in Phone Error Rate (PER). These findings demonstrate the synergistic impact of combining implicit and explicit regularisation strategies, setting a foundation for future advancements in ASR systems.
