# Speech Emotion Recognition
## What is Speech Emotion Recognition?
Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. This is also the phenomenon that animals like dogs and horses employ to be able to understand human emotion.

SER is tough because emotions are subjective and annotating audio is challenging.

## What is librosa?
librosa is a Python library for analyzing audio and music. It has a flatter package layout, standardizes interfaces and names, backwards compatibility, modular functions, and readable code. Further, in this Python mini-project, we demonstrate how to install it (and a few other packages) with pip.

# Prerequisites
`pip install librosa soundfile numpy scikit-learn pyaudio`

```
import librosa
import soundfile
import os, glob, pickle
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.neural_network import MLPClassifier
from sklearn.metrics import accuracy_score
```

# Jupyter Lab
<img width="1016" alt="Screenshot 2024-04-01 at 5 10 04 PM" src="https://github.com/jessica-starbase/Speech-Emotion-Recognition/assets/125201668/d7d3586b-d94c-4246-bac6-e5db3ea1414b">
<img width="1099" alt="Screenshot 2024-04-01 at 5 12 23 PM" src="https://github.com/jessica-starbase/Speech-Emotion-Recognition/assets/125201668/080b6f48-e0d9-4b8c-ad54-41cffcc5f05b">
