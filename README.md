# Sport Recognition Project (in progress)

## Overview

This project focuses on recognizing different sports based on **motion patterns** in video sequences. Using **Convolutional Neural Networks (CNN)** followed by a **Gated Recurrent Unit (GRU)**, the model analyzes video inputs to classify sports based on the movements of participants. The aim is to perform **action recognition** specifically through motion cues, without relying on additional visual or contextual information.

## Features

- **Data:** Uses the [UCF Sports Action Data Set](https://www.crcv.ucf.edu/data/UCF_Sports_Action.php), which includes 150 video sequences (resolution: 720 x 480) collected from broadcast channels like BBC and ESPN. The dataset covers a variety of sports actions in diverse scenes and perspectives, making it ideal for studying action recognition in real-world environments.
  
- **Methods:** Implements **Convolutional Neural Networks (CNN)** to extract spatial features from video frames, followed by **GRU (Gated Recurrent Unit)** layers to capture temporal dependencies in motion sequences.
  
- **Parameters:** Analyzes key motion patterns (e.g., speed, direction, posture) to differentiate sports.

- **Applications:** Can be applied to **action recognition**, **action localization**, and **saliency detection** in videos, particularly in unconstrained and complex environments.

## Usage

To replicate the model, follow setup instructions, data preprocessing steps, and execute the model for sports recognition.

## Contributing

Contributions are welcome. Please follow the provided guidelines for contributing.

## License

This project is open-source and is licensed under the [MIT License](LICENSE), allowing free use, modification, and distribution for personal and commercial purposes.
