# Incremental Disentanglement for Environment-Aware Zero-Shot Text-to-Speech Synthesis
### Ye-Xin Lu, Hui-Peng Du, Zheng-Yan Sheng, Yang Ai, Zhen-Hua Ling

**Abstract:** 
This paper proposes IDEA-TTS, an Incremental Disentanglement-based Environment-Aware zero-shot text-to-speech (TTS) method that can synthesize speech for unseen speakers while preserving the acoustic characteristics of a given environment reference speech.
IDEA-TTS adopts VITS as the TTS backbone.
To effectively disentangle the environment, speaker, and text factors, we propose an incremental disentanglement process, where an environment estimator is designed to first decompose the environmental spectrogram into an environment mask and an enhanced spectrogram.
The environment mask is then processed by an environment encoder to extract environment embeddings, while the enhanced spectrogram facilitates the subsequent disentanglement of the speaker and text factors with the condition of the speaker embeddings, which are extracted from the environmental speech using a pretrained environment-robust speaker encoder.
Finally, both the speaker and environment embeddings are conditioned into the decoder for environment-aware speech generation.
Experimental results demonstrate that IDEA-TTS achieves superior performance in the environment-aware TTS task, excelling in speech quality, speaker similarity, and environmental similarity.
Additionally, IDEA-TTS is also capable of the acoustic environment conversion task and achieves state-of-the-art performance.

**We will provide our implementation as open source in this repository after paper acceptance.**
Audio samples can be found [here](http://yxlu-0102.github.io/IDEA-TTS).
