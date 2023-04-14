# Music Generation with RNN

This is a project that generates music using Recurrent Neural Networks (RNNs). The project uses Python and TensorFlow to build a model that learns patterns in music data and generates new music based on those patterns.

## Getting Started

### Prerequisites

Before running the project, you need to have the following installed on your computer:

- Python (version 3.x)
- TensorFlow (version 2.x)

### Installation

1. Clone the repository using git clone https://github.com/Pramod858/Music-Generation-with-RNN.git.
2. Install the required packages
3. Run the Jupyter notebook using `jupyter notebook` command in the terminal.

### Dataset

The model was trained on the MIDI files of classical piano music. The dataset was obtained from MIDI World and ClassicalArchives.

### Model Architecture

The model uses a Recurrent Neural Network (RNN) with LSTM (Long Short-Term Memory) cells. The model is trained on sequences of notes and the corresponding time intervals between them. The architecture of the model is as follows:

- Input layer: Takes in the sequence of notes and time intervals
- LSTM layer: Learns the patterns in the data
- Dense layer: Generates the output (new sequence of notes and time intervals)

### Results
The model generates music that is similar in style to the music in the training data. The generated music can be saved as MIDI files played using a MIDI player or convert the generated MIDI file to WAV file and then play using a player.

## Conclusion
This project demonstrates the ability of Recurrent Neural Networks to generate music. The generated music can be used for various applications, such as music composition and video game soundtracks.

Happy coding!
