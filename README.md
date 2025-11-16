# CLiFT-ASR
CLiFT-ASR, a crosslingual fine-tuning framework for low-resource Automatic Speech Recognition that
- leverages Mandarin HuBERT backbone models and progressively adapts them to Taiwanese Hokkien
- employs a two-stage process in which it first learns acoustic and tonal representations from phonetic Tai-lo annotations and then captures vocabulary and syntax from Han-character transcriptions. This progressive adaptation enables effective alignment between speech sounds and orthographic structures.

Experiments on the TAT-MOE corpus demonstrate that CLiFT-ASR achieves a 24.88% relative reduction in character error rate (CER) compared with strong baselines. The results indicate that CLiFT-ASR provides an effective and parameter-efficient solution for Taiwanese Hokkien ASR and that it has potential to benefit other low-resource language scenarios.

All training procedures followed Icefall’s official recipes and default settings, with adjustments made according to the training scripts.

## Prerequisites
Before running the training script, please ensure that you have installed Icefall and its dependencies. 
