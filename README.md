# Social-Cue-Analysis-for-Human-Robot-Interaction
Social Cue Analysis for Human-Robot Interaction


# Project structure
```
/ProjectRoot
    /Modules (Features)
        /Vision (Feature)
            /Data (Datasets and Preprocessed Data)
            /FacialExpression (Sub-feature)
                - models.py (Model definitions and training scripts)
                - preprocessing.py (Data preprocessing and augmentation)
                - inference.py (Inference and testing scripts)
            /EyeGaze (Sub-feature)
                - models.py
                - preprocessing.py
                - inference.py
            /BodyPose (Sub-feature)
                - models.py
                - preprocessing.py
                - inference.py
        /Sound (Feature)
            /Data (Datasets and Preprocessed Data)
            /VoiceTone (Sub-feature)
                - models.py
                - preprocessing.py
                - inference.py
            /SpeechContent (Sub-feature)
                - models.py
                - preprocessing.py
                - inference.py
    /Integration
        - integration.py (Script for integrating outputs from all modules)
        - visualization.py (Scripts for visualizing the overall state)
    /Utils
        - utils.py (Common utility functions)
```
